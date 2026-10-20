# 📈 GuessMarket

### Java Prediction Market Simulation

GuessMarket is a collaborative Java project that simulates a prediction-market platform where users can trade shares based on the possible outcomes of real-world events.

The project combines object-oriented design, market-pricing algorithms, graphical interfaces, and client–server communication.
It was developed in stages, from a console-based application to a modular system with a JavaFX desktop client and an HTTP-based server.
## ✨ Key Features
- Event management: Load event definitions from XML files, validate their contents, browse available markets, and resolve completed events.
- Two trading mechanisms:
  - LMSR (Logarithmic Market Scoring Rule): Calculates share prices dynamically as market positions change.
  - Order Book: Manages buy and sell orders and matches compatible offers.
- User accounts and balances: Track users, market makers, transactions, commissions, and payouts.
- Trading history: Display the current status and activity history of events.
- JavaFX desktop application: Interact with markets and account information through a graphical interface.
- Client–server architecture: Connect multiple clients to a central server through HTTP endpoints.
- Data exchange: Use XML for event configuration and JSON for client–server communication.
- Web-related modules: Contains web/ and web-client/ components.

## 🎓 What This Project Demonstrates
- Designing and maintaining a multi-module Java application.
- Applying OOP principles and separating business logic from presentation.
- Implementing trading and price-calculation logic.
- Building a graphical desktop interface.
- Integrating clients and a server through HTTP and structured data exchange.
- Collaborating on a shared codebase using Git and GitHub.

## 👩‍💻 Contributors
Developed collaboratively by Noa Allouche and Almog Hasson as part of a Java software development course.
