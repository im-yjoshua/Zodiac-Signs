# Zodiac Sign Finder

This is a simple Streamlit application that allows users to enter their name and birth date to find out their zodiac sign. The application will display the zodiac sign and save the user's information in a JSON file.

## Features

- Input your name and birth date
- Determine your zodiac sign based on your birth date
- Save the user's name, birth date, and zodiac sign in a JSON file

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
```
2. Navigate to the project directory:
```
cd <project-directory>
```
3. Create a virtual environment (optional but recommended):
```
python -m venv venv
```
4. Activate the virtual environment:
- On Windows:
```
venv\Scripts\activate
```
- On macOS and Linux:
```
source venv/bin/activate
```
5. Install the required packages:
```
pip install -r requirements.txt
```
## Usage
1. Run the Streamlit app:
```
streamlit run main.py
```
2. Open your web browser and go to the provided URL (usually `http://localhost:8501`).

3. Enter your name and birth date to find out your zodiac sign.

## File Structure
- `app.py`: The main application file.
- `database/`: A directory where JSON files will be saved.
- `requirements.txt`: A file containing the required packages for the project.

## Example
1. Enter your name in the input field.
2. Enter your birth date and birth month in the respective fields.
3. Click the "Check" button.
4. The application will display your zodiac sign.
5. A JSON file will be created in the `database/` directory with your information.

## Contributing
Feel free to fork the repository and submit pull requests. Any improvements and suggestions are welcome!

## License
This project is licensed under the MIT License.


## Notes

- Make sure to replace `<repository-url>` and `<project-directory>` with your actual repository URL and project directory name.
- Ensure the `requirements.txt` file contains the necessary dependencies, such as `streamlit`.

