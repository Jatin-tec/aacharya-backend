# Aacharya Flask Backend

## Description

This is the backend for the Aacharya application. It is built using Flask, a lightweight web framework for Python.

## Installation

1. Clone the repository:

    ```bash
    git clone git@github.com:Jatin-tec/aacharya-backend.git
    ```

2. Navigate to the project directory:

    ```bash
    cd aacharya-backend
    ```

3. Create a virtual environment:

    ```bash
    python3 -m venv venv
    ```

4. Activate the virtual environment:

    ```bash
    source venv/bin/activate
    ```

5. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Start Database:
    
    ```bash
    docker compose up --build -d
    ```

2. Start the Flask development server:

    ```bash
    flask run --debug
    ```

3. Open your web browser and navigate to `http://localhost:5000` to access the backend API.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.