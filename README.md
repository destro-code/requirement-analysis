# requirement-analysis

## Requirement Analysis in Software Development.

## What is Requirement Analysis?

Requirement Analysis is a foundational phase in the Software Development Life Cycle (SDLC) where project stakeholders, analysts, and developers collaborate to define, analyze, and document what the software system should achieve. This process ensures that all parties involved have a mutual understanding of the project scope, functionality, and constraints before design and development begin.

### Importance in the SDLC:

1. **Clarity and Understanding**: Requirement Analysis eliminates ambiguity by capturing detailed expectations and functionalities desired by stakeholders. This clarity reduces miscommunication and rework later in the project.

2. **Scope Definition**: It clearly outlines the boundaries of the system, preventing scope creep and helping the team stay focused on agreed-upon objectives.

3. **Foundation for Design and Development**: All design, development, and testing activities stem from well-defined requirements. It serves as a blueprint that guides every subsequent phase.

4. **Accurate Cost and Time Estimation**: Understanding what needs to be built enables more realistic planning in terms of budget, resources, and timeline.

5. **Quality Assurance**: With well-documented and validated requirements, it's easier to test the final product against expectations, ensuring higher satisfaction and fewer bugs.

6. **Improved Communication**: Use of diagrams, user stories, and use cases facilitates effective communication among technical and non-technical stakeholders.


## Why is Requirement Analysis Important?

Requirement Analysis plays a crucial role in the success of any software project. Here are three key reasons why it is critical in the Software Development Life Cycle (SDLC):

1. **Reduces Ambiguity and Misunderstandings**  
   By thoroughly gathering and analyzing requirements, the project team ensures that all stakeholders have a clear and consistent understanding of what the software should do. This clarity minimizes miscommunication and reduces costly changes during development.

2. **Defines Project Scope and Prevents Scope Creep**  
   Requirement Analysis helps in clearly defining the boundaries and functionalities of the software. This prevents uncontrolled changes or additions to the project scope, which can lead to delays, budget overruns, and project failure.

3. **Enables Accurate Planning and Resource Allocation**  
   With well-defined requirements, project managers can estimate time, cost, and resources more precisely. This ensures that the project is feasible and that the team is adequately prepared to meet deadlines and budget constraints.

## Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collect detailed information from stakeholders through interviews, surveys, workshops, observations, and document reviews to understand their needs and expectations.

- **Requirement Elicitation**  
  Refine and explore requirements by engaging stakeholders in brainstorming sessions, focus groups, and prototyping to uncover hidden or implicit needs.

- **Requirement Documentation**  
  Create structured documents such as requirement specification documents, user stories, and use cases to clearly record all functional and non-functional requirements.

- **Requirement Analysis and Modeling**  
  Prioritize requirements based on their importance and feasibility, and create visual models like data flow diagrams and entity-relationship diagrams to better understand and communicate the requirements.

- **Requirement Validation**  
  Review requirements with stakeholders to ensure accuracy and completeness, define acceptance criteria, and establish traceability to confirm that all requirements are met throughout development and testing.

## Types of Requirements

### Functional Requirements ⚙️
Functional requirements describe **what** the system should do — the core features and behaviors expected from the software.

For the booking management project (hotel booking system), key functional requirements include:

- **Search Properties:** Users can search hotels based on location, price, availability, and ratings.
- **User Registration & Authentication:** Users (customers and managers) can create accounts and securely log in.
- **Property Listings Management:** Hotel managers can add, update, or remove hotel details and images through a dedicated portal.
- **Booking System:** Customers can book hotels, view booking details, cancel or modify bookings.
- **Notifications:** System sends booking confirmations and alerts (e.g., new offers) to users and managers.
- **Payment Integration:** The booking service interacts with third-party payment gateways to process payments securely.
- **View Booking History:** Users and managers can view current and past booking details via a portal.

---

### Non-functional Requirements 🛡
Non-functional requirements specify **how** the system performs its functions — qualities and constraints to ensure usability, reliability, and performance.

For the same hotel booking system, typical non-functional requirements include:

- **Performance:** Pages should load within 2 seconds; system must handle 1000+ concurrent users smoothly.
- **Scalability:** The architecture must support horizontal scaling (e.g., using load balancers, distributed databases) to accommodate traffic growth.
- **Security:** Secure login, data encryption, protection against common vulnerabilities (e.g., SQL injection, XSS).
- **Reliability:** System uptime of 99.9%, with failover mechanisms and quick recovery from failures.
- **Usability:** Intuitive, user-friendly interface for both customers and hotel managers.
- **Data Consistency:** Use of master-slave database architecture to ensure data synchronization and reduce read/write conflicts.
- **Caching and Speed:** Use of Redis caching to minimize database load and improve response times.
- **Data Archival:** Efficient handling of historical data via NoSQL databases like Cassandra to maintain system performance.

## Use Case Diagrams 📊

### What are Use Case Diagrams?

Use Case Diagrams visually represent the interactions between users (actors) and the system. They help identify the system's functionalities by showing how different actors engage with various features (use cases). This makes it easier to understand requirements, organize system functions, and communicate clearly among stakeholders and developers.

### Benefits of Use Case Diagrams:
- Provide a clear and concise visual overview of system functionalities.
- Help identify all user roles and their interactions with the system.
- Facilitate communication between technical teams and non-technical stakeholders.
- Assist in validating and organizing requirements during analysis.

### Use Case Diagram for Booking System

**Actors:**
- Customer
- Hotel Manager
- Admin

**Use Cases:**
- Search Properties
- Register / Login
- View Property Details
- Book Property
- Manage Bookings (view, cancel, modify)
- Manage Listings (add, update, remove properties)
- Receive Notifications
- Process Payments
- View Booking History





