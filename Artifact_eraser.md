# Artifact V1 Eraser

## Team

- Camilo Andres Pinzon Ruiz
- Miguel Angel Ortiz Escobar
- Omar Leonardo Zambrano Pulgarin
- Jesus Ernesto Quiñones Cely

## Software System
- **Name**: Artifact V1 Eraser
- **Logo**: **Pending**
- **Description**: Software system for medical appointments management.
    - **Domain**: Healthcare
    - **Purpose**: To manage medical appointments efficiently.
    - **Main Functionalities**: Scheduling, Payments, Notifications, Patient & Doctors Records.
- **Cloud-Native Principles**:
    - Containerization
    - Scalability
    - High Availability
    - Resilience
    - Elasticity
    - Automation
    - Observability
    - Loose Coupling
    - Microservices & Event Driven Architecture
    - Continuous Integration/Continuous Deployment (CI/CD)

## Software Design

### Architectural Design
- C&C
    - Graph
    <img src="C&C Light.png" alt="Alt text">
    - Components Description (Responsabilities, Technologies used, etc.)
        - **Frontend**: User interface for patients and doctors to interact with the system.
        - **API Gateway**: Routes requests to appropriate services and handles cross-cutting concerns.
        - **Auth Service**: Manages user authentication and authorization.
        - **Appointment Service**: Handles scheduling and managing medical appointments.
        - **Payment Service**: Processes payments for appointments.
        - **Patient Service**: Manages patient records and information.
        - **Doctor Service**: Manages doctor records and information.
        - **Event Bus**: Facilitates communication between microservices using events.
        - **Notification Service**: Sends notifications to patients and doctors.
        - **Reporting / Analytics Service**: Generates reports and analytics on appointments and payments.
        - **Databases**: Stores all persistent data for the services.
- Deployment Structure
    - Graph
    - Description (Responsabilities, Cloud services used, etc.)

### Detailed Design

- Data Model(s)
- API Specs
- Functional Flows

## Discussion and Reflection

In this section, the team must provide a critical analysis of the design and implementation carried out
during the project. The goal is not only to describe what was done, but also to reason about why
decisions were made, evaluate the effectiveness of the solution, and assess how well the system
demonstrates cloud-native principles.

The discussion should include the following elements:

 - **Design Rationale**
 - **Implementation Challenges**
 - **Cloud-Native Principles Evaluation**
 - **Effectiveness of the Process**
 - **Lessons Learned**