<h1 align="center">
  🌾 Manufac Assignment - Indian Agriculture Analytics
</h1>

---

## Overview

The **Manufac Assignment** is a data analytics application that processes crop data from the **Indian Agriculture Dataset** (provided by NITI Aayog, Government of India). The app displays important analytics in a dashboard format, helping users analyze key metrics like crop production, yield, and cultivation areas from 1950 to 2020.

---

## Application Features

- **Data Analytics**:
  - Displays two key analytics in a user-friendly table format:
    - **Crop with Maximum & Minimum Production per Year** (1950-2020).
    - **Average Yield & Average Cultivation Area per Crop** (1950-2020).
  
- **User Interface**:
  - Clean and responsive UI built with **React.js** and **Mantine** for modern table layouts and tab navigation.
  - Smooth transitions between tables using **Mantine Tabs** and **scrolling functionality** via Mantine's `useScrollIntoView` hook.
  
- **Performance Optimization**:
  - **Lazy loading** for efficient data handling.
  - **Modular codebase** for scalability and reusability.

- **Data Handling**:
  - Utilizes pure TypeScript functions to process and display crop data.
  - Constants are used to manage crop data keys to avoid errors and maintain consistency in data access.

---

## Tech Stack

- **TypeScript**: Ensures type safety and better code reliability.
- **React.js**: The front-end framework used to build the user interface.
- **Mantine**: A modern UI component library for building responsive components like tables, tabs, and hooks for smooth scrolling.
- **CSS Modules**: Scoped CSS styling to avoid global conflicts and maintain a clean design.

---

## Demo

You can view the live demo of the application here: [Live Demo](https://dataset-analysis.vercel.app/).

---

## Requirements

Before running the project locally, ensure that the following tools are installed:

- **Node.js**: A JavaScript runtime.
- **NPM**: Node package manager (comes with Node.js).

---

## How to Run the Project Locally

Follow the steps below to get the application running on your local machine:

1. **Clone the repository**:
   ```bash
$ git clone https://github.com/Nishka30/Dataset-Analysis
$ npm i
$ npm run dev

