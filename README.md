# API Tests – Postman Collection for trello.pl

This repository contains a set of basic API tests for the web application [trello.pl](https://trello.pl), created using Postman.

## About the Collection

- Covers fundamental HTTP methods: `GET`, `POST`, `PUT`, and `DELETE`
- Demonstrates the use of environment variables for authentication
- Useful for beginners learning API testing and Postman features

## How to Use the Collection in Postman

### Option 1: Import via Postman App

1. Open Postman
2. Click **"Import"** in the top-left corner
3. Select the file `Trello Portfolio EN.postman_collection.json` from this repository
4. Import the environment file `Trello Portfolio EN_environment.postman_environment.json`
5. Set your own credentials in the environment:
   - `apiKey` – your personal Trello API key
   - `apiToken` – your personal Trello API token  
   > You can get these credentials from your Trello account's developer settings.
6. Go to **Collections**, open `Trello Portfolio EN`, and click **Run** to start testing

### Option 2: Use Postman Web

1. Go to [Postman Web](https://web.postman.co/)
2. Sign in to your account
3. Click **"Import"**, then drag and drop the collection and environment files
4. Select the environment and run the collection manually or via the Collection Runner

## Requirements

- Postman (desktop or web)
- Internet access
- A Trello account to generate an API key and token

---

Feel free to clone or fork this repository to explore and run the test cases.