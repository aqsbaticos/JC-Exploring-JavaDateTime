# Laboratory: Exploring Java Date and Time API
Developed by: Baticos, Andric Quinn S.

## Screenshot of Proof

---
### Exercise 1: `LocalDate` and `DateTimeFormatter`

**Code Snippet**

![Screenshot Proof](/ss/e1-cs.png?raw=true "exercise-1-code-snippet")

**Prediction**: _This code will output the default format of LocalDate.of(2025, 8, 21), '21/08/2025' and August 21, 2025._

**Output**

![Screenshot Proof](/ss/e1-o.png?raw=true "exercise-1-output")

**Observation**: _As expected, the program outputted a defaulted format 2025-08-21, 21/08/2025 and August 21, 2025. What I missed is that EEEE would print the day of the week as well._

---
### Exercise 2: `LocalTime` and `DateTimeFormatter`

**Code Snippet**

![Screenshot Proof](/ss/e2-cs.png?raw=true "exercise-2-code-snippet")

**Prediction**: _This code will output the default format of LocalTime.of(16, 45, 30), '16:45:30' and '04:45:30 PM'._

**Output**

![Screenshot Proof](/ss/e2-o.png?raw=true "exercise-2-output")

**Observation**: _As expected, the program outputted a defaulted format 16:45:30, 16:45:30 and 04:45:30 PM. What I missed is that EEEE would print the day of the week as well._

---
### Exercise 3: `LocalDateTime` and `DateTimeFormatter`

**Code Snippet**

![Screenshot Proof](/ss/e3-cs.png?raw=true "exercise-3-code-snippet")

**Prediction**: _This code will output the default format of LocalDateTime.of(2025, 11, 27, 19, 0, 0) and 'Nov 27, 2025 at 07:00 PM'._

**Output**

![Screenshot Proof](/ss/e3-o.png?raw=true "exercise-3-output")

**Observation**: _As expected, the program outputted a defaulted format of LocalDateTime.of(2025, 11, 27, 19, 0, 0) and 'Nov 27, 2025 at 07:00 PM'._

---
### Exercise 4: The Immutability of Date-Time Objects

**Code Snippet**

![Screenshot Proof](/ss/e4-cs.png?raw=true "exercise-4-code-snippet")

**Prediction**: _This code will output the default format of LocalDate.of(2025, 9, 1), an unedited LocalDate.of(2025, 9, 1) and LocalDate.of(2025, 19, 1)._

**Output**

![Screenshot Proof](/ss/e4-o.png?raw=true "exercise-4-output")

**Observation**: _As expected, the program outputted a defaulted format 2025-09-01, 2026-09-01, and 2025-09-11._

---
### Exercise 5: Adding and Subtracting Time (`plus` and `minus`)

**Code Snippet**

![Screenshot Proof](/ss/e5-cs.png?raw=true "exercise-5-code-snippet")

**Prediction**: _This code will output Present: '2025-10-15 10:30', Future: '2026-12-15 15:30', and Past: '2025-09-21 10:30'._

**Output**

![Screenshot Proof](/ss/e5-o.png?raw=true "exercise-5-output")

**Observation**: _As expected, the program outputted a 2025-10-15 10:30, 2026-12-15 15:30 and 2025-09-21 10:30._

---
### Exercise 6: Period - Measuring a Span of Time

**Code Snippet**

![Screenshot Proof](/ss/e6-cs.png?raw=true "exercise-6-code-snippet")

**Prediction**: _This code will output "The period between the two dates is: 2 years, 4 months, and 5 days."._

**Output**

![Screenshot Proof](/ss/e6-o.png?raw=true "exercise-6-output")

**Observation**: _As expected, the program outputted "The period between the two dates is: 2 years, 4 months, and 5 days."._
