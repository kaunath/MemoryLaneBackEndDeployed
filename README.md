# Project Name

Memory Lane is an online platform where users can create their travel diaries by uploading photos from recent destinations. Explore others' adventures, connect with like-minded travelers, and build a community around shared travel experiences. Engage with interactive social features, discover new destinations, and showcase your wanderlust through vivid visuals.

Join Memory Lane and embark on a global journey through the eyes of fellow adventurers.

## Getting Started

### Prerequisites

1. Ensure you have [Git](https://git-scm.com/) installed to clone the repository.
2. Create an account on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) to manage your MongoDB database.

### Installation

```bash
git clone [repository_url]
cd [project_directory]
npm install
````

### Setting Up MongoDB Atlas
- Follow [this link](https://www.mongodb.com/cloud/atlas) to create an account on MongoDB Atlas.
- Create a database in MongoDB Atlas with a username, password, and database name of your convenience.


### Postman Setup
- If you don't have Postman installed, install Postman to test different API endpoints.
- Learn how to use Postman [here](https://learning.postman.com/).

### JWT Authentication
- Learn about JWT (JSON Web Tokens) and its usage [here](https://jwt.io/)

### Google Geocoding API
- Learn about Google Geocoding API [here](https://developers.google.com/maps/documentation/geocoding/overview)

### Configuration

Create a `nodemon.json` file and include the following:

```json
{
  "env": {
    "DB_USER": "[your_database_username]",
    "DB_PASSWORD": "[your_database_password]",
    "DB_NAME": "[your_database_name]",
    "API_KEY": "[your_google_geocoding_api_key]",
    "JWT_TOKEN": "[your_jwt_token]"
  }
}
```
### Running the Project

`npm run dev`

Now, your project is ready to go! Open Postman, test the API endpoints, and explore the features.

