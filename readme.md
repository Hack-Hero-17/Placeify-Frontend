# Placeify Frontend

## Project Overview

Placeify is a unique web application that allows users to discover, organize, and manage their favorite places efficiently. By creating categorized lists, users can keep track of various locations, such as restaurants, parks, or shops, and access their details conveniently.

## Features

- **Create Custom Lists**: Organize places into personalized lists for easy reference.
- **Search Functionality**: Find places using integrated search features and view relevant details.
- **Add Places to Lists**: Save searched places to your custom lists for quick access.
- **View Saved Places**: Access detailed profiles of saved places from your lists.

## Prerequisites

Before running the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

## Installation and Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Hack-Hero-17/Placeify-Frontend.git
   cd Placeify-Frontend
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Configure Environment Variables**:

   - Create a `.env` file in the root directory and add any necessary environment-specific variables.

4. **Start the Development Server**:

   ```bash
   npm start
   ```

5. **Access the Application**:

   Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage

1. **Create a List**:

   - Navigate to the "Lists" section.
   - Click on "Add New List" and enter a name for your list.
   - The new list will appear in the "Lists" section.

2. **Search for Places**:

   - Go to the "Places" section.
   - Enter a search term (e.g., "restaurants") in the search bar.
   - The app will display relevant search results.

3. **Add a Place to a List**:

   - Select a place from the search results to view its profile.
   - Click on "Add to List" and choose the desired list.
   - The place will be added to the selected list.

4. **View Saved Places**:

   - In the "Lists" section, select a list to view all saved places within it.
   - Click on a place to view its detailed profile.

## Future Enhancements

- **Delete Lists and Places**: Allow users to remove lists and places.
- **Data Persistence**: Store lists and places in a database for data persistence.
- **Add Custom Places**: Enable users to add custom places, such as friends' houses.
- **"Navigate Here" Integration**: Integrate with mapping services for quick navigation to saved places.
- **Enhanced Styling**: Implement more modular styling for a better user experience.

## Technologies Used

- **Frontend**: React
- **State Management**: Redux
- **Styling**: CSS

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project is developed by [Hack-Hero-17](https://github.com/Hack-Hero-17).
