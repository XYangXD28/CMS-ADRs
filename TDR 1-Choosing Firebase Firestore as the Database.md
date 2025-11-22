TDR 1: Choosing Firebase Firestore as the Database

# Forces
We required a cloud-based database that can provide real-time updates, document structure flexibility, low-operating cost and simple integration with a serverless backend. The team expertise and the project schedule also demanded low-maintenance utilization of servers with no administration of servers.

# Decision
We will use Firebase Firestore as the primary database for the system.

# Rationale
Firestore has auto-scaling, robust client SDK, easy security rules, and flexible NoSQL document structures. It eliminates maintenance and set up of database server, making the development less complex. SQL databases were dismissed due to the need to administer schema and extra hosting power which does not fit the time and constraint of the project and the resources of the backend mechanisms.

# Status
Accepted

# Consequences
Firestore offers quick development and real time synchronization but it has to be carefully designed with collections and subcollections in order to avoid expensive reads. Complex relational queries may also require denormalization.
