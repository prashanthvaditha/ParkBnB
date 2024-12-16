# ParkBnB Project

## Overview
ParkBnB is a platform inspired by the sharing economy, aimed at addressing parking challenges in urban areas. Similar to Airbnb, it connects drivers with private parking spot owners to optimize space usage and reduce time spent searching for parking. By leveraging a relational database, the project seeks to provide an efficient, user-friendly parking solution.

## Key Features
1. **User Account Management**: Securely manage user information to deliver a personalized experience.
2. **Search and Book Parking**: Allow users to filter parking spaces by location, price, and duration.
3. **Payment Integration**: Support secure transactions via credit/debit cards, PayPal, and mobile wallets.
4. **Reservation and Confirmation**: Real-time availability updates and instant booking confirmation.
5. **Rating and Review System**: Enable users and owners to rate their experiences for quality assurance.
6. **Data Analytics and Insights**: Analyze parking trends to optimize platform performance.

## Technical Implementation
### Conceptual Data Modeling
- **EER Diagram** and **UML Diagram**: Developed to represent entities and relationships.
  
### Relational Model Design
- Structured using primary and foreign keys to ensure database normalization and integrity.
- Key Tables:
  - **User**: Manages user details.
  - **ParkingSpot**: Stores parking space information.
  - **Reservation**: Tracks booking details.
  - **Transaction**: Logs payment and transaction details.

### Database Systems
1. **MySQL**: 
   - Implemented relational model.
   - Includes queries for user data, parking trends, and revenue insights.
2. **MongoDB**:
   - Explored NoSQL implementation for future scalability.

### Python Integration
- **Database Access**: Utilized `pymysql` to connect Python with MySQL.
- **Data Visualizations**: Libraries like Matplotlib and Seaborn were used to generate graphs such as:
  - Most active parking spot owners.
  - Distribution of ratings.
  - Penalty amounts per city.

## Achievements
- Successfully designed and implemented a relational database system.
- Integrated analytics for operational efficiency and user behavior insights.
- Prototyped a NoSQL database for scalability.

## Future Enhancements
- Add real-time parking availability updates.
- Integrate GPS tracking for parking spots.
- Expand platform to include public parking spaces.

Please feel free to contact vaditha.s@northeastern for any questions

---
