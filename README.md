# sqlalchemy-orm-movie-booking-system

🎬 Movie Booking System using SQLAlchemy ORM
This repository contains a mini backend project built with Python and SQLAlchemy ORM, simulating a movie booking system where customers can book tickets for different movies. It demonstrates how to design relational models, establish relationships, and perform CRUD operations in a clean, object‑oriented way.

🔑 Features
- Database Schema Design using DeclarativeBase and ORM classes:
- Movies_tb – stores movie details
- Customers_tb – stores customer details
- Booking_tb – links customers and movies with booking timings
- Relationships:
- One‑to‑many and many‑to‑one mappings between movies, customers, and bookings
- Bidirectional navigation using back_populates
- Database Connection:
- PostgreSQL integration via create_engine
- CRUD Operations:
- Insert movies and customers
- Create bookings with foreign key references
- Query records using select()
- Delete records using delete()
- Reusable Query Function:
- select_orm(engine, tb) – fetches rows and introspects table columns dynamically

🛠️ Tech Stack
- Python 3
- SQLAlchemy ORM
- PostgreSQL

📚 Learning Outcomes
- Hands‑on practice with ORM modeling and relationships
- Confidence in writing reusable query functions
- Stronger understanding of session management and schema design
- Ability to explain ORM concepts like foreign keys vs relationships, lazy/eager loading, and bidirectional mapping

🚀 How to Run
- Clone the repository
- Install dependencies (sqlalchemy, psycopg2)
- Update the PostgreSQL connection string in create_engine
- Run the script to create tables and test CRUD operations
