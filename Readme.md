# My SaaS Platform

## Overview

This repository contains the structure for an enterprise SaaS platform UI built using the React framework with a micro-frontend architecture. The project is divided into multiple micro-frontend applications, each of which can be developed, deployed, and maintained independently.

## Project Structure

- `microfrontends/`
  - Contains individual micro-frontend applications (e.g., `app1`, `app2`).
  - Each application has its own `src`, `public`, `package.json`, and `webpack.config.js`.

- `container/`
  - The main container application that integrates all micro-frontends.
  - Contains its own `src`, `public`, `package.json`, and `webpack.config.js`.

## Libraries

### Dependencies

### Dependencies

- **React** (^17.0.1): A JavaScript library for building user interfaces.
- **React-DOM** (^17.0.1): Provides DOM-specific methods that can be used at the top level of your app.
- **Axios** (^0.26.1): Promise-based HTTP client for the browser and Node.js.
- **React-Quill** (^2.0.0): A Quill component for React.
- **AWS-RUM-Web** (^1.13.7): The Real User Monitoring SDK for AWS.
- **MobX** (^6.9.0): Simple, scalable state management.
- **MobX-React** (^7.6.0): React bindings for MobX.
- **Axios-Retry** (^3.5.0): Axios retries for failed requests.
- **React-Query** (^3.39.3): Data fetching and caching library for React.
- **React-Toastify** (^9.1.3): React component for toast messages.
- **ESLint** (^8.12.0): Linting utility for JavaScript.
- **ESLint-Plugin-React** (^7.29.4): React specific linting rules for ESLint.
- **Lodash** (^4.17.21): A utility library for JavaScript.
- **Apollo-Client** (^3.5.10): A comprehensive state management library for JavaScript apps.
- **i18next** (^21.6.6): Internationalization framework for JavaScript.
- **Formik** (^2.2.9): Form management for React.
- **Yup** (^0.32.11): JavaScript schema builder for value parsing and validation.
- **Storybook/React** (^6.5.10): Tool for developing UI components in isolation.
- **Jest** (^27.5.1): Test runner for JavaScript testing.
- **Date-Fns** (^2.27.0): Toolkit for manipulating dates.
- **React-Helmet** (^6.1.0): React component for managing document head tags.
- **Framer-Motion** (^5.4.5): Animation library for React.
- **React-Error-Boundary** (^3.1.3): React component for error boundaries.
- **@Emotion/CSS** (^11.11.0): Library for styling components in React.
- **React-Testing-Library** (^12.1.5): Testing utilities for React components.
- **@Ant-Design/Icons** (^4.11.2): Ant Design icons library for React.
- **React-Hook-Form** (^7.18.0): Performant forms with easy-to-use hooks.
- **@Apollo/Client** (^3.5.4): Library for interacting with GraphQL APIs.
- **React-Intl** (^5.22.4): Internationalization library for React.
- **Recharts** (^2.0.10): Charting library for React.
- **@Lexical/Core** (^0.8.9): Library for lexical analysis in JavaScript.
- **@Lexical/React** (^0.8.0): React bindings for Lexical.
- **React-File-Upload** (^1.5.0): Component for uploading files in React.
- **React-Dates** (^21.8.1): Datepicker component for React.
- **React-Paginate** (^7.1.5): Pagination component for React.
- **Bugsnag-JS** (^7.0.6): Real-time error monitoring and reporting tool.
- **React-Helmet-Async** (^1.2.0): Asynchronous version of React Helmet for managing document head tags.
- **Socket.io-Client** (^4.3.2): Real-time communication library for the web.
- **React-Doc-Viewer** (^1.14.1): Document viewer component for React.
- **@Cyntler/React-Doc-Viewer** (^1.14.1): Enhancement package for React Doc Viewer.
- **Mixpanel-Browser** (^2.41.0): Library for event tracking and analytics  

### DevDependencies

- **webpack**: Module bundler.
- **webpack-cli**: Command line interface for webpack.
- **webpack-dev-server**: Development server for webpack.
- **babel-loader**: Loader for transpiling JavaScript files using Babel and webpack.
- **@babel/core**: Babel core package.
- **@babel/preset-env**: Smart preset that allows you to use the latest JavaScript without needing to micromanage which syntax transforms are needed.
- **@babel/preset-react**: Babel preset for React.
- **html-webpack-plugin**: Simplifies creation of HTML files to serve webpack bundles.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn

### Installation

1. Clone the repository:
   ```sh
   cd my-saas-platform

Install dependencies:
    npm install

Start the development server:
    npm start

Building for Production
Run the following command to build the project for production:
    npm run build

