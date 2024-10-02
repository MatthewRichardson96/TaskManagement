# Task Management Application

### Architecture Pattern: CQRS (Command Query Responsibility Segregation)
### Future Advanced Features:

 - Event-Driven Architecture: Trigger events like TaskCreated, TaskCompleted, and use an event broker (like Kafka or RabbitMQ) to handle asynchronous task updates or notifications.
 - Event Sourcing: Store each state change as an event, allowing you to rebuild the state from scratch or audit changes easily.
 - Microservices: Split the application into services like TaskService, NotificationService, and CategoryService for better modularity.
 - GraphQL API: Provide flexible, efficient data querying through GraphQL, enabling users to fetch only the fields they need.
 - Saga Pattern: Use sagas to handle complex workflows (e.g., task delegation and multi-step task execution).
 - Distributed Tracing: Implement OpenTelemetry to trace user actions and debug the flow across multiple services.

### Acceptance Criteria:

- Task Creation: Users can create tasks with priority and due date.
- Task Listing: Users can view tasks filtered by status.
- Task Updates: Users can update task details or mark tasks as completed.
- Categorization: Organize tasks into different categories (e.g., Work, Personal).
