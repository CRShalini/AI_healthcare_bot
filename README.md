# AI Healthcare Chatbot

AI Healthcare Chatbot is a project built using the RASA framework. The bot predicts the disease of the patient by their symptoms and suggests the appropriate medicine for it. The bot is trained using custom data. The operational behavior of the bot can be enhanced by feeding more data about the diseases and training the bot using those data fed.

## How to Run this Project

1. Clone the repository:
    ```sh
    git clone https://github.com/PrajwalGouthamMP/AI_healthcare_bot.git
    ```

2. Install RASA:
    ```sh
    pip install rasa
    ```

3. Install Flask:
    ```sh
    pip install flask
    ```

4. Navigate to the RASA bot directory:
    ```sh
    cd rasabot/
    ```

5. Run the RASA bot:
    ```sh
    rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml
    ```

6. Open a new terminal and navigate to the web app directory:
    ```sh
    cd ../webapp/
    ```

7. Run the Flask server:
    ```sh
    flask run
    ```

8. Visit the localhost link where the Flask server runs.

