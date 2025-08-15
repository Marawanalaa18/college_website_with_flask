# Faculty of Computing and Information - Website

## Overview

This project is a website for the Faculty of Computing and Information built using the Flask framework. The website provides comprehensive information about the faculty including academic departments, study programs, vision and mission, and contact methods.

## Features

- **Home Page**: Displays an overview of the faculty, its vision, mission, and academic departments.
- **About Page**: Provides detailed information about the faculty's vision, mission, and strategic goals.
- **Departments Page**: Showcases the various academic departments and their specializations.
- **Programs Page**: Explains the available study programs, graduation requirements, and the education system.
- **Contact Us Page**: Provides contact information and the location of the faculty.
- **Responsive Design**: The website works well on all screen sizes (phones, tablets, computers).
- **Arabic User Interface**: The website is designed in Arabic with right-to-left (RTL) support.

## Technical Stack

- **Backend**: Python Flask
- **Frontend**: HTML, CSS, JavaScript
- **CSS Framework**: Bootstrap 5 (with RTL support)
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Cairo)

## Installation

### Prerequisites

- Python 3.6 or higher
- pip (Python package manager)

### Setup

1. Clone the repository or download the source code

2. Navigate to the project directory
   ```
   cd college_site
   ```

3. Create a virtual environment (optional but recommended)
   ```
   python -m venv venv
   ```

4. Activate the virtual environment
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

5. Install the required packages
   ```
   pip install flask
   ```

## Usage

1. Run the application
   ```
   python app.py
   ```

2. Open your web browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

## Project Structure

```
├── app.py                 # Main Flask application file
├── static/                # Static files directory
│   ├── css/               # CSS stylesheets
│   │   ├── about.css      # Styles for about page
│   │   ├── base.css       # Base styles for all pages
│   │   ├── contact.css    # Styles for contact page
│   │   ├── departments.css # Styles for departments page
│   │   ├── index.css      # Styles for home page
│   │   ├── main.css       # Main stylesheet
│   │   └── programs.css   # Styles for programs page
│   └── js/                # JavaScript files
│       └── main.js        # Main JavaScript file
└── templates/             # HTML templates
    ├── about.html         # About page template
    ├── base.html          # Base template (layout)
    ├── contact.html       # Contact page template
    ├── departments.html   # Departments page template
    ├── index.html         # Home page template
    └── programs.html      # Programs page template
```

## Development

To contribute to this project:

1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For more information, please contact the faculty administration.