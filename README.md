# Gif-Expert-App

This is a React project created with Vite that allows users to search for GIFs using the GIPHY API.Users can enter a search term in the search bar and the app will display a list of GIFs related to the search query.

<img width="1038" alt="Screenshot 2023-06-14 at 12 41 15" src="https://github.com/sebastianroar/Gif-Expert-App/assets/112570917/b447947c-f2f9-46f2-80b3-ed1f9d6be984">

## Features

1. Search for GIFs based on user input
2. Display a list of GIFs matching the search query
3. Responsive design for different screen sizes

## Getting Started

1. Clone the repository:
    ```
    
    git clone https://github.com/your-username/Gif-Expert-App.git
    
    ```
2. Navigate to the project directory.
    ```
    
    cd Gif-Expert-App
    
    ```
3. Install the dependencies:
    ```
    
    npm install
    
    ```
4. Create a GIPHY API key:
    - Visit the GIPHY Developer Dashboard and create an account (if you don't have one already).
    - Create a new app and obtain an API key.
5. Create a .env file in the root directory of the project and add the following line, replacing YOUR_API_KEY with your GIPHY API key:
    ```
    
    VITE_API_KEY=YOUR_API_KEY
    
    ```
6. Start the development server:
   ```
   
   npm run dev
   
   ```
   This will start the app in development mode. Open http://localhost:3000 in your browser to see the app.

## Build

To build the project for production, run the following command:

```

npm run build

```
This will generate an optimized build of the app in the dist directory.

---
This project was made as part of Fernando Herrera's course "React: From zero to expert"
