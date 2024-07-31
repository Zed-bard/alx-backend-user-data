 0x00-personal_data


| Task | Description |
|---|---|
| 0. Regex-ing | `filter_datum` function obfuscates log messages with regex. |
| 1. Log formatter | `RedactingFormatter` class accepts fields and filters values in logs. |
| 2. Create logger | `get_logger` function creates a logger named "user_data" for specific log levels and configures a `RedactingFormatter` with PII fields. |
| 3. Connect to secure database | `get_db` function retrieves database credentials from environment variables and connects to a secure MySQL database. |
| 4. Read and filter data | `main` function retrieves user data from the database, filters PII fields, and displays the results. |
| 5. Encrypting passwords | `hash_password` function creates a salted and hashed password from a plain text password. |
| 6. Check valid password | `is_valid` function validates a plain text password against a hashed password. |

## Project Description

**Personal Data Protection Project**

This project focuses on implementing measures to protect user personal data (PII) through secure handling and storage. It involves developing Python scripts to:

* **Obfuscate sensitive data** within log messages using regular expressions.
* **Create a secure logger** that filters and redacts PII before logging.
* **Establish a connection to a secure database** to store user data.
* **Implement password hashing** for enhanced security.


