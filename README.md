#  Trello API Postman Project

This project demonstrates how to interact with the Trello API using Postman. It includes a full set of CRUD operations for boards, lists, and cards, along with test scripts and environment variables.

---

##  Features

- ✅ Create, Read, Update, and Delete Trello Boards
- ✅ Manage Lists and Cards within Boards
- ✅ Environment variables used for security (API Key & Token)
- ✅ Test scripts included to validate API responses

---

##  Test Results

Tests were run using Postman's Collection Runner. All tests passed successfully.

![Test Results](screenshots/test_results_summary.png)

---

##  Collection Structure

The collection is neatly organized into folders and requests for each Trello feature:

- Board
  - Create Board
  - Get Created Board
  - Update Board
  - Delete Board
- List
  - Create List
  - Get Created List
  - Update List
- Card
  - Create Card
  - Get Created Card
  - Update Card
  - Delete Card
  
![Collection Structure](screenshots/collection_structure.png)

---

##  How to Run It

1. Clone this repository.
2. Open Postman.
3. Import the exported collection file (`Trello APIs.postman_collection.json`).
4. Set up your environment with:
   - `key`: your Trello API Key
   - `token`: your Trello Token
5. Run the collection using the Collection Runner.

---

##  Files Included

- `Trello APIs.postman_collection.json` – Main Postman collection
- `screenshots/` – Folder with test result screenshots
- `.env.example` – Example file to show required environment variables

---

##  Notes

- You’ll need a [Trello API Key and Token](https://trello.com/app-key) to run this project.
- Do **not** commit your real credentials.

---

##  Author

Panagiotis Mpalampanis  
[GitHub](https://github.com/Panos2050) | [LinkedIn](https://linkedin.com/in/panosmpalampanhs)


