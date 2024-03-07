# PassCheck

The provided HTML document represents a Password Strength Checker website with additional features such as password generation and weather information display. Here's a detailed description of its functionality:

The website allows users to input passwords into the designated field. As the user types, the script dynamically evaluates the password strength based on criteria such as length, presence of uppercase and lowercase letters, numbers, and special characters. The strength of the password is categorized as Weak, Medium, or Strong, and it is visually represented in the interface. The script provides feedback on the number of characters, uppercase and lowercase letters, numbers, and special characters in the password.

Users have the option to generate strong passwords using the "Generate Password" button. Generated passwords consist of a mix of uppercase letters, lowercase letters, numbers, and special characters, with a minimum length of 12 characters. The generated password is shuffled to increase randomness and security.

Visual feedback is provided through buttons that change color to indicate whether the password contains specific types of characters (uppercase, lowercase, numbers, and special characters).

The website fetches a random quote from an external API (quotable.io) each time a new password is generated. The quote is displayed in the interface for users to see.

Furthermore, the website requests permission to access the user's device location. If permission is granted, it fetches the user's current location using the Geolocation API. It then uses the latitude and longitude coordinates to fetch the current temperature and weather condition from an external weather API (weatherapi.com). The fetched weather information, including the location name, temperature, and weather condition, is displayed on the website.

Visual styling is applied using CSS to enhance readability and user experience. Visual elements such as buttons, input fields, and text are styled to provide a visually appealing and intuitive user interface.

In summary, the website provides a comprehensive tool for users to check the strength of their passwords, generate strong passwords, and access weather information based on their current location, all within a visually appealing and user-friendly interface.

## Team members

- [@BhadraR](https://www.github.com/Bhadra2005)
- [@JesseTeresaBiju](https://www.github.com/jesteresabiju)
- [@AryaPradeep](https://www.github.com/aryapradeep147)
- [@AshwiniNK](https://www.github.com/123MGHVH)

## Screenshots

![App Screenshot](1.jpg)
![App Screenshot](2.jpg)

## How it Works ?

The Password Strength Checker website evaluates the strength of user-input passwords in real-time based on their length, presence of uppercase and lowercase letters, numbers, and special characters. It visually categorizes the password strength as Weak, Medium, or Strong.

Users can also generate strong passwords with a minimum length of 12 characters using the "Generate Password" button. These passwords consist of a mix of uppercase letters, lowercase letters, numbers, and special characters, ensuring robust security.

The website displays a random quote each time a new password is generated, fetched from an external API (quotable.io). Additionally, it requests permission to access the user's device location to display current weather information, including temperature and condition, based on their coordinates fetched using the Geolocation API.

Visual styling using CSS enhances the interface's readability and user experience, making it visually appealing and intuitive. In summary, the website offers users a comprehensive tool for assessing password strength, generating strong passwords, and accessing weather information within a user-friendly interface.


## Libraries used

The provided HTML document utilizes several web technologies and APIs to implement its functionality. Here's an overview of the libraries and APIs used:

1. JavaScript: The primary scripting language used to implement interactive behavior and dynamic content on the web page.

2. CSS: Cascading Style Sheets are employed to style and format the visual elements of the webpage, enhancing its appearance and layout.

3. Geolocation API: Used to retrieve the user's current geographical location, enabling the website to display location-specific weather information.

4. Fetch API: Utilized to make HTTP requests to external resources such as the weather and quote APIs, enabling data retrieval and integration into the webpage.

5. quotable.io API: An external API that provides random quotes. The website fetches quotes from this API to display them dynamically on the webpage.

6. weatherapi.com API: Another external API used to retrieve current weather information based on the user's location. The website fetches weather data from this API to display temperature and weather conditions.

7. HTML5: The latest version of Hypertext Markup Language is used to structure and define the content of the webpage, including elements such as input fields, buttons, and text areas.

8. Font Awesome: Although not explicitly mentioned, Font Awesome icons are likely used for the eye icon that toggles password visibility. Font Awesome provides a library of scalable vector icons that can be easily integrated into web projects.

Overall, these libraries and APIs enable the website to provide features such as password strength checking, password generation, random quote display, and weather information retrieval based on the user's location.

## How to configure

Configuring the Password Strength Checker website involves setting up and adjusting various aspects of its functionality and appearance. Here's a general guide on how you might configure it:

1. API Keys: If you're using external APIs like the quotable.io API or weatherapi.com API, you'll need to sign up for accounts on these services and obtain API keys. These keys are typically provided after registration and are required to authenticate your requests to the APIs.

2. API Endpoints: Once you have your API keys, you'll need to ensure that the API endpoints used in the JavaScript code are correct and match the endpoints provided by the APIs you're using.

3. Styling: You can adjust the CSS styles in the <style> section of the HTML document to customize the appearance of the website. This includes colors, fonts, sizes, and layout adjustments to match your desired look and feel.

4. HTML Structure: If you need to add or remove elements from the HTML structure, you can modify the layout to accommodate additional features or to streamline the user interface.

5. JavaScript Logic: The JavaScript functions control the behavior and functionality of the website. You can modify these functions to customize how password strength is calculated, how passwords are generated, and how external APIs are called and handled.

6. Permissions: If your website requests permission to access the user's location, you should ensure that the functionality works correctly and that users are properly informed about why their location is being accessed and how it will be used.

7. Testing: Before deploying your changes, it's essential to thoroughly test the website to ensure that all features function as expected across different browsers and devices.

8. Deployment: Once you've configured and tested the website, you can deploy it to a web server or hosting platform to make it accessible to users on the internet.

By following these steps and making adjustments as needed, you can configure the Password Strength Checker website to meet your specific requirements and preferences.

## How to Run

1. Clone the repository `https://github.com/Bhadra2005/PasswordStrengthChecker.git`
2. Run `index.html`
