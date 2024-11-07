# Find job project

A job listing web application built with Vue.js and Vite. This project demonstrates the use of modern frontend technologies like Vue 3, Vue Router, and TailwindCSS for styling, along with backend API simulation using JSON Server.

## Features

- **Job Listings**: View and manage job listings including job type, salary, location, and company information.
- **CRUD Operations**: Create, read, update, and delete job listings.
- **Toast Notifications**: Feedback messages displayed for actions like job creation, update, and deletion.
- **Responsive Design**: Built using TailwindCSS for a mobile-first responsive layout.
- **Vue 3**: Built with Vue 3 for modern reactive UI components.
- **JSON Server**: A mock REST API for serving job data, simulating backend behavior.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) (version 16 or above)
- [npm](https://www.npmjs.com/get-npm) or [Yarn](https://yarnpkg.com/) for package management

### Steps to Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/vue-traversy.git
   cd vue-traversy

   ```

2. Install dependencies:

Using npm:

```bash
    npm install
```

Or using Yarn:

```bash
    yarn install
```

3. Run JSON Server:

The app uses `json-server` to simulate a backend API.

To start the JSON server, run the following command:

```bash
    npm run server
```

This will start the server on `http://localhost:5000` and will watch src/jobs.json for any changes.

4. Run the development server:

After starting the JSON server, run the following command to start the frontend:

```bash
    npm run dev
```

Your app will be available at `http://localhost:5173` (default Vite port).

### Environment Setup

This project is designed to run locally in development. There are no special environment variables required. However, the project assumes that the mock backend API is running on `http://localhost:5000`.

## Project Structure

```bash
vue-traversy/
├── src/
│   ├── assets/                 # Static assets (images, styles)
│   ├── components/             # Reusable Vue components
│   ├── pages/                  # Vue pages
│   ├── router/                 # Vue Router setup for navigation
│   ├── App.vue                 # Root Vue component
│   └── main.js                 # Entry point for the application
├── public/                     # Public assets (index.html)
├── src/jobs.json               # Mock job data for JSON Server
├── tailwind.config.js          # Tailwind CSS configuration
├── vite.config.js              # Vite configuration file
├── package.json                # Project metadata and dependencies
└── README.md                   # Project documentation (this file)
```

## Technologies Used

- Vue 3: Modern JavaScript framework for building UIs.
- Vite: A next-generation build tool that focuses on speed and performance.
- TailwindCSS: A utility-first CSS framework for creating responsive and customizable designs.
- Vue Router: A library for handling client-side routing in Vue.js applications.
- Axios: A promise-based HTTP client for the browser and Node.js.
- PrimeIcons: A collection of icons used within the application.
- Vue Toastification: A simple and customizable toast notifications library.
- JSON Server: A fast mock backend server for simulating API calls.

## Available Scripts

In the project directory, you can run:

`npm run dev`

Runs the app in development mode using Vite. Open `http://localhost:5173` to view it in the browser.

`npm run build`

Builds the app for production to the dist folder. It optimizes the build for the best performance.

`npm run preview`

Preview the production build in a local server.

`npm run server`

Starts the mock JSON Server on `http://localhost:5000`, which provides the backend API for job data.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request. Here are some ways you can contribute:

- Fix bugs
- Add features
- Improve documentation
- Submit suggestions for new features or improvements

To get started, clone the repository and install the dependencies:

```bash
    git clone https://github.com/yourusername/vue-traversy.git
    cd vue-traversy
    npm install
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

[Vue.js](https://vuejs.org/): The progressive JavaScript framework used for building the UI.

[Vite](https://vitejs.dev/): A next-generation build tool..

[Tailwind CSS](https://tailwindcss.com/): Utility-first CSS framework for responsive design.

[PrimeIcons](https://primeng.org/icons): The icon library used for the project.

[JSON Server](https://github.com/typicode/json-server): Fast and simple REST API mock server.

## Contact

For any questions or suggestions, feel free to contact the project maintainers:

- [Mahsa Ghezel - LinkedIn](https://www.linkedin.com/in/mahsaghezel/)

Thank you for using Vue Traversy! Enjoy building!
