# Yew Solana Dapp Project Overview

## Project Structure
The project is organized into multiple Rust modules, including `button`, `phantom`, and `phantom_connect`, each responsible for different aspects of the Dapp's functionality.

## Phantom Wallet Integration
The Dapp seamlessly integrates with the Phantom wallet, a widely-used Solana wallet extension for browsers. This integration enables users to connect their Phantom wallet to the Dapp, facilitating Solana-related operations.

## Components
Utilizing Yew, a Rust framework for client-side web applications, the project constructs interactive and reactive components. Key components include `PhantomConnect`, managing the connection to the Phantom wallet, and various UI elements like buttons.

## HTML Structure
The `index.html` file establishes the foundational structure for the web application. It incorporates references to external CSS and JavaScript libraries and serves as the entry point for the application.

## Main Functionality
The core functionality of the Dapp revolves around tasks such as connecting to the Phantom wallet, executing Solana transactions, and engaging with the Solana blockchain.

## Debugging and Troubleshooting
Throughout the development process, we encountered challenges related to Phantom wallet integration, feature implementation, and debugging JavaScript errors.

## Improvements
Various enhancements were discussed to enhance the project, including restructuring the HTML layout to feature header and footer sections, aligning UI elements, and implementing error handling and logging to streamline debugging processes.

This project aims to deliver a user-friendly interface for interacting with the Solana blockchain via the Phantom wallet, leveraging the capabilities of Rust and Yew to create a robust and efficient web application.

Certainly! Below is a sample README.md file providing instructions on how to install the project from Git, set up Rust, Trunk, and Solana CLI, and import necessary libraries:

```markdown
# Yew Solana Dapp Project

Welcome to the Yew Solana Dapp project! This project aims to provide a user-friendly interface for interacting with the Solana blockchain using the Phantom wallet extension.

## Installation

To install and run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/yew-solana-dapp.git
cd yew-solana-dapp
```

### 2. Install Rust

Make sure you have Rust installed. You can install it using Rustup:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### 3. Install Trunk

Trunk is a build tool for WebAssembly projects. You can install it using Cargo:

```bash
cargo install trunk
```

### 4. Install Solana CLI

Make sure you have Solana CLI installed. You can install it using the following command:

```bash
sh -c "$(curl -sSfL https://release.solana.com/v1.9.4/install)"
```

### 5. Install Dependencies

Before running the project, install the necessary dependencies:

```bash
cargo update
```

## Usage

### 1. Build the Project

Use Trunk to build the project:

```bash
trunk build
```

### 2. Run the Project

Run the project using Trunk's development server:

```bash
trunk serve
```

### 3. Access the Application

Once the server is running, access the application in your web browser at http://localhost:8080.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

