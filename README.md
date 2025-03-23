# School Fee Tracker

## Project Overview

The School Fee Tracker is a Java-based application designed to manage the financial transactions of a school, including student fee payments and teacher salary disbursements. The application allows for the tracking of students, teachers, and the overall financial health of the school. It provides functionalities to pay fees, receive salaries, and calculate remaining fees and total money earned/spent.

## Features

- **Student Management**: Create and manage student records, including their ID, name, grade, fee paid, and total fee.
- **Teacher Management**: Create and manage teacher records, including their ID, name, salary, and total salary earned.
- **Fee Payment**: Students can pay their fees, and the application updates the total money earned by the school.
- **Salary Payment**: Teachers can receive their salaries, and the application updates the total money spent by the school.
- **Financial Tracking**: The application keeps track of total money earned and spent, providing insights into the school's financial status.

## Technologies Used

- Java
- Object-Oriented Programming (OOP) principles

## Object-Oriented Programming Concepts Used

1. **Encapsulation**: 
   - The properties of the `Student` and `Teacher` classes are private, ensuring that they cannot be accessed directly from outside the class. Public methods (getters and setters) are provided to access and modify these properties.

2. **Abstraction**: 
   - The implementation details of how fees are paid and salaries are received are hidden from the user. The user interacts with the `payFee` and `reciveSalary` methods without needing to understand the underlying logic.

3. **Inheritance**: 
   - While this project does not explicitly demonstrate inheritance, it can be extended to include subclasses for different types of students or teachers in the future.

4. **Polymorphism**: 
   - The `toString` method is overridden in both the `Student` and `Teacher` classes to provide a custom string representation of the objects, allowing for polymorphic behavior when printing the objects.

## Future Enhancements

- Implement a user interface (UI) for better interaction.
- Add functionality to handle multiple fee structures for different grades.
- Include a database to persist student and teacher records.
- Implement error handling for invalid inputs.

