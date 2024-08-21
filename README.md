![Application Overview](https://www.accuknox.com/wp-content/uploads/2023/06/accuknox-logo-2.png)


# Front-End Trainee Assignment

## Overview

This project demonstrates the use of various front-end technologies to build a user-friendly and interactive application. The application leverages React and JavaScript along with several libraries and tools to create a dynamic user interface, implement Material Design, manage styling, display charts, and ensure code quality through testing.

## Screenshots

### 1. Application Overview

![Application Overview](./images/application-overview.png)

*Caption: A snapshot of the application's main user interface.*

### 2. Chart Visualization

![Chart Visualization](./images/chart-visualization.png)

*Caption: A chart demonstrating data visualization capabilities.*

## Project Structure

### 1. **React (react, react-dom)**

- **Purpose**: React is the core library used to build the user interface. It allows for the creation of reusable components and efficient updates to the UI based on state changes.
- **Installation**: 
  ```bash
  npm install react react-dom
  ```

### 2. **Material-UI (@mui/material, @mui/icons-material)**

- **Purpose**: Material-UI provides a collection of React components that implement Google’s Material Design. It helps create a modern and responsive user interface.
- **Installation**: 
  ```bash
  npm install @mui/material @mui/icons-material
  ```

### 3. **Emotion (@emotion/react, @emotion/styled)**

- **Purpose**: Emotion is used for writing CSS styles with JavaScript. It allows for dynamic styling and theming of components.
- **Installation**: 
  ```bash
  npm install @emotion/react @emotion/styled
  ```

### 4. **FontAwesome (@fortawesome/react-fontawesome, @fortawesome/free-solid-svg-icons)**

- **Purpose**: FontAwesome provides a library of icons that can be easily integrated into the application to enhance user experience.
- **Installation**: 
  ```bash
  npm install @fortawesome/react-fontawesome @fortawesome/free-solid-svg-icons
  ```

### 5. **Chart.js (chart.js, react-chartjs-2)**

- **Purpose**: Chart.js is used for creating charts and visualizing data. `react-chartjs-2` integrates Chart.js with React, allowing you to create interactive charts.
- **Installation**: 
  ```bash
  npm install chart.js react-chartjs-2
  ```

### 6. **Testing Libraries (@testing-library/react, @testing-library/jest-dom, @testing-library/user-event)**

- **Purpose**: These libraries are used for testing React components. They ensure that components render correctly and user interactions work as expected.
- **Installation**: 
  ```bash
  npm install @testing-library/react @testing-library/jest-dom @testing-library/user-event
  ```

## How It Works

1. **Setup and Installation**
   - Clone the repository: `git clone <repository-url>`
   - Navigate to the project directory: `cd <project-directory>`
   - Install dependencies: `npm install`

2. **Running the Application**
   - Start the development server: `npm start`
   - Open your browser and go to `http://localhost:3000` to view the application.

3. **Component Structure**
   - The application is structured around reusable React components.
   - Components are styled using Emotion and Material-UI to ensure a consistent look and feel.

4. **Data Visualization**
   - Chart.js is used to render charts. Data for these charts is managed and passed to chart components as props.

5. **Testing**
   - Unit tests are written using @testing-library/react and @testing-library/jest-dom.
   - Run tests with: `npm test`

## Example Commands

- **Start Development Server**: `npm start`
- **Run Tests**: `npm test`
- **Build for Production**: `npm run build`

## Contributing

If you wish to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a pull request.

## License

This project is licensed under the MIT License.
