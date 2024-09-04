


# DevOps Vue

This is a simple Vue.js application named **DevOps Vue** that displays the current URL and port of the running application.

## Features

- Displays the full URL of the application.
- Displays the port number on which the application is running.

## Prerequisites

- Node.js (version 12 or higher)
- npm (Node Package Manager)

## Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd devops-vue
   ```

   Replace `<repository-url>` with the actual URL of your repository.

2. **Install dependencies**:

   ```bash
   npm install
   ```

## Running the Application

To run the application, use the following command:

```bash
npm run serve
```

By default, the application will run on `http://localhost:8080`. 

### Changing the Port

If you want to change the port on which the application runs, you can do so by modifying the `package.json` file or by using the command line.

#### Method 1: Modify `package.json`

1. Open the `package.json` file in your project directory.
2. Find the `scripts` section and modify the `serve` command to include the desired port. For example, to change the port to `3000`:

   ```json
   "scripts": {
     "serve": "vue-cli-service serve --port 3000"
   }
   ```

#### Method 2: Command Line

You can also specify the port directly in the command line when starting the application:

```bash
npm run serve -- --port 3000
```

## Accessing the Application

Once the application is running, open your web browser and navigate to:

- Default: `http://localhost:8080`
- If you changed the port: `http://localhost:3000` (or whatever port you specified)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### Instructions to Run on Linux

1. **Open a terminal**.
2. **Navigate to your project directory** where the `devops-vue` application is located.
3. **Follow the installation and running instructions** provided in the README above.

### Summary

This README provides a comprehensive guide on how to set up and run your `devops-vue` application, including how to change the port. Make sure to replace `<repository-url>` with the actual URL of your repository if you are cloning from a repository.
