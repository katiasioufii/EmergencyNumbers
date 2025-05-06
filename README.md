# Emergency Numbers API

This repository contains a **JSON file** with **emergency contact numbers** for various countries. The data is structured in a way that can be easily accessed for use in projects that require emergency information.

### Purpose

The goal of this project is to provide a centralized resource of emergency numbers from around the world. This JSON file can be used in various applications, especially in contexts where quick access to emergency services is crucial.

The numbers include:
- Police
- Fire
- Ambulance
- Disaster

This is designed to be used as an API or as a local resource for accessing emergency contact numbers across different countries.

## Table of Contents
- [About](#about)
- [Countries Included](#countries-included)
- [How to Use](#how-to-use)
- [How to Add More Countries](#how-to-add-more-countries)
- [Usage in Your Project](#usage-in-your-project)
- [License](#license)

## About

This JSON file includes emergency contact numbers for different countries, such as the **United States**, **Brazil**, **India**, and more. These numbers are important for users to access emergency services in case of accidents, health issues, or natural disasters.

### Countries Included:
- US
- CA (Canada)
- MX (Mexico)
- BR (Brazil)
- AR (Argentina)
- CO (Colombia)
- CL (Chile)
- PE (Peru)
- EC (Ecuador)
- AU (Australia)
- NZ (New Zealand)
- ZA (South Africa)
- EG (Egypt)
- KE (Kenya)
- NG (Nigeria)
- DZ (Algeria)
- MA (Morocco)
- TH (Thailand)
- VN (Vietnam)
- MY (Malaysia)
- SG (Singapore)
- IN (India)
- CN (China)
- JP (Japan)
- KR (South Korea)
- PK (Pakistan)
- PH (Philippines)
- ID (Indonesia)
- SA (Saudi Arabia)
- AE (United Arab Emirates)
- IL (Israel)
- KW (Kuwait)
- LB (Lebanon)
- SY (Syria)
- OM (Oman)
- JO (Jordan)
- IQ (Iraq)
- IR (Iran)
- TR (Turkey)
- GR (Greece)
- IT (Italy)
- ES (Spain)
- FR (France)
- GB (United Kingdom)
- PT (Portugal)
- BE (Belgium)
- CH (Switzerland)
- CZ (Czech Republic)
- PL (Poland)

## How to Use

To use this file in your project, you can either:
1. **Directly import the JSON file** into your project and use it to fetch emergency numbers based on the country.
2. **Set up an API** to dynamically serve the JSON data via an HTTP request.

### Example of Accessing Data (in JavaScript):
```javascript
fetch('path-to-your-json-file.json')
  .then(response => response.json())
  .then(data => {
    console.log(data.US.police);  // Logs the police emergency number for the US
  });
How to Add More Countries
If you'd like to add more countries or update the numbers, you can edit the JSON file directly. Here’s the format:

json
Copy
Edit
"COUNTRY_CODE": {
  "police": ["emergency_number"],
  "fire": ["emergency_number"],
  "ambulance": ["emergency_number"],
  "disaster": ["emergency_number"]
}
Just follow the existing structure and add the new country's emergency numbers. After editing, simply commit the changes to the repository.

Usage in Your Project
This repository can be used in various types of projects:

Mobile Apps: Incorporate the emergency numbers into your mobile app to allow users to quickly access emergency services.

Web Apps: Use this data to show emergency contact details in your web application.

Other Software: If your software needs to handle emergency situations, you can integrate this data.

The data is already structured in a way that makes it easy to integrate into any programming language or framework.

License
This project is intended for personal or private use. Feel free to integrate it into your projects, but please do not distribute it for commercial purposes unless permission is granted.

