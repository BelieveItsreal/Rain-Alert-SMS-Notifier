# Rain-Alert-SMS-Notifier
This Python code retrieves weather data from the OpenWeatherMap API for a specified location. It checks the hourly weather forecast for the next 12 hours and determines if it will rain during that period.
If rain is predicted, it uses the Twilio API to send an SMS message to a specified phone number, reminding the recipient to bring an umbrella. The Twilio API requires account SID and authentication token, which need to be provided in the code.

# _**To use this code, you need to replace the placeholders with your own details such as account SID, API key, latitude, longitude, Twilio virtual number, and Twilio verified real number.**_

## **Once the message is sent, the code prints the status of the message, indicating whether it was successfully delivered or not.**

### **To add the API to the code, follow these steps:**

Sign up for an account on the OpenWeatherMap website (https://openweathermap.org/) and obtain an API key.

Copy your API key and replace the placeholder "YOUR API KEY" in the code with your actual API key obtained from OpenWeatherMap.

Sign up for an account on the Twilio website (https://www.twilio.com/) to get your Twilio account SID and authentication token.

Replace the placeholder "YOUR ACCOUNT SID" in the code with your Twilio account SID.

Set up a Twilio virtual number and verify your real phone number with Twilio. Replace the placeholders "YOUR TWILIO VIRTUAL NUMBER" and "YOUR TWILIO VERIFIED REAL NUMBER" in the code with your respective Twilio virtual number and verified real number.

If you are behind a proxy, modify the code to include the necessary proxy settings. Otherwise, you can leave the code as is.

Save the modified code.

Make sure you have the required packages installed: requests, twilio, and os. If not, install them using pip.

Run the code. It will retrieve the weather forecast, check if rain is predicted, and send an SMS message if rain is expected within the next 12 hours.

Make sure to keep your API keys, account SID, and authentication token confidential and do not share them publicly.
