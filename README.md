## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Overview

This registration form allows students to input their personal details, including name, email, password, telephone number, gender, and age. Upon submission, the data is sent to a PHP script (`irene.php`) for processing.

## Features

- User-friendly input fields for:
  - Full Name
  - Email Address
  - Password
  - Telephone Number (with country code selection)
  - Gender selection
  - Age input (restricted between 18 and 30)
- Simple and clean design

## Technologies Used

- HTML5
- CSS3 (linked stylesheet `redform.css`)
- PHP (for form processing)

## File Structure

. ├── index.html # Main HTML file for the registration form ├── redform.css # Stylesheet for styling the form └── irene.php # PHP script to handle form submission

bash
Copy code

## How to Use

1. Clone the repository to your local machine using:
   ```bash
   git clone https://github.com/yourusername/student-registration-form.git
Open the index.html file in your preferred web browser.
Fill in the required fields and click "Submit" to send your data to the irene.php script for processing.
Contributing
Contributions are welcome! If you'd like to improve this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Make your changes and commit them (git commit -m 'Add some feature').
Push to your branch (git push origin feature/YourFeature).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

