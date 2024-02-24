
# Name-Sphere-ThreeJs (threejs package)

Name-Sphere-Three.js is a React component built using Three.js and @react-three/fiber library. It enables you to create captivating word clouds in a sphere shape, adding an interactive and visually appealing element to your web applications.



## How It Works

Name-Sphere-Three.js uses Three.js to create a 3D sphere and position words evenly across its surface. The component leverages @react-three/fiber for rendering 3D graphics in React applications. Users can pass an array of words as props to the NameSphere component, which then generates a word cloud with the specified settings.


## Demo 

![Demo](https://i.imgur.com/w6RAlXe.gif)



## Local Setup & Installation

To install Name Sphere Three.js locally and set up a project using it, follow these steps:

1. **Install Name Sphere Three.js**: Open your terminal and run the following command to install the package:

    ```bash
    npm install name-sphere-threejs
    ```

2. **Import NameSphere Component**: In your React project, import the `NameSphere` component from `"name-sphere-threejs"`:

    ```jsx
    import React from "react";
    import { NameSphere } from "name-sphere-threejs";
    ```

3. **Use NameSphere Component**: Use the `NameSphere` component in your React components as shown in the following example:

    ```jsx
    function App() {
      return (
        <NameSphere
          count={5} // Number of words in each row/column on the sphere
          radius={15} // Radius of the sphere
          words={["word1", "word2", "word3"]} // Array of words to display on the sphere
          color="black" // Default color of words
          hoveredColor="red" // Color of words when hovered
          width={"100%"} // Width of the canvas (you can use units like %, vh, vw, or px)
          height={"100vh"} // Height of the canvas (you can use units like %, vh, vw, or px)
        />
      );
    }

    export default App;
    ```

4. **Customize Props**: Customize the props of the `NameSphere` component as needed to adjust the appearance and behavior of the word cloud.

By following these steps, you'll be able to set up a project using Name Sphere Three.js in your local environment.

## Author

- [@Priyansh Khunt](https://github.com/KHUNTPRIYANSH)
## Props

- `count`: Number of words in each row/column on the sphere (default: `5`)
- `radius`: Radius of the sphere (default: `15`)
- `words`: Array of words to display on the sphere (default: `[]`)
- `color`: Default color of words (default: `"black"`)
- `hoveredColor`: Color of words when hovered (default: `"red"`)
- `width`: Width of the canvas (default: `"100%"`)
- `height`: Height of the canvas (default: `"100vh"`)

## Tips

- Experiment with different values for `count` and `radius` to adjust the density and size of the word cloud.
- Use colors that contrast well with the background for better visibility.
- Provide an array of diverse and relevant words for a more engaging word cloud experience.
- Try to keep the number of words in a multiple of 4 to make a good sphere
## Tech Stack

- React
- Three.js
- @react-three/fiber
- @react-three/drei
## Live Demo

 - [Demo](https://name-sphere-demo.vercel.app/)
 - [Portfolio](https://priyansh-khunt.vercel.app/)


## Feedback

If you have any feedback, please reach out to us at khuntpriyansh1@gmail.com

## Use Cases

- **Data Visualization**: Visualize textual data in a creative and engaging way, making it easier for users to explore and understand.
- **Educational Tools**: Create interactive educational tools such as vocabulary builders or language learning applications.
- **Marketing and Branding**: Use word clouds to showcase key themes, slogans, or brand values in marketing materials or presentations.

## Contribution

Contributions to Name Sphere Three.js are welcome! If you encounter any bugs, have suggestions for improvements, or would like to contribute new features, feel free to open an issue or submit a pull request on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).## Key Features

- **Interactive Word Cloud**: Users can interact with the word cloud by hovering over the words, which change color to indicate interactivity.
- **Customizable Settings**: Easily customize the appearance of the word cloud by adjusting parameters such as count, radius, colors, and more.
- **Easy Integration**: Seamlessly integrate the NameSphere component into your React applications with just a few lines of code.
## 🔗 Contact Me
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://priyansh-khunt.vercel.app/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/priyansh-khunt-2318061b0/)


