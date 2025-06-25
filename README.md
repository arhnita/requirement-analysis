# Requirement Analysis in Software Development

The purpose of this repositry is to focus on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements.

## What is Requirement Analysis?

Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.

# Why is Requirement Analysis Important?
- It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- It clearly defines the scope of the project which helps in preventing scope creep
- It provides a solid foundation for designing and developing the system
- It facilitates accurate estimation of project cos, resources and time
- It ensures that the final product meets the specified requirements, leading to higher customer satisfaction

# Key Activities in Requirement Analysis.
The key activities in requirements analysis consists of 5 steps
1. Requirement Gathering
   - Interviews: Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
   - Surveys/Questionnaires: Distributing surveys to collect requirements from a larger audience
   - Workshops: Organizing workshops with stakeholders to discuss and gather requirements.
   - Observation: Observing end-users in their working environment to understand their needs.
   - Document Analysis: Reviewing existing documentation and systems to understand current functionalities and requirements.

2. Requirement Elicitation
   - Brainstorming: Conducting brainstorming sessions to generate ideas and gather requirements.
   - Focus Groups: Holding focus group discussions with selected stakeholders to gather detailed requirements.
   - Prototyping: Creating prototypes to help stakeholders visualize the system and refine their requirements.

  
3. Requirement Documentation
   - Requirement Specification Document: Creating a detailed document that lists all functional and non-functional requirements.
   - User Stories: Writing user stories to describe functionalities from the user’s perspective.
   - Use Cases: Creating use case diagrams to show interactions between users and the system.

4. Requirement Analysis and modelling
   - Requirement Prioritization: Prioritizing requirements based on their importance and impact on the project.
   - Feasibility Analysis: Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
   - Modeling: Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.
     
5. Requirement Validation
   - Review and Approval: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
   - Acceptance Criteria: Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
   - Traceability: Establishing traceability matrices to ensure all requirements are addressed during development and testing.

# Types of Requirements.
1. # Functional Requirements
Definition: Describe what the system should do.
Examples: User authentication, property search, booking system, user registration.

Key Functional Requirements:

# Hotel Management Service:

- Hotel managers can add, update, and delete hotel information
- Managers can manage room inventory and availability
- Managers can update pricing and hotel amenities
- Managers can view booking details for their properties

# Customer Service:

- Customers can search for hotels by location, date, and other criteria
- Customers can view hotel details, photos, and amenities
- Customers can make hotel reservations
- Customers can process payments for bookings
- Customers can receive recommendations and view offers

# Booking Management:

- System can display current booking details
- System can show booking history for both customers and managers
- System can handle booking confirmations and cancellations

# Notification Service:

- System sends booking confirmations to customers
- System notifies managers when new bookings are made
- System sends promotional offers to customers

# Data Management:

- System archives old booking data
- System provides business analytics and reporting capabilities

2. # Non-functional Requirements
Definition: Describe how the system should perform.
Examples: Performance, security, scalability, usability, reliability.

# Key Non-functional Requirements:

# Scalability:

- System uses microservices architecture to handle high user traffic
- Load balancers distribute requests across multiple servers
- Database clusters can scale horizontally

# Performance:

- Redis caching reduces database load and improves response times
- CDN provides fast content delivery globally
- Elasticsearch enables fast search functionality
- Load balancing ensures optimal resource utilization

# Availability:

- Master slave database architecture ensures high availability
- Multiple server instances prevent single points of failure
- Geographic distribution through CDN improves uptime

# Reliability:

- Messaging queues (Kafka/RabbitMQ) ensure reliable data processing
- Data replication between master and slave databases
- Asynchronous processing prevents system bottlenecks

# Security:

- Separate portals for hotel managers and customers
- Secure payment processing through third-party services
- Data access controls for different user types

# Maintainability:

- Microservices architecture enables independent service updates
- Clear separation of concerns between different services
- Modular design facilitates easier debugging and maintenance

# Data Consistency:

- Real-time synchronization between master and slave databases
- Messaging queues ensure eventual consistency across services
- Data validation and integrity checks

# Usability:

- Fast search results through Elasticsearch
- Smooth user experience with minimal loading times
- Intuitive interfaces for both customers and hotel managers

# Storage & Archival:

- Cassandra handles large volumes of historical data
- Hadoop stores data for big data analysis
- Efficient data retention and archival policies

# Use Case Diagrams
Please find the link to the use case diagram below
![Image](https://github.com/user-attachments/assets/a1508776-bd3d-4964-ba92-ca8f617e313c)

# Acceptance Criteria.
Acceptance criteria are conditions that a feature must meet to be accepted by the stakeholders.

# How to Define Acceptance Criteria:
- Be specific and measurable.
- Include functional and non-functional aspects.
- Example for Booking System: “Users should be able to select available dates, confirm booking, and receive a confirmation email within 2 minutes.”

# Benefits of Acceptance Criteria
- Ensure all parties have a clear understanding of feature requirements.
- Provide a basis for testing and validation.
- Help in maintaining quality and meeting user expectations.
