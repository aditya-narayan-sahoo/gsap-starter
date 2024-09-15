# React GSAP Demo

This React project demonstrates various GSAP (GreenSock Animation Platform) methods, including `from`, `to`, `fromTo`, `stagger`, `trigger`, `text`, and `timeline`. 

## Features

- **GSAP Methods**:
  - `from`: Animates properties from a starting state to their current state.
  - `to`: Animates properties from their current state to a specified end state.
  - `fromTo`: Animates properties from one state to another state.
  - `stagger`: Animates elements with a delay between each animation.
  - `trigger`: Triggers animations based on scroll or other events.
  - `text`: Animates text content.
  - `timeline`: Creates complex sequences of animations.

## Setup and Installation

To clone and set up this project on your local machine, follow these steps:

### 1. Clone the Repository

Open your terminal and run the following command to clone the repository:

```bash
git clone https://github.com/aditya-narayan-sahoo/gsap-starter.git
```

### 2. Navigate to the Project Directory

Change into the project directory:

```bash
cd gsap-starter
```

### 3. Install Dependencies

Install the required npm packages:

```bash
npm install
```

### 4. Run the Development Server

Start the development server to view the project in your browser:

```bash
npm run dev
```

Your default browser should open automatically and navigate to `http://localhost:5173`, where you can see the GSAP animations in action.

## Project Structure

- `src/`
  - `pages/`: Contains React components demonstrating different GSAP methods.
    - `GsapFrom.jsx`
    - `GsapFromTo.jsx`
    - `GsapScrollTrigger.jsx`
    - `GsapStagger.jsx`
    - `GsapTimeline.jsx`
    - `GsapTo.jsx`
    - `Home.jsx`
    - `index.jsx`
  - `index.css` : Main styling code for the app.
  - `App.jsx`: Main application component where animations are set up.
  - `Main.js`: Entry point for the React application.
- `public/`
  - `index.html`: Main HTML file.
- `package.json`: Contains project metadata and dependencies.


## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Your contributions are welcome!

Feel free to modify the README and code samples to suit the specific requirements or features of your project.
