# Bitasmbl-AI-Powered-Recipe-Finder-UI — AI-Powered-Recipe-Finder-UI

Description
A sleek, responsive web application that allows users to search for and display AI-generated recipes based on available ingredients. The focus is on creating an interactive, modular, and visually appealing front-end interface using modern design principles and component composition.

## Tech Stack
- React

## Requirements
- Use component-based architecture and modern UI principles
- Manage state using hooks or framework state tools
- Implement at least one transition or animation

## Installation
1. Clone the repository:
   bash
   git clone https://github.com/your-username/Bitasmbl-AI-Powered-Recipe-Finder-UI.git
   
2. Navigate to the project folder:
   bash
   cd Bitasmbl-AI-Powered-Recipe-Finder-UI
   
3. Install dependencies:
   bash
   npm install
   
4. Create a `.env` file in the project root and add your environment variables:
   env
   REACT_APP_API_BASE_URL=https://api.yourbackend.com
   

## Usage
1. Start the development server:
   bash
   npm start
   
2. Open your browser and go to `http://localhost:3000`
3. Enter ingredients into the search field to fetch AI-generated recipes.

## Implementation Steps
1. Scaffold a new React app using Create React App or your preferred boilerplate.
2. Set up a folder structure for components, hooks, and assets.
3. Create a `RecipeSearch` component to handle user input and trigger API calls.
4. Use `useState` and `useEffect` hooks to manage form state and fetch data from the API.
5. Build a `RecipeList` component to display recipe cards with title, image, and summary.
6. Integrate animations using CSS transitions or a library like Framer Motion for smooth UI feedback.
7. Implement a `RecipeDetail` modal or slide-out panel to show full recipe details on selection.
8. Apply responsive design principles and modular styling (CSS Modules or styled-components).
9. Test transitions and layout across devices to ensure responsiveness.
10. Optimize performance by memoizing components and lazy-loading images.

## API Endpoints
- GET /recipes?ingredients={comma-separated-list}
  - Description: Fetch AI-generated recipes based on provided ingredients.
  - Query Parameters:
    - `ingredients` (string): Comma-separated list of ingredient names.