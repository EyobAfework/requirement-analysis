# Requirement Analysis in Software Development

This repository is dedicated to understanding and documenting the process of requirement analysis in software development. 

Requirement analysis is a critical phase in the software development lifecycle where the needs and expectations of stakeholders are gathered, analyzed, and documented. This ensures that the final product aligns with business goals and user requirements.

The repository includes:
- Overview of requirement types
- Techniques and tools used in requirement gathering
- Case studies and practical examples
- Templates for requirement documentation

This project is useful for software engineers, business analysts, project managers, and students who want to learn or improve their skills in requirement analysis.

**What is Requirement Analysis?**

Requirement Analysis is the process of identifying, gathering, analyzing, and documenting the needs and expectations of stakeholders for a software system. It is one of the most critical phases in the Software Development Lifecycle (SDLC) because it lays the foundation for all subsequent stages, including design, development, testing, and deployment.

✅ Key Objectives of Requirement Analysis:

- Understand what the users and stakeholders need from the system
- Clearly define system functionalities and constraints
- Avoid ambiguity and miscommunication during development
- Ensure the final product aligns with business goals
  
**Why is Requirement Analysis Important?**

- *Clarity and Understanding*: It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- *Scope Definition*: Clearly defines the scope of the project, which helps in preventing scope creep.
- *Basis for Design and Development*: Provides a solid foundation for designing and developing the system.
- *Cost and Time Estimation*: Facilitates accurate estimation of project cost, resources, and time.
- *Quality Assurance*: Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.

# **Key Activities in Requirement Analysis**

**1. Requirement Gathering 🗂️**
   
- **Interviews:** Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
- **Surveys/Questionnaires:** Distributing surveys to collect requirements from a larger audience.
- **Workshops:** Organizing workshops with stakeholders to discuss and gather requirements.
- **Observation:** Observing end-users in their working environment to understand their needs.
- **Document Analysis:** Reviewing existing documentation and systems to understand current functionalities and requirements.

**2. Requirement Elicitation ✍️**

- **Brainstorming:** Conducting brainstorming sessions to generate ideas and gather requirements.
- **Focus Groups:** Holding focus group discussions with selected stakeholders to gather detailed requirements.
- **Prototyping:** Creating prototypes to help stakeholders visualize the system and refine their requirements.

**3. Requirement Documentation 📚**

- **Requirement Specification Document:** Creating a detailed document that lists all functional and non-functional requirements.
- **User Stories:** Writing user stories to describe functionalities from the user’s perspective.
- **Use Cases:** Creating use case diagrams to show interactions between users and the system.

**4. Requirement Analysis and Modeling 📊**

- **Requirement Prioritization:** Prioritizing requirements based on their importance and impact on the project.
- **Feasibility Analysis:** Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
- **Modeling:** Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.

**5. Requirement Validation ✅**

- **Review and Approval:** Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
- **Acceptance Criteria:** Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
- **Traceability:** Establishing traceability matrices to ensure all requirements are addressed during development and testing.

## **Types of Requirements**

### **Functional Requirements ⚙️**

**Definition:** Describe what the system should do.
**Examples:** User authentication, property search, booking system, user registration.

**Key Functional Requirements:**

- **Search Properties:** Users should be able to search for properties based on various criteria such as location, price, and availability.
- **User Registration:** New users should be able to create an account with personal details and login credentials.
- **Property Listings:** Display properties with essential details and images.
- **Booking System:** Users should be able to book properties, view booking details, and manage their bookings.
- **User Authentication:** Secure login and registration process for users.
  
### **Non-functional Requirements 🛡️**

**Definition:** Describe how the system should perform.
**Examples:** Performance, security, scalability, usability, reliability.

**Key Non-functional Requirements:**

- **Performance:** The system should load pages within 2 seconds and handle up to 1000 concurrent users.
- **Security:** Ensure data encryption, secure login, and protect against common vulnerabilities.
- **Scalability:** The system should be able to scale horizontally to handle increased traffic.
- **Usability:** The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
- **Reliability:** The system should have an uptime of 99.9% and recover quickly from any failures.

## **Use Case Diagrams**

**Use Case Diagrams 📊**

**Objective:** Visual representation of interactions between users and the system.

### **What are Use Case Diagrams?**

Use case diagrams show how different users (actors) interact with the system to achieve specific goals (use cases).
Creating Use Case Diagrams:

- Identify actors (e.g., guest, registered user, admin).
- Define use cases (e.g., search properties, book property, manage listings).
- Draw interactions between actors and use cases.

### **Benefits of Use Case Diagrams:**

- Provide a clear visual representation of system functionalities.
- Help in identifying and organizing system requirements.
- Facilitate communication among stakeholders and development team.

## Use Case Diagram

![Use Case Diagram](./alx-booking-uc.png)


## ✅ Acceptance Criteria

### 📌 Importance of Acceptance Criteria in Requirement Analysis

**Acceptance Criteria** define the specific conditions that a product or feature must meet to be accepted by users, stakeholders, or the product team. They are essential in **requirement analysis** because they:

* Provide **clarity** on what needs to be delivered
* Help eliminate **ambiguity** and miscommunication
* Serve as a **reference** for developers, testers, and stakeholders
* Define the **scope** and **limits** of a user story or feature
* Ensure the feature meets **business goals** and **user expectations**

### 🛒 Example: Acceptance Criteria for the **Checkout Feature** in a Booking Management System

**User Story**:
*As a customer, I want to check out after selecting a listing and confirming my booking details so that I can complete the reservation and receive a confirmation.*

**Acceptance Criteria**:

1. ✅ The user must be logged in to proceed to checkout.
2. ✅ The checkout page must display a summary of the booking (listing, dates, price, taxes, etc.).
3. ✅ The system must allow users to enter or select a payment method.
4. ✅ The system must validate the payment information before processing.
5. ✅ Upon successful payment, the booking status is updated to “Confirmed.”
6. ✅ The system sends a confirmation email and/or notification to the user.
7. ✅ If the payment fails, the user is notified and remains on the checkout page with error details.
8. ✅ The checkout process must be completed within 15 minutes of initiating checkout, otherwise the session expires.


