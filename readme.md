# Bajaj Finserv Health | Python Automation Task

This repository contains an automated Python solution for the Bajaj Finserv Health Qualifier 1 round, built with Python and environment variables to securely handle user input.

## ✅ Task Steps

1. *Webhook Generation:*
   - A POST request is sent to generate a webhook and access token.
   - The request includes user details (name, registration number, and email) from the .env file.

2. *SQL Question Determination:*
   - Based on the last digit of the registration number (reg_no), the script determines which SQL question to download.
   - A specific Google Drive link is printed based on whether the last digit of reg_no is odd or even.

3. *SQL Query Submission:*
   - The solution to the SQL problem is stored in solution.sql.
   - The final SQL query is submitted to a webhook using the generated access token for authentication.

4. *Successful Submission:*
   - After submission, the script confirms whether the submission was successful and prints the response.

## ▶️ How to Run

### 1. Clone this repository

```bash
git clone <your-repository-url>
cd bajaj