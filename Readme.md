# Movie Search Engine

A beginner-friendly **Movie Search Engine** built in React! This app lets you search for movies, view details, and practice key React concepts as you develop.

## Features

- **Live Search:** Type to search for movies using a real public API (like OMDb).
- **Movie List:** Browse search results with movie posters and basic info.
- **Movie Details:** Click a movie for more details—plot, actors, year, and more.
- **Responsive Design:** Works on desktop and mobile.
- **Learning Focus:** Clean structure with well-commented code to help you learn core React practices.

## Demo

_Insert a screenshot or live link here when ready!_

## Getting Started

These instructions will get your copy of the project up and running for development and learning purposes.

### Prerequisites

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)
- Basic terminal knowledge

### Installation

1. **Clone the repo:**

   ```
   git clone https://github.com/yourusername/movie-search-engine.git
   cd movie-search-engine
   ```

2. **Install dependencies:**

   ```
   npm install
   ```

3. **Start the dev server:**

   ```
   npm start
   ```

   This opens [http://localhost:3000](http://localhost:3000) in your browser.

### Setting Up the Movie API

This project uses the [OMDb API](http://www.omdbapi.com/). Get a free API key at [omdbapi.com/apikey.aspx](http://www.omdbapi.com/apikey.aspx).

Create a `.env` file in your project root and add:

    ```
    REACT_APP_OMDB_API_KEY=your_api_key_here
    ```

## Usage

- Enter a movie title in the search bar.
- View the list of results.
- Click a movie to see detailed information.

## Learning Outcomes

You'll learn:

- React functional components & JSX
- State management with `useState` and `useEffect`
- Making API calls with `fetch`
- Component composition
- Basic props and conditional rendering
- Environmental variables in React

## Project Structure

movie-search-engine/
├── public/
├── src/
│ ├── components/
│ ├── App.js
│ ├── index.js
│ └── ...
├── .env
├── package.json
└── README.md

## Contributing

Contributions are welcome! Open issues or submit pull requests to collaborate.

## License

MIT License

## Acknowledgements

- [React documentation](https://reactjs.org/docs/getting-started.html)
- [OMDb API](http://www.omdbapi.com/)

Happy Coding and Learning React!
