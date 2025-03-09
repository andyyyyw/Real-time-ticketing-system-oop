
# Real- Time Event Ticketing System with Advanced Producer-Consumer Implementation 

The Ticketing System Simulation is a multi-component program created to effectively manage ticket sales through concurrent and object-oriented approach. It has built from an Angular frontend for user interaction, a Spring Boot backend for managing business logic, and a Java Command Line Interface (CLI) for system configuration. The system guarantees thread safety, appropriate capacity management, and real-time updates while enabling vendors to distribute tickets into a pool that customers can retrieve tickets from.

## Setup Instructions

Prerequisites

•	Java: Version 17 or above

•	Node.js: Version 16 or above

•	Angular CLI: Version 19.0.4

•	Maven: For building the Spring Boot backend

•	Git: For cloning the repository


Building and Running the Application

1.	Clone the Repository:

git clone <repository-url>

cd ticketing-system-simulation

2.	Build and Run the Backend:

•	Navigate to the backend directory:

cd backend

•	Build the Spring Boot application:

mvn clean install

•	Run the application:

java -jar target/ticketing-system-backend.jar

3.	Build and Run the Frontend:

•	Navigate to the frontend directory:

cd ../frontend

•	Install dependencies:

npm install

•	Run the Angular application:

ng serve

4.	Run the CLI:

•	Navigate to the cli directory:

cd ../cli

•	Compile and run the CLI:

javac CLI.java

java CLI

## Usage Instructions
Configuring and Starting the System
1.	Open the UI: Navigate to http://localhost:4200 in your web browser.
2.	Fill in the form:

o	Total tickets per vendor: The number of tickets each vendor can release.

o	Maximum ticket capacity of the ticket pool: The total number of tickets allowed in the pool(Ticket-pool size).

o	Ticket release rate: The rate at which tickets are released into the pool.

o	Customer retrieval rate: The rate at which customers retrieve tickets from the ticket pool.

o	Number of vendors: The total number of vendors releasing tickets.

o	Number of customers: The total number of customers retrieving tickets.

3.	Start the system: Press the Start button to initiate the simulation.

UI Controls

•	Configuration form: Allows users to configure the system first

•	Start Button: Begins the simulation with the provided parameters.

•	Stop button: Terminates the simulation.

•	Ticket availability: Shows the current number of tickets in the pool.

•	System Logs: Displays real-time logs of the system's operations.





