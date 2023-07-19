# Birthday Buddy - Frontend Component Practice

This is a simple demo project called "Birthday Buddy" that I built to practice creating components, using the `useState` hook, and passing data with props in a frontend application.

## Project Overview

The main goal of Birthday Buddy is to render a list of people with their information, including their name, age, and image. The project follows these steps:

1. **Import Data**: In `App.jsx`, import the data from `data.js` as an array of objects. Each object represents a person and contains properties such as name, age, and image URL.

2. **Setup State Variable**: Use the `useState` hook to set up the data as a state variable. This allows for modifications to the data and automatic reflection of those changes in the rendered output.

3. **Iterate and Render**: Display the number of items in the list by using the `length` property of the state variable. This information can be displayed as plain text or added to a message or heading element.

4. **Render the List**: Iterate over the data array using the `map` method. For each item in the array, render a `Person` component. The `Person` component should receive the person's data as props and render the image, name, and age information.

5. **Create List and Person Components**: Create a `List` component to hold the rendered items. The `List` component can be a simple `div` element containing the list of `Person` components.

6. **Clear List**: In `App.jsx`, add a button to clear the list. Define a function that resets the state variable to an empty array to implement the functionality.

## Design Preview

You can preview the design of the Birthday Buddy application in Figma by clicking [here](https://www.figma.com/file/e2vsLe9DMnXZIygNHkwGL1/Birthday-buddy?node-id=0%3A1&t=AGNWdO5QQGOoNCfD-1).

## Getting Started

To get started with this demo project, follow these steps:

1. Clone the repository: `git clone https://github.com/Mohamed-Esmat/react-component-practice.git`
2. Navigate to the project directory: `cd frontend-component-practice`
3. Install the dependencies: `npm install`
4. Start the development server: `npm run dev`
5. Open your browser and visit `http://localhost:3000` to see the Birthday Buddy application in action.

## Technologies Used

This project utilizes the following technologies and libraries:

- React: A JavaScript library for building user interfaces.
- Vite: A fast development build tool for modern web applications.
- JavaScript: The programming language used for the frontend logic.
- HTML: The markup language used for structuring the application.
- CSS: The styling language used for visual enhancements.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore the code and make any modifications to suit your needs. Contributions, issues, and pull requests are welcome!

## Acknowledgements

- This demo project was created as part of my frontend development practice.
- Special thanks to [John Smilga](https://johnsmilga.com/) for his course [React 18 Tutorial and Projects Course (2023)](https://www.udemy.com/course/react-tutorial-and-projects-course).

If you have any questions or suggestions, feel free to contact me. Happy coding!