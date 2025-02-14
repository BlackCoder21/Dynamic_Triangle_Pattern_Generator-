# Trianglify: A Web-Based Triangle Pattern Generator

## Overview
Trianglify is a user-friendly web application designed to generate right-aligned triangle patterns using asterisks (`*`). Developed with Flask, HTML, CSS, and JavaScript, it offers an interactive interface where users can specify the number of rows and instantly generate a triangle pattern.

## Features
- ✅ Intuitive web interface for seamless interaction
- ✅ Real-time triangle generation with Flask API
- ✅ Responsive and modern UI design
- ✅ Instant updates without page reloads
- ✅ Robust error handling for invalid inputs

## Technologies Used
- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS, JavaScript (AJAX)
- **Styling:** CSS for enhanced responsiveness

## Installation
### Prerequisites
- Python 3.x installed
- Flask installed (`pip install flask`)

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/BlackCoder21/Dynamic_Triangle_Pattern_Generator.git
   cd Trianglify
   ```
2. **Install Dependencies**
   ```sh
   pip install flask
   ```
3. **Run the Application**
   ```sh
   python app.py
   ```
4. **Open in Browser**
   Navigate to `http://127.0.0.1:5000/`

## Project Structure
```
Trianglify/
│── app.py                # Flask backend
│── templates/
│   └── index.html        # Frontend UI
│── static/
│   ├── styles.css        # CSS styling
│   └── script.js         # JavaScript for AJAX requests
│── README.md             # Project documentation
```

## Usage
1. Enter the desired number of rows in the input field.
2. Click the "Generate" button.
3. The triangle pattern will be displayed instantly on the screen.

## Example Output
For an input of `5`, the output will be:
```
    *
   **
  ***
 ****
*****
```

## Future Enhancements
- 🎨 Introduce multiple pattern styles
- 📐 Support left-aligned and centered triangles
- 🌐 Deploy as a live web application

## License
This project is open-source and licensed under the MIT License.

---
**Happy Coding! 🚀**

