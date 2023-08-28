# Findr-Assignment

Backend Service for Efficient Email Search
Objective:
● Develop a robust backend service that empowers users to connect their Gmail accounts via OAuth
authentication and efficiently fetch emails received after a user-selected timestamp. This service will
streamline email searches and eliminate the hassle of manual retrieval.
● You're free to implement this assignment in any programming language, with Go and Python being the
preferred choices.
Requirements:
OAuth Authentication:
1. Implement OAuth 2.0 authentication to securely connect users' Gmail accounts to the backend service.
2. Utilise OAuth libraries or SDKs to facilitate the authentication process.
Timestamp-Based Email Retrieval:
1. Allow users to specify a timestamp (e.g., date and time) indicating the starting point for fetching emails.
2. Fetch all emails received after the provided timestamp.
Concurrency and Parallelism:
1. Implement concurrency and parallelism techniques to optimise email retrieval.
Extract Mail Data:
1. For each fetched email, extract the complete email body and handle attachments.
2. Encode the email body in Base64 format.