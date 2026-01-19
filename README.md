# ISS Overhead Email Alert 🚀

This project checks whether the International Space Station (ISS) is overhead during nighttime.
If both conditions are met, an email alert is sent to the user.

## Features
- Uses ISS Location API
- Checks local nighttime using Sunrise-Sunset API
- Sends automated email alerts using SMTP
- Runs periodically to monitor ISS position

## Technologies Used
- Python
- APIs
- SMTP
- datetime module

## How It Works
1. Fetches current ISS coordinates
2. Compares with user's location
3. Checks if it's nighttime
4. Sends email alert if conditions match

## Note
API keys and email credentials are stored securely using environment variables.
