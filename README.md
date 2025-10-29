# Exp - 3 RAILWAY MANAGEMENT SYSTEM

## AIM:
To develop the Railway Reservation System using Star UML tool.
## PROCEDURE:
### USECASE :
Identified the primary Actors (`Passenger`, `Admin`, `Clerk`) and mapped all their key interactions (e.g., Login, Book Ticket, Manage Schedules) to define the system's functional boundary.

### CLASS :
Defined all necessary Classes (`Passenger`, `Tickets`, `Train Details`, `Payment`), specified their essential Attributes and Methods, and established the relationships between them to form the conceptual data model.

### SEQUENCE :
Detailed the exact sequence of messages between lifelines (`passenger`, `IRCTC Website`, `Railway System`) for a Ticket Booking from Login $\rightarrow$ Verify User $\rightarrow$ Check Availability $\rightarrow$ Initiate Payment $\rightarrow$ Ticket Generated.

### ACTIVITY :
Charted the complete control flow for Ticket Booking, including decision points (`CHECK TICKET AVAILABILITY`) and concurrency (PAYMENT METHOD selection for UPI, CARD, NET), starting at LOGIN and concluding at PRINT TICKET.

### COMMUNICATION :
Placed the interacting objects (`Passenger`, `IRCTC`, `Railway System`) and used numbered arrows to model the sequential message exchange for the booking process, highlighting which object handles each action (e.g., verifying user, processing payment).

### PACKAGE :
Grouped the system's components into five high-level, logical Packages (`Passenger`, `IRCTC`, `Ticket`, `Payment`, `Train`) and mapped the dependencies between these modules to show the architectural organization.

## UML DIAGRAMS:
### USECASE DIAGRAM :
![UseCaseDiagram1](https://github.com/user-attachments/assets/ed082ad2-c9b8-4f90-b396-dbcbc29d7a55)

### CLASS DIAGRAM :
![ClassDiagram1](https://github.com/user-attachments/assets/3044df34-17ce-4e83-ab75-dc5b00f1e0eb)

### SEQUENCE DIAGRAM :
![SequenceDiagram1](https://github.com/user-attachments/assets/c91b92cd-fc07-4c41-b3c9-82dd5f4a6a76)

### ACTIVITY DIAGRAM :
![ActivityDiagram1](https://github.com/user-attachments/assets/6cd09e59-92eb-47c4-9e4b-a8d2345685da)

### COMMUNICATION DIAGRAM :
![CommunicationDiagram1](https://github.com/user-attachments/assets/a2bea892-7ca4-4bb9-b748-52695742e58a)

### PACKAGE DIAGRAM :
![PackageDiagram1](https://github.com/user-attachments/assets/47da31b9-14b7-4a53-a542-9eff55de5826)

## RESULT:
Thus the project to develop e-ticketing system was developed using Star UML Software.
