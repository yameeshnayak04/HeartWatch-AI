Steps to setup the project:

1. Clone the repository:

   ```bash
   git clone https://github.com/yameeshnayak04/HeartWatch-AI.git
    cd HeartWatch-AI
    ```
2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:
    ```bash 
    pip install -r requirements.txt
    or
    pip install fastapi uvicorn[standard] scipy numpy scikit-learn wfdb websockets python-multipart twilio requests
    ```