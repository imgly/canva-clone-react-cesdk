# Canva Clone with React and IMG.LY's CE.SDK

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
   - [Available Scripts](#available-scripts)
5. [Essential Canva Features](#essential-canva-features)
6. [Using CE.SDK for These Features](#using-cesdk-for-these-features)
7. [Extending the Example](#extending-the-example)
8. [Learn More](#learn-more)
9. [License](#license)

## Introduction
This project demonstrates how to build a Canva-like design editor using React and IMG.LY's CreativeEditor SDK (CE.SDK). With this clone, users can create invitations, greeting cards, flyers, postcards, and business cards with ease.

![Canva Clone Demo](https://imgly-blog-prod.storage.googleapis.com/2022/07/creator-mode-cesdk.gif)

## Features
- Template Management
- Custom Asset Libraries
- Intuitive Drag-and-Drop Interface
- Advanced Image Editing Tools
- A host of design editing and composition features ([Learn More](https://img.ly/products/creative-sdk))

## Prerequisites
- Node.js and npm (version 8.0+)
- React (version 18 or higher)
- @cesdk/cesdk-js (version 1.6.3 or higher)

## Getting Started
To get started with this project, follow these steps:

1. Clone the repository:
    ```sh
    git clonegit@github.com:imgly/canva-clone-react-cesdk.git
    cd canva-clone-react-cesdk
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm start
    ```

### Available Scripts
Inside of the project directory, you can run the following scripts:

- **`npm start`**: Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser. The page will reload when you make changes. You may also see any lint errors in the console.
- **`npm test`**: Launches the test runner in interactive watch mode. See the section about running tests for more information.
- **`npm run build`**: Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified, and the filenames include the hashes. Your app is ready to be deployed!

## Essential Canva Features
To provide a Canva-like experience, our app should include:

1. **Template Management**: Predefined templates to help users start quickly.
2. **Asset Library**: Extensive collection of images, icons, and design elements.
3. **User Interface**: User-friendly, drag-and-drop interface.
4. **Customization Options**: Allow users to modify templates and elements.
5. **Different Export Formats**: Allow exporting designs in different formats such as PDF for print.
6. **Saving Work in Progress**: When saving our designs we want to ensure not to do so destructively to enable users to pick back up where they left off.

## Using CE.SDK for These Features
IMG.LY's CE.SDK simplifies the integration of these features:

- **Getting Started with React**: [CE.SDK Quickstart Guide](https://img.ly/docs/cesdk/ui/quickstart?framework=react)
- **Custom Templates**: [Guide to Custom Template Source](https://img.ly/docs/cesdk/ui/guides/custom-template-source/)
- **Custom Asset Libraries**: [Guide to Customize Asset Library](https://img.ly/docs/cesdk/ui/guides/customize-asset-library/)
- **Scene Format for Saving WIP**: [Guide to Creating Scenes](https://img.ly/docs/cesdk/engine/guides/create-scene/)

## Extending the Example
To further enhance your Canva clone, consider:

- **Extending the Editor with Plugins**: Use CE.SDK's plugins for such things as vectorization or [background removal](https://img.ly/showcases/cesdk/background-removal/web#c).
- **Batch Processing**: Implement features for processing multiple designs simultaneously.
- **Dynamic Content**: Use [CE.SDK's Variable API](https://img.ly/docs/cesdk/engine/api/variables/) for automated insertion of dynamic content.

## Learn More
For a detailed tutorial on building a Canva clone with CE.SDK, check out the [IMG.LY blog article](https://img.ly/blog/how-to-build-a-canva-clone-with-ce-sdk/). To learn more about IMG.LY and our offerings, visit our [home page](https://www.img.ly).

## License
While the code in this project is licensed under the MIT License. Using CE.SDK in your project requires a commercial license. 
You can obtain a license for trialing purposes by [signing up for our free trial](https://img.ly/forms/free-trial).
