# ViewBot Application

A GUI application built with PyQt5 and Selenium for automating YouTube views.

## Prerequisites

- Python 3.9 or higher
- Google Chrome browser
- ChromeDriver (matching your Chrome version)

## Installation Steps

1. **Clone the repository**
   ```bash
   git clone [your-repository-url]
   cd [repository-name]
   ```

2. **Create a virtual environment (optional)**
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **ChromeDriver Setup**
   - Download ChromeDriver that matches your Chrome browser version from [ChromeDriver Downloads](https://sites.google.com/chromium.org/driver/)
   - Place the ChromeDriver executable in the `webdrivers` folder

## Running the Application

### Method 1: Running from Python
