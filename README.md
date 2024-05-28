# Currency Converter

The Currency Converter is a web application designed to help users convert between different currencies using the latest exchange rates. This application utilizes the Fetch API in JavaScript to dynamically fetch exchange rates from an external API and display them to the user.

![Screenshot 2024-03-19 213333](https://github.com/sanjay-1458/Currency-Converter/assets/121040100/080794e9-e131-428e-93bb-f410d823258a)


## Features

- **User-Friendly Interface:** The interface of the Currency Converter is simple and intuitive, making it easy for users to understand and interact with.
- **Dynamic Exchange Rates:** The application fetches the latest exchange rates from an external API, ensuring that users always have access to accurate and up-to-date information.
- **Customizable Conversion:** Users can input the amount they want to convert and select the currencies they are converting from and to using dropdown menus.
- **Visual Representation:** Flags representing the currencies being converted from and to are displayed alongside the dropdown menus for easy identification.

## Files Description

- **index.html:** This file contains the structure of the web page, including the form for inputting the amount to convert and selecting the currencies.
- **style.css:** The CSS file responsible for styling the elements of the Currency Converter, ensuring a visually appealing and responsive layout.
- **codes.js:** JavaScript file that contains functions for fetching exchange rates and updating the UI with the fetched data.
- **app.js:** JavaScript file responsible for handling user interactions and executing the necessary functions to convert currencies and display the results.

## Technologies Used

- **HTML:** Used for structuring the web page elements.
- **CSS:** Styling the elements to enhance the visual appeal and user experience.
- **JavaScript:** Utilized for fetching data from external APIs, handling user interactions, and dynamically updating the UI.
- **Fetch API:** Used to make asynchronous requests to fetch exchange rate data from an external API.

## Getting Started

To get a local copy of this project up and running, follow these steps:

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/sanjay-1458/Currency-Converter.git
   ```

2. Navigate to the project's directory:

   ```bash
   cd your-repo
   ```
3. Run live server 
4. Open your browser and visit [http://127.0.0.1:5500/](http://127.0.0.1:5500/) to see the project running.
5. Input the amount you want to convert in the "Enter Amount" field.
6. Select the currency you want to convert from in the "From" dropdown menu.
7. Select the currency you want to convert to in the "To" dropdown menu.
8. Click on the "Get Exchange Rate" button to fetch the latest exchange rate and see the converted amount.

## Api
```
https://2024-03-06.currency-api.pages.dev/v1/currencies/${currency}.json
```
Replace `${currency}` with `inr`, `usd`, etc...



