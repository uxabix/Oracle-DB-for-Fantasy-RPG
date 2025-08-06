# RPG Game Database Project

This project is a comprehensive database schema for a Role-Playing Game (RPG), designed using Oracle SQL Data Modeler. It serves as a university portfolio piece for a course in database management. The database is designed to handle all core aspects of an RPG, including user accounts, characters, skills, items, quests, and game world interactions.

## Project Details

-   **Course:** Bazy Danych (Databases)
-   **University:** Politechnika Białostocka
-   **Semester:** 3rd Semester
-   **Academic Year:** 2024–2025
-   **Authors:**
    -   Kiryl Alishkevich
    -   Rafał Ciereszko

## Technologies Used

-   **Database Modeling:** Oracle SQL Data Modeler
-   **Database System:** Oracle Database
-   **Language:** SQL (DDL for schema generation)

## Project Structure

The repository is organized as follows:

-   `./Diagram ER Alishkevich Ciereszko/`: This directory contains the complete Oracle SQL Data Modeler project.
    -   `BDStruktura.dmd`: The main project file. This can be opened with Oracle SQL Data Modeler to view and edit the logical, relational, and physical models.
    -   `BDStruktura/`: A directory containing the detailed XML structure of the data model.
-   `./SQL/`: Contains the final, generated SQL script.
    -   `SQL to generate db for Oracle.txt`: The Data Definition Language (DDL) script required to create the entire database schema in an Oracle database.
-   `./Projekt Bazy Danych Ciereszko Alishkevich.pdf`: The official project documentation and report (in Polish).

## Database Schema Overview

The database is designed to be the backbone of an RPG. It includes entities to manage:

-   **Users & Characters:** User accounts, their game characters, attributes (strength, agility), classes, and races.
-   **Items & Inventory:** Different item types, their properties (rarity, value), and character inventories.
-   **Skills & Abilities:** Character skills, pet skills, skill types, and their effects (damage, mana cost).
-   **World & Interaction:** Locations, towns, NPCs, shops, and dungeons.
-   **Gameplay:** Quests, battles, guilds, achievements, and pets.

A detailed Entity-Relationship Diagram (ERD) is available in the project report (`.pdf`) and can be explored interactively by opening the `.dmd` project file.

## Setup and Usage

To set up the database, you will need access to an Oracle Database instance.

1.  **Clone the Repository:**
    ```sh
    git clone <repository-url>
    ```
2.  **Connect to Oracle Database:**
    Use your preferred SQL client (e.g., SQL Developer, SQL*Plus, DBeaver) to connect to your Oracle database schema/user.

3.  **Execute the DDL Script:**
    Run the script located at `SQL/SQL to generate db for Oracle.txt` in your SQL client. This will create all the necessary tables, primary keys, foreign keys, and other constraints.

    *Note: The script may contain some errors related to Oracle's 30-character limit for object names. These may need to be manually corrected for your specific Oracle version if they cause issues.*

4.  **Explore the Model:**
    To view or modify the data model, open the `Diagram ER Alishkevich Ciereszko/BDStruktura.dmd` file using Oracle SQL Data Modeler.