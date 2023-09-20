# EcoRide -- Team "Go Big or Go Home"
Members: Khalil Burns, Shu Chen, Jet Chiang, Jonathan Qian

## Documentation and website
- A working website deployed with Firebase Hosting: https://uber-hackathon-de6f1.web.app
- Project Proposal: [EcoRide – Where Sustainable Ridesharing Meets the Future of Urban Mobility](https://docs.google.com/document/d/1gaHmGHSE5t4xnwp2LIjBirs6nvmM8TvIeSA0xAQKRmo/edit)

## Project Background
### Introduction:
Go Big or Go Home is an Uber Virtual Global Hackathon team situated in Ottawa. Our prototype products include EcoRide, a visionary web application designed to provide a unique solution for the traffic problem in major cities by facilitating and encouraging ridesharing. Cities around the world are facing the difficult challenge of traffic congestion and escalated emissions. We have noticed how inefficient private cars are and on the other hand, public transportation failed to become a suitable replacement due to its own limitations. Therefore, our team has redirected its focus towards optimizing individual auto-transportation as a means to address these pressing urban mobility challenges. We had our initial inspiration from the growing popularity in ridesharing, a perfect fusion of private vehicle's convenience and public transit's efficiency. Many people drive to work alone routinely every morning. With our app, they could pick up passengers travelling in the same direction and share the gas price. Our project matches drivers with passengers for mutually beneficial cooperation in which both parties can travel more economically with environmental-friendliness in mind. As a result, we can reduce the number of cars on the road, therefore cutting emissions and alleviating the traffic congestion problem in the hectic metropolis, shortening travel time. Ultimately, EcoRide is an inititative contributing to sustainable smart cities of the future. 

### Uniqueness:
* Unlike most apps that only allow immediate ride requests, EcoRide allows users to schedule rides for later in the day or on the following day, offering unprecedented convenience and flexibility.
* Convenience is one of our major strengths – it tremendously simplifies the ridesharing process by handling all the complications of matching and planning, requiring the users to input only basic information and returning a comprehensive trip overview.
* It is highly specialized and meticulously optimized for the sole purpose of facilitating ridesharing, resulting in a seamless and efficient experience for users
* Integration with the current Uber Transportation ecosystem (and a 5% transaction fee can be charged if applicable)

### Features:
* Google Maps API provides real-time feedback of distance and time for matching drivers and passengers. It also plans routes to pick up and drop off passengers with minimal detours, considering all environmental factors such as traffic conditions
* Firebase services such as Real-Time Database allow users to store their information (phone, email, vehicle...) and be retrieved when needed. We compare new input from riders with existing entries of drivers

## User's Manual:
1. Users login/sign-in in the landing page
2. In the home page, choose whether you would like to become a driver or search for a ride
3. Driver information will be stored in database while rider requests will be stored and processed immediately
4. The passenger will be paired with a driver by computing the distance and time deviation from the driver's original route. Wait after submitting a request and the user will be automatically redirected to a rides overview page
5. After route analysis, we will provide a list of the top 5 closest drivers from which passengers can choose from
6. Once the offer is accepted by the driver, the passenger will be notified and a trip overview (including email, contact, time, fee) will be shown to both users
8. The driver could log in to the app again and use our provided planned route to pick up passengers. He/She could also choose to export the map to Google Maps on any mobile device.
9. Payment should be made via e-transfer between the driver and the user. In the next stage, we would include a transaction feature as well as a chat/communication channel between the user and the driver. We would also create a profile setting function for users to update their information after logged in at any time. 

## Troubleshooting and FAQs
* Q: The log-in page is not working properly (i.e. your submission doesn't redirect you automatically)
*     A: Please use the redirect button manually. Your login status has been updated and you will be able to access the main page.
* Q: It took a while for pairing
*     A: Generally, it should be completed within 1 minute. We run complicated algorithm to compute the optimal match and generate comprehensive trip overview for both parties so please wait patiently
* Q: The Google Map is not showing properly when arrived on the page
*     A: Please refresh the page and wait for reload patiently. It is just a minor issue and your data is saved.
* Q: Button is not displaying properly when entering driver/rider information
*     A: Be calm, do not worry. Simply re-enter your input. Despite possible visual flaw, your submission will still be received and recorded in the databse. As long as you can proceed to the waiting page, you are good to go!
* Q: It is difficult to enter the time manually
*     A: You are highly recommended to click on the clock and select a time from the drop-down instead of typing it manually, althought both option will work.
* Q: Cannot pin points on the Google Map. Is the site not responding?
*     A: You must type the location in the input box and Google Maps API will automatically convert it into a set of coordinates, which will be stored and used in our algorithm. Maps will suggest locations based on your input like a search bar suggestion, though it is not necessary to select from the dropdown list for the feature to work.
