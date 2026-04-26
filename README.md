# cs320-software-testing-portfolio
Portfolio repository showcasing unit testing, software validation, and quality assurance techniques using JUnit 5. Includes Contact Service implementation, test cases, and reflection on testing strategies.
Reflection

How can I ensure that my code, program, or software is functional and secure?

I ensure that my software is functional and secure by using unit testing to validate both expected and unexpected behaviors. In this project, I wrote JUnit tests to verify correct functionality using valid inputs, while also using negative testing to ensure invalid inputs were properly rejected.

For example, I tested constraints such as null values and field length limits to prevent invalid data from being accepted. This helps improve both reliability and security, as it ensures the system cannot be easily broken by incorrect input. I also used assertThrows() to confirm that exceptions were triggered when rules were violated, which reinforces secure input handling.



How do I interpret user needs and incorporate them into a program?

I interpret user needs by carefully analyzing the software requirements and translating them into specific validation rules and behaviors within the code. Each requirement is directly implemented and then verified through testing.

For example, if a requirement states that a contact ID must not exceed 10 characters, I implement this constraint in the code and then create a test case to ensure longer IDs are rejected. This approach ensures that user expectations are consistently enforced and validated through testing.



How do I approach designing software?

I approach software design by breaking the system into smaller, manageable components and focusing on building and testing each part independently. In this project, I designed separate services such as Contact Service, Task Service, and Appointment Service, each responsible for specific functionality.

I prioritize simplicity, clarity, and validation at every step. I also design with testing in mind, ensuring that each method can be easily tested in isolation. This modular approach makes the system easier to maintain, debug, and expand in the future.



Summary of Work

In Project One, I developed and tested three service components using JUnit 5. My testing approach included:

* Unit testing for individual methods
* Boundary value analysis for field limits
* Equivalence partitioning for valid vs invalid inputs
* Negative testing to ensure proper error handling

In Project Two, I reflected on my testing strategies, mindset, and the importance of aligning tests with software requirements. This helped reinforce my understanding of quality assurance and the role of testing in preventing technical debt.
