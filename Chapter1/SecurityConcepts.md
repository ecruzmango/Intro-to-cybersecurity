# Chapter 1: Security Concepts and Principles

## 1.1 Fundamentals goals of computer security
There are six high level computer security goals to aim for

1. **Confidentiality**: Keeping information private and can only be accessed with those who are authorized
*  We use two main approaches to achieve this. First, we have `access control`. In computer systems, the operating system does the job (i.e. it checks for usernames, passwords, and permissions before allowing access). Second, we use `encryption`. We use sophisticated mathematical algorithms to encrypt data, and only people with the correct 'key' can decrypt and read it.


2. **Integrity**: 
Data remains unchanged since it was created.

3. **Authorization**: 
computing resources can only be accessed by those who are authorized. We can use <ins>access control</ins> to achieve authorization.

4. **Availability**:
Availability means to ensure that systems, services, and data are accessible when authorized users need them. 
* systems need to maintain enough capacity to handle legitimate requests, even during busy periods. 
* We must protect against threats that could interrupt service, such as `distributed denial-of-service` (DDoS) attacks. These attacks try to overwhelm systems, like hundreds of people crowding an emergency room with fake injuries to prevent real patients from getting care.
* We also need reliable backup systems and disaster recovery plans. If the main system fails, we should have alternatives ready 
* the agents representing users or system processes are called `principals`.
* `privilege`- defines what a principle can do such as read,write, execute, shutdown the system, etc.

5. **Authentication**: 
`Entity authentication` provides assurances that the identity of a principle involved in a transaction is as asserted. In other words, verifying that someone/something is who they claim to be 
`Data origin Authentication`: Verifying the source of data/software and ensuring it hasn't been changed. 

6. **Accountability**:

## 1.2 Policies and Attacks
