# Estimation by the COSMIC method
The COSMIC (Counting Software Objects through Measurement and Instrumentation) method is a functional measurement method used in estimating the cost and size of software development projects that focuses on measuring the functional size of software based on the number of functions provided. by the system.
Unlike other software estimation methods that focus on lines of code or function points, the COSMIC method focuses on identifying and measuring the business functions provided by the software.

It is important to note that, although the COSMIC method can be a valuable tool for cost estimation, no methodology is perfect, and the accuracy of the estimates will depend on several factors, such as the quality of the information available and the experience of the estimators. In this case, the estimate of effort, costs and time for an application like MusicHub varies depending on several factors, such as the complexity of the functions required, the technology used and the experience of the team.

In this case, we decided to apply this technique to our most recent sprint. Because in this sprint we focus on interface improvement and interface testing, COSMIC measurement points are aimed at non-functional requirements.

# Sprint: Flow fixes in interfaces and User Acceptance Testing (UAT)

* **Task 1: Flow Corrections in User Interfaces (UI)**
     * Complete review of interfaces to correct flows and review interfaces to correct, add or delete.
* **Task 2: Integration and Performance Testing**
     * Testing to ensure correct operation of new features.

## 1. Identification of Functions:

* **External Inputs (1 CFP (Cosmic Function Point)):**
     * Corrections in flows such as search interface and editing of content uploaded by the user.

* **External Outputs (2 CFP):**
     * Improvements in flows between interfaces.

* **External Consultations (1 CFP):**
     * User flow testing to evaluate and correct navigation and interaction.

* **Internal Files (1 CFP):**
     * Corrections in interfaces such as the notifications section and their flow.

* **External Files (0 CFP):**
     * We do not add in this sprint.

## 2. Effort Estimation:
Using an average of 8 hours for each CFP, we have estimated an approximate total of 5 CFPs for this sprint.

## 3. Cost Estimation:

Because we are carrying out this project as students, we cannot make a realistic cost estimate, since we are not employees and therefore do not receive remuneration, however, below we show 2 cases in the cost estimate based on the data historical records of these positions in Mexico, which are referenced at the end of this page.

* **Case 1: Junior Developers**
     * Tester (Junior): $66 per hour.
         * Members:
             * Adrian Vazquez
             * Hector Barrera
             * Javier Ortiz

     * UX/UI Designer (Junior): $58 per hour. - 4 members
         * Members:
             * Adriel Yerbes
             * Aldar Gonzalez
             * Greco Gachuz
             * Ruben Perez

* **Case 2: Senior Developers**
     * Tester (Senior): $116 per hour.
     * UX/UI Designer (Senior): $150 per hour.

To obtain an approximate cost of the Sprint, we require other data such as employee salaries, resulting in the following formulas:

Employee Salary = (Hourly Salary * Total Hours)
Sprint Cost = Employee 1 Salary + Employee 2 Salary + ... Employee N Salary

With the data obtained, we can define an approximate cost for this sprint, which would be:

Sprint Cost:
| Member | Salary/hour | Total hours | Salary |
|---------|--------------|----------------|---- -----|
| Adrián Vázquez | $66 | 5.5 hrs | $363 |
| Hector Barrera | $66 | 5.5 hrs | $363 |
| Javier Ortiz | $66 | 5.5 hrs | $363 |
| Adriel Yerbes | $58 | 5.5 hrs | $319 |
| Aldar Gonzalez | $58 | 5.5 hrs | $319 |
| Greco Gachuz | $58 | 5.5 hrs | $319 |
| Ruben Perez | $58 | 5.5 hrs | $319 |
|||||
|**Total:** | $430 | 38.5 hrs | $2,365 |

We can conclude that the Sprint would have an approximate cost of $2,365 with Junior Developers and Testers in Mexico according to our requirements and historical data found.

## 4. Time Estimation:

For this project, taking into account that it is our first approach to Software Engineering, we have decided to approximate 8 hours for each CFP; We have 5 CFPs, so for this sprint we dedicated approximately a total of 40 hours throughout the week that this sprint lasted.

## Salary References:

* “Salary: Tester In Mexico In 2023.” Glassdoor, 2023, https://www.glassdoor.com.mx/Sueldos/tester-sueldo-SRCH_KO0,6.htm. Accessed 2 Dec. 2023.

* Salary: Junior UX/UI Designer in 2023. (2023). Glassdoor. https://www.glassdoor.com.mx/Sueldos/junior-ux-ui-designer-sueldo-SRCH_KO0,21.htm#:~:text=%C2%BFCu%C3%A1nto%20gana%20un%20Junior% 20ux, from%20MXN%2421%2C949%20in%20M%C3%A9xico.

* Salary: UX/UI Senior in 2023. (2023). Glassdoor. https://www.glassdoor.com.mx/Sueldos/ux-ui-senior-sueldo-SRCH_KO0,12.htm
