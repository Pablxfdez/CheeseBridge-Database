
# Cheesebridge Database Repository

Welcome to the Cheesebridge Database repository. This repository contains the schema, scripts, and related documentation for the Cheesebridge database.

## Cheesebridge Problem

**Cheesebridge** (or **Puentequeso** in Spanish) is an elegant Victorian city obsessed with money, class, and the most delicious stinky cheeses. Beneath its cobbled streets live the Boxtrolls, quirky and adorable monsters who wear recycled cardboard boxes just as turtles wear their shells. Every night, the Boxtrolls come out of the sewers of Cheesebridge to collect the cardboard containers discarded by its inhabitants. The retrieved boxes are classified and stored carefully, but the vast amount accumulated recently begins to make this task challenging. **Tuna** is a Boxtroll with some knowledge about relational database design, wishing to store the following information:

1. **The Boxtrolls form a harmonious community**. They all know each other by their own name and take care of each other. A fair distribution of tasks ensures the proper functioning of the colony, as each monster does the jobs for which they are most competent. In this aspect, there are two types of Boxtrolls: collectors (those who go out every night to get recycling material) and organizers (those in charge of classification and storage).

2. **The collectors retrieve, among other objects, cardboard boxes**. The organizers record their dimensions (height, width, and depth), as well as the place and date of the find. Once examined, the boxes are stored in the warehouse or worn by the Boxtrolls. The stored boxes indicate the shelf and shelf number where they are kept. For example, **Heel** found two camembert cheese boxes with dimensions of 40x40x40 at the Cheesebridge school on 10/11/2014. These boxes were processed by the organizer **Specs**, who stored one of them in the warehouse (shelf 4 - shelf 7) and registered the other as **Volt's** clothing.

3. **Many recycled containers in Cheesebridge have contained cheese**. Some have a very peculiar aroma, so the organizers sniff each box and take note of the stinkiest cheese it has stored (origin and intensity). For example, among the stinkiest cheeses are the vieux-Boulogne (France, intensity 10) and the pont-l'Eveque (France, intensity 9), while cheddar (UK, intensity 3) and parmesan (Italy, intensity 2) are the less aromatic cheeses.

## Repository Contents

1. **Cheesebridge Script.sql**: The SQL script containing the database schema, table creations, and any necessary setup operations.
2. **FernandezdelAmoP_EntregaProyecto.pdf**: A formal documentation that provides a comprehensive explanation of the database design, entities, relations, and other pertinent details about the database system.

## Getting Started

### Prerequisites

- Ensure you have an SQL database system compatible with the provided SQL script.
- An appropriate viewer for PDF files.

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone [git@github.com:Pablxfdez/CheeseBridge_Database.git]
   ```
2. Navigate to the repository directory:
   ```bash
   cd [repository-directory-name]
   ```

### Setting up the Database

1. Execute the SQL script to create the Cheesebridge database:
   ```bash
   your-sql-client -u [username] -p [password] < Cheesebridge Script.sql
   ```

> Note: Replace `your-sql-client` with the command for your specific SQL database system (e.g., `mysql`, `psql`), and replace `[username]` and `[password]` with your database credentials.

### Understanding the Database

For a deep dive into the design and nuances of the Cheesebridge database:

1. Open the `FernandezdelAmoP_EntregaProyecto.pdf`.
2. Explore the sections detailing the database entities, relations, and other significant details.

## Contributing

If you'd like to contribute to this project or report issues, please submit a pull request or open an issue through the repository's issue tracker.
