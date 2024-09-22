# Distributed Systems Security Notes

## Introduction to Distributed Systems

### Definition
- Collection of independent computers appearing as a single coherent system to users.
- Involves interaction between independent entities with common protocols and goals.

### Characteristics of Distributed Systems
1. Mandatory Characteristics:
   - Multiple entities: Various users or subsystems composing the distributed system.
   - Heterogeneity: Diversity in system types, policies, or resources consumed.
   - Concurrency: Components run simultaneously, requiring synchronization considerations.
   - Resource Sharing: Allows sharing of hardware, software, and data across the system.

2. Desirable Characteristics:
   - Openness: Extendable architecture, protocols, and resources.
   - Scalability: Ability to grow without significant performance loss.
   - Transparency: Hiding system complexities from users (location and system).

### Types of Distributed Systems
1. Distributed Computing System: Focused on computational tasks.
2. Distributed Information System: Handles distributed data storage and retrieval.
3. Distributed Pervasive System: Ubiquitous, next-generation distributed systems.

## Distributed Computing Systems

### Cluster Computing System
- Homogeneous nature, using similar workstations or PCs.
- Connected by high-speed LAN, used for parallel programming.

### Grid Computing System
- Highly heterogeneous, federation of diverse computer systems.
- Enables collaboration through virtual organizations.

## Distributed Information Systems

### Transaction Processing System
- Uses single or nested databases with ACID properties.
- Transaction primitives: Start, End, Abort, Read, Write.

### Enterprise Application System
- Technologies: CORBA, RPC/RMI, DCOM, MOM.
- Web Services: Simple, XML-based, loosely coupled, platform-independent.

## Distributed Pervasive Systems
- Types: Home systems, Electronic health care, Sensor networks.
- Sensor Networks: Numerous small nodes, wireless, battery-powered.

## Distributed System Architectures

### Client-Server Architecture
- Challenges: Scalability, Flexibility.
- Solutions: Scale up/out, Three-tier architecture.

### Multinode Architecture
- Components: Processing nodes, Scheduler, Clients.
- Advantages: Performance, Fault tolerance, Scalability.

### Peer-to-Peer Architecture
- Used for file sharing, data storage.
- Pros: Scalability, Fault tolerance. Cons: Security, SLA issues.

### Service-Oriented Architecture (SOA)
- Roles: Provider, Requestor, Registry.
- Operations: Publish, Find, Bind.

## Challenges in Designing Distributed Systems

### Synchronization
- Issues: Clock sync, Leader election, Global state collection, Mutual exclusion.

### Fault Tolerance
- Failure sources: Processing sites, Communication media, Transmission delays.

### Security
- Complex due to multiple vulnerability points and heterogeneity.

## Common Security Issues and Technologies

### Security Issues
- Authentication, Authorization, Data Integrity, Confidentiality, Availability.
- DoS, Trust, Privacy, Identity Management.

### Security Techniques
1. Encryption: Symmetric and Asymmetric.
2. Digital Signatures and MACs.
3. Authentication: Password, Certificate, Biometric, Smart cards.
4. Public Key Infrastructure (PKI).
5. Trust Models: Implicit, Explicit, Intermediary.
6. Firewalls: Packet filtering, Proxy, Application-level.
