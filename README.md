
# Faal Hafez GUI

Faal Hafez GUI is a Java application that fetches and displays Hafez's poems and their interpretations from a REST API. The application provides a simple graphical user interface (GUI) for users to interact with.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [JSON and API](#json-and-api)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Features
- Fetches Hafez's poems and their interpretations from a REST API.
- Displays the poems and interpretations in a user-friendly GUI.
- Allows users to easily navigate between the home page and the poem page.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/faal-hafez-gui.git
   cd faal-hafez-gui
   ```

2. **Compile the code:**
   Make sure you have JDK installed. Then compile the Java files.
   ```bash
   javac -cp ".:json-simple-1.1.1.jar" GUI.java
   ```

3. **Run the application:**
   ```bash
   java -cp ".:json-simple-1.1.1.jar" GUI
   ```

## Usage
1. Run the application using the instructions in the installation section.
2. On the home page, click the "دریافت فال" button to fetch a poem.
3. The fetched poem and its interpretation will be displayed on a new page.
4. Click the "بازگشت" button to return to the home page.

## JSON and API
### JSON
JSON (JavaScript Object Notation) is a lightweight data-interchange format that is easy for humans to read and write, and easy for machines to parse and generate. In this project, JSON is used to format the data received from the API. Each poem and its interpretation are encapsulated in a JSON object, which is parsed and displayed by the application.

### API
The project uses a RESTful API to fetch Hafez's poems and their interpretations. The API endpoint used in this project is [https://faal.spclashers.workers.dev/api](https://faal.spclashers.workers.dev/api). When a user requests a poem, the application sends a GET request to the API. The response, which is in JSON format, contains the poem and its interpretation, which are then displayed in the GUI.

Here is an example of a JSON response from the API:
```json
{
    "Poem": "Example poem text",
    "Interpretation": "Example interpretation text"
}
```

The application uses the `json-simple` library to parse the JSON response and extract the required data.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## Authors
- [Mohammadreza Sheikholeslami](https://github.com/yourusername)

## Acknowledgments
- Special thanks to the [Faal API](https://faal.spclashers.workers.dev/api) for providing the poems and interpretations.

## Demo

![image](https://github.com/MohammadrezaSheikholeslami84/Hafez/assets/166950228/2fe47822-2ed9-40fc-8913-a8123d2f02d8)

![image](https://github.com/MohammadrezaSheikholeslami84/Hafez/assets/166950228/a476715a-04c0-44f2-a113-3c0185bd4a70)
