# GoodEats

## Overview

**GoodEats** is an interactive platform designed for food enthusiasts, tourists, and social media users who enjoy exploring and sharing restaurant experiences. The platform allows users to search for restaurants based on various filters, post reviews, and interact socially by sharing recommendations and experiences.

## Features

- **Restaurant Search:** Find restaurants based on location, cuisine type, rating, and distance using an interactive map.
- **User Reviews & Posts:** Users can share their dining experiences and promote favorite restaurants.
- **Social Interaction:** Engage with other users through comments and posts.
- **Advanced Filtering:** Utilize filters to narrow down restaurant searches.
- **Chatbot Assistance:** Get recommendations and platform-related answers using the integrated chatbot.

## Technologies Used

### Frontend (React + JavaScript)
- **Axios:** Handles HTTP/HTTPS requests.
- **React Toastify:** Provides aesthetic notifications.
- **React Router:** Enables seamless page navigation.
- **Material UI:** Supplies modern UI components (buttons, forms, grids).

### Backend (Node.js + Express + Python)
- **bcryptjs:** Encrypts user passwords.
- **cors:** Manages cross-origin requests between frontend and backend.
- **dotenv:** Handles environment variables.
- **jsonwebtoken:** Implements JWT authentication.
- **multer:** Manages file uploads (e.g., images).
- **sequelize:** ORM for PostgreSQL database interactions.

### Database
- **PostgreSQL:** Stores user-generated content, restaurant data, and interactions.
- **Data Relationships:** Users can create multiple posts and comments, with posts supporting multiple comments.

### APIs and External Integrations
- **ArcGIS API:** 
  - Location-based search to find nearby restaurants.
  - Advanced filtering options based on cuisine, rating, and distance.
  - Interactive map for viewing restaurants and reviews.

- **Gemini API + Python (Flask):** 
  - AI chatbot for user queries.
  - Flask used to create RESTful APIs for chatbot communication.

## System Architecture

The application follows a client-server model, where the frontend interacts with the backend through RESTful APIs, and the backend processes requests and interacts with the PostgreSQL database.
