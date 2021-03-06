## Installation

 Make sure you have python3 and pip installed


 Create and activate virtual environment using virtualenv
 ```bash
 $ python -m venv python3-virtualenv
 $ source python3-virtualenv/bin/activate
 $ python3-virtualenv\Scripts\activate (For Windows)
 ```

 Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all dependencies

 ```bash
 pip install -r requirements.txt
 ```

 ## Usage


 Create a .env file using the example.env template


 Start flask development server
 ```bash
 $ export FLASK_ENV=development 
 $ set FLASK_ENV=development (For Windows)
 $ flask run
 ```

 ## Contributing
 Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

 Please make sure to update tests as appropriate.
