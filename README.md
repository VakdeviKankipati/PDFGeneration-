                              PDF Generation Project

Objective:

To develop a service that dynamically generates invoices in PDF format based on seller, buyer, and item details.

Technologies Used:

Java: Core programming language.

Spring Boot: To implement and manage the service.

iText (lowagie): Library for creating and manipulating PDF files.

JUnit: For unit testing.

Mockito: For mocking during testing.


Key Features:

Generates a PDF containing:

Seller details (name, GSTIN, address).

Buyer details (name, GSTIN, address).

List of items (name, quantity, rate, and total amount).

Handles empty or missing data gracefully.

Returns the file path of the generated PDF.

Supports exception handling for issues like file I/O errors.

TDD Implementation:

Developed with Test-Driven Development, ensuring robust and error-free code.

Unit tests cover:

Successful PDF generation.

Handling of edge cases (e.g., empty item list).

Exception handling scenarios.

Testing Tools and Strategies:

Used JUnit for testing service functionality.

Verified that:

The PDF file is created successfully.

The file contains non-empty content.

Errors like invalid file paths are managed.

Project Workflow:

Input: Seller details, buyer details, and item list.

Processing: Generates a structured invoice PDF.

Output: Returns the file path of the created PDF.


Error Handling:

Validates input and handles edge cases.

Manages file-related exceptions (e.g., missing directory).


Outcome:

Successfully generates well-formatted invoice PDFs.

Modular and testable codebase.

Easy to enhance for additional features like custom layouts or table formatting.
