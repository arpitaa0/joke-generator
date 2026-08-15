# Joke Generator 😂

A simple and interactive Joke Generator web application built using **HTML, CSS, and JavaScript**.

The application uses the **JokeAPI** to fetch random jokes and display them on the screen. Users can generate a new joke with a click and easily copy the displayed joke to their clipboard.

## Features

* 🎭 Generate random jokes
* 🔄 Get a new joke with the **New Joke** button
* 📋 Copy the current joke using the **Copy Joke** button
* 🌐 Fetch jokes from an external API
* 📱 Responsive design for smaller screens
* ✨ Simple animations and clean user interface

## Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling, layout, responsive design, and animations
* **JavaScript** – API integration and application functionality
* **JokeAPI** – Used to fetch random jokes

## API Used

This project uses **JokeAPI** to fetch random jokes.

API endpoint:

`https://v2.jokeapi.dev/joke/Any`

## How It Works

1. The application sends a request to JokeAPI using JavaScript's `fetch()` method.
2. The API returns a joke in JSON format.
3. JavaScript extracts the joke from the response.
4. The joke is displayed on the webpage.
5. Clicking **New Joke** fetches another joke.
6. Clicking **Copy Joke** copies the displayed joke to the clipboard.

## Project Structure

```text
joke-generator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run

1. Clone this repository:

```bash
git clone < https://github.com/arpitaa0/joke-generator.git>
```

2. Open the project folder in VS Code.

3. Open `index.html` using **Live Server** or directly in your browser.

4. Click **New Joke** to generate a random joke.

## Future Improvements

* Add different joke categories
* Add a loading animation while fetching jokes
* Improve mobile responsiveness
* Add dark mode
* Add better error handling
* Add social sharing options

## Author

**Arpita Muduli**

---

⭐ If you like this project, feel free to star the repository!
