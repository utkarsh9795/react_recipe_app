Here is the demo of this project

[Demo Link](https://utkarsh-recipe-site.netlify.app) 

# React Recipe App

Welcome to the **React Recipe App**, a dynamic and user-friendly application designed to help you explore, search, and save your favorite recipes. Built with React.js, this project showcases modern web development practices, integrating powerful features to deliver a seamless user experience.

## Features

- **Recipe Search:** Easily search for a variety of recipes using keywords or ingredients.
- **Recipe Details:** View detailed information about each recipe, including ingredients, instructions, and preparation time.
- **Favorites:** Save your favorite recipes for quick access later.
- **Responsive Design:** Fully responsive design, ensuring a great experience on both desktop and mobile devices.
- **API Integration:** Fetches data from a third-party recipe API for a vast collection of recipes.
- **State Management:** Efficient state management using React's Context API or Redux.
- **User-Friendly Interface:** Intuitive and easy-to-navigate UI.

## Tech Stack

- **Frontend:** React.js
- **Styling:** CSS Modules / Styled Components
- **State Management:** Context API / Redux
- **Routing:** React Router
- **API:** Integration with an external recipe API 
- **Build Tool:** Vite / Create React App
- **Version Control:** Git

## Installation and Setup

Follow these steps to set up and run the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/react-recipe-app.git
   cd react-recipe-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Create an `.env` file in the root directory and add your API key:**

   ```env
   REACT_APP_API_KEY=your_api_key_here
   ```

4. **Start the development server:**

   ```bash
   npm start
   ```

   The application will be available at `http://localhost:3000`.

## Usage

1. **Search Recipes:** Enter a keyword or ingredient in the search bar to find recipes.
2. **View Recipe Details:** Click on a recipe to see its details, including ingredients and instructions.
3. **Save Favorites:** Click the "Favorite" button to save recipes for quick access later.

## Folder Structure

```
react-recipe-app/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── RecipeList.js
│   │   ├── RecipeDetail.js
│   │   ├── Favorites.js
│   │   └── SearchBar.js
│   ├── context/
│   │   └── RecipeContext.js
│   ├── services/
│   │   └── api.js
│   ├── styles/
│   │   └── App.css
│   ├── App.js
│   ├── index.js
│   └── ...
└── package.json
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your forked repository.
4. Submit a pull request.


