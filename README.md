# Simple CRUD Application Using MongoDB

This project is a Items data management application that allows users to manage items with attributes like name, description, and price using MongoDB as the database.

## Project Structure
server/

├── controllers/
│   └── itemControllers.js

├─ models/
│   └── items.js

├── public/
│   ├── index.html
│   ├── script.js
│   └── style.css

├── routes/
│   └── itemRoutes.js

└── server.js


## Features

- Create new items
- Read existing items
- Update item details
- Delete items
- User-friendly interface

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed on your machine.

### Installation

1. **Clone the Repository**: 
   ```bash
   git clone <repository-url>

2. **install dependencies**:
   ```bash
   npm init
   and other modules by npm i <moduleName>
   
3. **connect to database**:
   ```bash
    MONGODB_URI= '<your-mongodb-connection-string>'
4. **Run application**:
  node server.js
     (or)
  we can also use the nodemon.

5.Performance

Page Load Time: Under 3 seconds.
First Contentful Paint (FCP): Under 1.8 seconds.
Largest Contentful Paint (LCP): Under 2.5 seconds.
Time to Interactive (TTI): Under 5 seconds.
Total Blocking Time (TBT): Less than 300 ms.
Cumulative Layout Shift (CLS): Below 0.1.
Time to First Byte (TTFB): Under 200 ms.
Requests: Keep under 100.
Total Page Size: Keep under 2MB.

UI
![image](https://github.com/user-attachments/assets/8998855b-5afe-4a53-b80a-3f9f7b72521f)
