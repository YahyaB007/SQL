# SQL

# 🏎️ Formula 1 Racing Database

An SQL relational database designed to model the complex world of Formula 1 racing. It captures essential entities such as drivers, teams, circuits, races, sponsors, penalties, and results—enabling multi-dimensional analysis of performance, standings, and historical trends in the sport.

## 1. Short Description

The Formula 1 Database provides a structured framework for storing and analyzing all aspects of F1 competitions. It tracks race results, driver and team performance, penalties, sponsorship deals, and historical circuit data. This schema serves as the foundation for analytics dashboards, predictive modeling, and motorsport strategy research.

## 2. Tech Stack

The project was built using the following technologies:

🗄️ MySQL (8.0) – Core relational database for storing Formula 1 data.

📂 SQL Dump (.sql) – Final project file containing schema definitions and constraints.

📊 Entity-Relationship Diagram (ERD) – Visual model to illustrate relationships between tables.

🔗 Foreign Keys & Constraints – Ensure data integrity across drivers, races, and results.

📝 ENUM, DECIMAL, DATE, YEAR datatypes – Used for realistic modeling of attributes like driver status, sponsorship amounts, and circuit lengths.

## 3. Data Source & Structure

The database schema is fictional but modeled on real-world Formula 1 structures. It consists of interconnected tables that represent:

Drivers: Personal details, nationality, career stats, team affiliation.

Teams: Team names, base location, engine suppliers, championships won.

Races: Race events linked to circuits, dates, and weather conditions.

Circuits: Track locations, lap records, and characteristics.

Results: Driver positions, points, fastest laps, and retirements.

Penalties: Details of infractions, reasons, and race context.

Sponsors: Team sponsorship deals with financial values and timelines.

Driver Standings: Seasonal rankings, points, and championship progression.

## 4. Features

### • Business Problem

Formula 1 generates vast amounts of structured data (results, sponsorships, penalties, lap times). Without a centralized schema, analyzing trends across seasons becomes difficult, limiting insights for teams, analysts, and fans.

### • Goal of the Database

To create a single source of truth for Formula 1 analysis that can:

Track driver and team performance across multiple seasons.

Record race results and reasons for retirements/penalties.

Manage sponsorship contracts and financial contributions.

Preserve historical circuit records for benchmarking.

Enable calculation of driver standings season by season.

## 5. Business Impact & Insights

🏆 Performance Tracking – Identify top-performing drivers and teams over time.

📊 Seasonal Analysis – Compare results across circuits, weather conditions, and years.

💰 Financial Insights – Analyze sponsorship contributions and their impact on team success.

⚖️ Fair Play Monitoring – Record and review penalties to assess rule compliance.

🔮 Predictive Potential – Serve as a foundation for predictive analytics (e.g., who might win based on past performance).

## 6. Entity Relationship Diagram
