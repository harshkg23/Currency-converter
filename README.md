# Currency Converter

Currency Converter is a Vite-powered React-based web application that allows users to convert currencies using real-time exchange rate data fetched from an online API. The app offers an interactive user interface where users can input the amount to be converted, select the source and target currencies, and get the converted value based on live exchange rates. The application communicates with a third-party API to fetch the most up-to-date exchange rates. The frontend is styled using **Tailwind CSS** for a responsive and modern look.

---

## **Table of Contents**
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

---

## **Features**
- **Frontend**: Built with React using Vite for fast and optimized development.
- **Currency Conversion**: Allows users to convert currencies in real-time using live exchange rates.
- **API Integration**: Fetches exchange rates from a third-party API for accurate and up-to-date data.
- **Interactive Interface**: Simple and user-friendly interface to input currency amounts and select currencies for conversion.
- **Responsive Design**: Fully responsive design using Tailwind CSS, ensuring compatibility across all devices.
- **Real-Time Updates**: Automatically updates the conversion rates whenever the user selects a new currency pair.

---

## **Tech Stack**
- **Frontend**: React, Tailwind CSS, Vite
- **API**: Currency Exchange API for live exchange rates

---

## **Folder Structure**

Currency-converter/<br>
│<br>
├── public/         # Public files (index.html, images, etc.)<br>
│<br>
├── src/            # Source files (React components, styles)<br>
│   ├── components/ # React components for the UI<br>
│   ├── App.jsx     # Main React app component<br>
│   ├── main.jsx    # Entry point for the React application<br>
│   ├── style.css   # Global styling for the app (tailwind imports)<br>
│   └── tailwind.config.js # Tailwind CSS configuration<br>
│<br>
└── README.md       # Project documentation<br>

---

## **Installation**
### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/harshkg23/Currency-converter.git
   cd Currency-converter
2. Set up environment variables (see below).

3. Start the development server:
    ```bash
    npm install
    npm run dev
    ```
---


# Usage

1. **Open the frontend**: http://localhost:5173
2. **Select currencies**: Choose the source and target currencies from the dropdowns.
3. **Enter amount**: Input the amount you wish to convert.
4. **View result**: The converted amount will be displayed based on real-time exchange rates.

---

## **Contact**
- **Author**: Harsh Kumar Gupta  
- **Email**: harshkumargupta2023@gmail.com  
- **GitHub**: [https://github.com/harshkg23](https://github.com/harshkg23)

