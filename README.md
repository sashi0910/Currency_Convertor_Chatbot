# Currency Converter Chatbot
## Table of Contents
1. Project Overview
2. Features
3. Requirements
4. Installation
5. Configuration
6. Usage
7. How It Works
8. Technologies Used
9. Future Enhancements
10. Contributing
11. License
12. Acknowledgements

## Project Overview
The Currency Converter Chatbot is an intelligent assistant that helps users convert currencies in real-time. It integrates with Dialogflow for natural language understanding and uses a Flask-based API to fetch live exchange rates.

## Features
1. Real-Time Currency Conversion: Provides instant conversion rates between various currencies.
2. Natural Language Understanding: Leverages Dialogflow to understand user queries and respond accurately.
3. Support for Multiple Currencies: Can convert between a wide range of currencies.
4. User-Friendly Interaction: Engages users through a conversational interface.

## Requirements
- Python 3.7 or later
- Flask
- Dialogflow
- Requests library

## How It Works
- User Input: The user initiates a conversation by asking the chatbot to convert a currency.
- Dialogflow Processing: Dialogflow processes the natural language input and extracts parameters like amount and currency type.
- Webhook Request: Dialogflow sends a POST request to the Flask webhook with the extracted parameters.
- Currency Conversion: The Flask app receives the request, fetches the latest exchange rates using the specified API, and calculates the conversion.
- Response: The chatbot replies with the converted amount in the target currency.

## Technologies Used
- Python: Core programming language for backend development.
- Flask: Micro web framework for creating the API.
- Dialogflow: Platform for natural language processing and chatbot development.
- Requests: Library for making HTTP requests to fetch exchange rates.
- ExchangeRate-API: Third-party service for obtaining current exchange rates.

## Future Enhancements
- Voice Interaction: Integrate with voice services like Google Assistant for voice commands.
- Historical Data: Provide historical exchange rates and trends.
- Enhanced Currency Support: Add support for cryptocurrencies and additional fiat currencies.
- User Profiles: Store user preferences and conversion history.

## Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (`git checkout -b feature-branch`).
Commit your changes (`git commit -m 'Add new feature'`).
Push to the branch (`git push origin feature-branch`).
Create a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Dialogflow: For providing a powerful platform for building conversational interfaces.
Flask: For being an easy-to-use and flexible web framework.
