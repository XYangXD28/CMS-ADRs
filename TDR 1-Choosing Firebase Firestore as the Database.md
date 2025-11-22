
# TDR 1: Choosing Firebase Firestore as the Database 
## Forces
We needed a database that was hosted in the cloud, scalable, and could synchronize in real time, low-maintenance, and supported powerful client SDKs. It was also required to be seamlessly integrated with a serverless backend.

## Decision
We will use Firebase Firestore as the primary database for the system.

## Rationale
Firestore has built-in scaling, customizable NoSQL documents, and easy security policies. SQL databases were eliminated as they are more expensive to set up, require strict schema control, and slow development in this project.

## Status
Accepted

## Consequences
It is now possible to develop faster and update in real-time, though one has to be careful about the design of collections to prevent read/write wastage.
