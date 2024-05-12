## Introduction

The Currency Converter Application, designed with Android Studio, offers a practical solution for converting currencies. Its unique interface allows users to specify the source currency, target currency, and the amount to convert. The application communicates with the external API "https://api.freecurrencyapi.com" to fetch the latest exchange rates.

## Features

### API Interaction

The application performs requests to the API using the endpoint "v1/latest" with the following parameters:
- `apikey=sgiPfh4j3aXFR3l2CnjWqdKQzxpqGn9pX5b3CUsz`
- `base_currency=USD`
- `currencies=AUD`

The JSON response from the API is parsed, and the extracted conversion rate is used to calculate the final conversion.

### User Interface

The main page of the application offers input fields to specify:
- Source currency
- Target currency
- Amount to convert

Users can submit the request by pressing a button, thus initiating the conversion process.

### API Parameters Analysis

- **API key**: `sgiPfh4j3aXFR3l2CnjWqdKQzxpqGn9pX5b3CUsz` for authentication.
- **Base Currency**: Sets the base currency as the US Dollar (USD).
- **Currencies**: Specifies the currencies to include in the response, with an example of the AUD (Australian Dollar).

## Conclusion

The Currency Converter Application provides a simple and effective user experience for currency conversion by connecting to the API "https://api.freecurrencyapi.com". The screenshots (not included here) demonstrate the ease of use of the application and the clarity of the results obtained after conversion. This project highlights the ability to create functional and informative applications to meet user needs while accurately analyzing the parameters of the used API.
