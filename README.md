---

# Invoice Generation Site

## Overview

This is a simple, user-friendly invoice generation web application that allows users to create, manage, and download invoices. The application supports currency conversion to enhance usability for international clients.

## Features

- **User-Friendly Interface**: Clean and responsive design for easy navigation.
- **Dynamic Invoice Creation**: Users can add multiple items, input customer details, and automatically calculate totals.
- **Currency Conversion**: Users can enable or disable currency conversion and select the desired currency for the total amount.
- **PDF Download**: Option to download the generated invoice as a PDF document.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **HTML**: Markup for the web application structure.
- **CSS**: Styling using Bootstrap and custom styles for enhanced user experience.
- **JavaScript**: Dynamic functionality for the application, including invoice management and currency conversion.
- **APIs**: Integration with a currency exchange API for real-time conversion rates.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/invoice-generation-site.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd invoice-generation-site
   ```

3. **Open the `index.html` file in your preferred web browser**:

   ```bash
   open index.html
   ```

## Usage

1. Fill in the customer details, including name, email, and phone number.
2. Add invoice items by clicking the "Add Item" button, entering item name, quantity, and price.
3. Check the "Enable Currency Conversion" checkbox to enable conversion.
4. Select the desired currency from the dropdown to view the converted total.
5. Click the "Download Invoice" button to save the invoice as a PDF.

## API Information

- The currency conversion feature uses the ExchangeRate-API for real-time currency exchange rates. You may need to replace the API URL in the JavaScript code with your own if required.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to your branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---