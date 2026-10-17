# Appointment Service Application

## Project Overview

The Appointment Service Application is a Java-based project I originally developed for CS 320: Software Testing, Automation, and Quality Assurance at Southern New Hampshire University. The application manages appointment records and provides functionality for adding, retrieving, and deleting appointments.

The original application used an ArrayList to store appointment records and perform searches. For my CS 499 Computer Science Capstone, I enhanced the application by replacing the ArrayList with a Binary Search Tree (BST) to improve search efficiency and demonstrate my understanding of data structures and algorithms.

## Application Features

The application includes the following functionality:

- **Appointment Management:** Create, retrieve, and delete appointment records.
- **Unique Appointment IDs:** Each appointment is identified by a unique ID.
- **Input Validation:** Appointment records are validated to prevent invalid data.
- **Binary Search Tree Storage:** The enhanced application organizes records using a Binary Search Tree instead of an ArrayList.
- **Efficient Record Searches:** The BST allows searches to follow the tree structure rather than checking each record sequentially.
- **Record Deletion:** The BST supports deleting nodes with zero, one, or two children.
- **In-Order Traversal:** Records can be retrieved in sorted order by their IDs.
- **Automated Testing:** JUnit tests verify the application's functionality and data structure operations.

## Technologies Used

- Java
- Java Collections Framework
- Binary Search Tree (BST)
- JUnit
- Java Development Kit (JDK)

## Original Application and Enhancements

### Original Application

The original Appointment Service application used an ArrayList to store appointment records. Searching for an appointment required checking records sequentially until a matching ID was found.

This approach worked for smaller collections but became less efficient as the number of records increased.

### Enhanced Application

For my capstone enhancement, I developed a reusable generic Binary Search Tree class and integrated it into the application's service layer.

The BST supports insertion, searching, deletion, and in-order traversal. I also updated the service methods to use the new data structure while maintaining the application's original functionality.

This enhancement allowed me to apply concepts from my earlier data structures coursework to an existing Java application.

## Performance Comparison

To evaluate the improvement, I compared the search performance of the original ArrayList implementation against the enhanced Binary Search Tree.

The performance test used 10,000 records and performed 20,000 searches.

| Data Structure | Search Time |
|---|---|
| ArrayList | 267.271 ms |
| Binary Search Tree | 10.046 ms |

The Binary Search Tree completed the searches approximately **26.6 times faster** than the ArrayList in this test.

These results demonstrate how selecting an appropriate data structure can improve application performance.

The BST is not self-balancing, so performance can vary depending on the order in which records are inserted. In the worst case, an unbalanced tree can perform similarly to a linear search.

## How to Access and Run the Application

The repository contains the original and enhanced versions of the project.

### Requirements

- Java Development Kit (JDK)
- A Java IDE such as Eclipse or VS Code
- JUnit for running automated tests

### Setup Instructions

1. Download the ZIP file for the original or enhanced application.
2. Extract the ZIP file to a folder on your computer.
3. Open your preferred Java development environment.
4. Import or open the extracted Java project.
5. Configure the JDK and any required project dependencies.
6. Locate the Appointment Service classes and associated test files.
7. Run the JUnit tests to verify the application's functionality.

**Note:** This is a Java service application rather than a graphical application. Its functionality is demonstrated through service methods and automated tests.

## Testing

I used JUnit to verify that the application continued to function correctly after replacing the original data structure.

Testing included:

- Inserting records into the BST.
- Searching for existing and nonexistent IDs.
- Preventing duplicate IDs.
- Deleting nodes with zero, one, or two children.
- Verifying in-order traversal.
- Confirming that the existing service functionality continued to work.

I also performed a benchmark comparing the search performance of the original and enhanced implementations.
