# Safe-Stride
Safe Stride is a "One Stop" solution for ensuring elderly safety, which uses Geolocation to track the user's location and accelerometer readings to detect falls. It shows the user's live location on a map and provides an emergency alert feature that sends an SMS to a predefined number in case of a fall.

## Project Description

The Safe Stride is a web application that allows users to track the live location of an individual and detect falls in real-time. The system uses geolocation services to track the user's location and a device's accelerometer to detect falls. When the system detects a fall, it triggers an emergency alert and sends an SMS to a pre-configured contact. The web application includes a dashboard that displays the user's live location and an emergency alert trigger that displays the user's current location and acceleration magnitude. The system uses Leaflet, a popular open-source JavaScript library, to display the user's location on a map. The system is designed to be simple and easy to use, with a minimalistic interface that enables users to quickly access the information they need. Overall, the Save Stride is an effective tool for monitoring the well-being of individuals who are at risk of falls, such as the elderly or people with disabilities.

## Getting Started

1. Open the `https://naman-gururani.github.io/Safe-Stride/` file in a web browser.


![Screenshot (125)](https://user-images.githubusercontent.com/77580466/233870326-52f57f6e-19e6-4acf-860c-b0d502ef65ff.png)


2. Click the "Show Location" button to view the user's live location on a map.


![image](https://user-images.githubusercontent.com/77580466/233870184-8cf9e519-a8f2-49fa-8139-3785912194e4.png)


3. If the accelerometer detects a fall, an emergency alert will be triggered after a 30-second timer, which will send an SMS to the number specified in the `sendSMS()` function.


![image](https://user-images.githubusercontent.com/77580466/233869824-51fa0873-5a8e-4a3e-ba5c-8dacb351ddaa.png)


4. The emergency alert sms recieved by emergency contact.


![image](https://user-images.githubusercontent.com/77580466/233870245-ed4f0c49-5299-4329-8f02-37118bc51da7.png)


## Technologies Used

- HTML
- CSS
- JavaScript
- HTML Geolocation API
- Leaflet.js (a JavaScript library for interactive maps)
- jQuery (a JavaScript library for DOM manipulation)
- Twilio API (for sending SMS)

## Contributors

This project has been created by Piyush Gupta `https://github.com/piyush2cool` , Naman Gururani `https://github.com/Naman-Gururani` and Vishal Dubey `https://github.com/vishaldubey40`.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

