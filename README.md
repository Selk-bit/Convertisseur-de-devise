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

For more, visit my LinkedIn profile: [Salim Elkellouti](https://www.linkedin.com/in/salim-elkellouti/)
