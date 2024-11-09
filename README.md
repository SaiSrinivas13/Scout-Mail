# Scout-Mail
ScoutMail is a web application that validates email addresses using the Email Validation API. It provides a user-friendly interface to check the validity of email addresses and displays detailed results.

## Features
### 1.  Email Validation: 
Scout-Mail allows users to validate email addresses by leveraging the Email Validation API. When an email address is entered and submitted, the application sends a request to the API, which checks the email address for various factors such as format validity, domain existence, and mailbox status. The results are then displayed in a detailed and organized manner, providing users with insights into the validity of the email address.

### 2.  Responsive Design: 
The application is designed to be fully responsive, ensuring that it works seamlessly across a variety of devices and screen sizes. Whether the user is accessing ScoutMail from a desktop, tablet, or smartphone, the interface adjusts accordingly to provide an optimal viewing and interaction experience. This makes it convenient for users to validate email addresses on the go or from different devices.

### 3. User-Friendly Interface: 
Scout-Mail features a simple and intuitive interface that makes it easy for users to validate email addresses without any hassle. The input field for entering the email address is prominently displayed, and the submit button is easily accessible. Once the email address is submitted, the validation results are presented in a clear and organized format, allowing users to quickly understand the status and details of the email address. The use of visual elements such as tables and loading indicators enhances the overall user experience.

## Getting Started
### Prerequisites
* HTML: Understanding of HTML to structure the web application.
* CSS: Basic knowledge of CSS to style the web application.
* JavaScript: Proficiency in JavaScript to handle the email validation logic and API integration.
* API Integration: Familiarity with making API requests and handling responses in JavaScript.

### Installation
1. Clone the repository:
   ```
   
   git clone https://github.com/SaiSrinivas13/Scout-Mail
   
   ```
2. Navigate to the project directory:
   ```

   cd Scout-Mail
   
   ```
3. Open index.html in your web browser.

### Usage:
1. Open the application in your web browser.
2. Enter the email address you want to validate in the input field.
3. Click the "Submit" button.
4. The validation results will be displayed below the input field.

### Project Files:
#### 1. index.html
   The main HTML file that contains the structure of the web application.

#### 2. style.css
The CSS file that styles the web application.

#### 3. index.js
The JavaScript file that handles the email validation logic and interacts with the Email Validation API.

### API Integration:
The application uses the Email Validation API to validate email addresses. The API key is stored in the JavaScript file and used to make requests to the API.

#### Example API Request:
```

let url = `https://api.emailvalidation.io/v1/info?apikey=${key}&email=${email}`
let res = await fetch(url)
let result = await res.json()

```

### Contributing
Contributions are welcome!! Please fork the repository and create a pull request with your changes.
