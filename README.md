
# AI
It's just a simple web AI using OpenAI GPT-3 and flask (Python)  

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd 
   ```

4. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

5. Install the requirements

   ```bash
   $ pip install -r requirements.txt
   ```

6. Create a `.env` file


7. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

8. Run the app

   ```bash
   $ flask run
   ```

## Customize

You can change your AI, you need to change the `conversation` and add or delete what you want to be your real AI

You can update the picture on main.css ` <img src="{{ url_for('static', filename='manga.png') }}" >`
 

![OpenAI](https://i.blogs.es/0dbd39/openai-gpt-3/1366_2000.jpg)

## Authors

- [@Antoine Smet](https://github.com/AntoineSmet/)

