Great! Here's the updated documentation with your GitHub repository link:

---

# KoFakeGen - Koala Fake Data Generator

KoFakeGen is a Python tool designed to generate fake realistic data and populate PostgreSQL database tables with it. It takes user input for database credentials, schema name, and the number of rows to generate, and then automatically generates and inserts fake data into the specified tables.

## Installation

To use KoFakeGen, follow these steps:

1. Clone the KoFakeGen repository from GitHub:
    ```bash
    git clone https://github.com/jayronsoares/KoFakeGen.git
    ```

2. Install the required dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run KoFakeGen, execute the main script `kofakegen.py` from the command line:

```bash
python kofakegen.py
```

Follow the prompts to enter the required information:

1. Database Name: Enter the name of the PostgreSQL database.
2. Username: Enter the username for database authentication.
3. Password: Enter the password for database authentication.
4. Host: Enter the host address of the PostgreSQL database.
5. Port: Enter the port number of the PostgreSQL database.
6. Schema Name: Enter the name of the schema where tables are located.
7. Number of Rows: Enter the number of rows of fake data to generate for each table.

KoFakeGen will then connect to the specified database, retrieve metadata information about tables and columns in the specified schema, generate fake data based on the column data types, and insert the generated data into the tables.
