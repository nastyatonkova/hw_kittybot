# hw_kittybot
###### Telegram bot that can send you funny random photos with cats.

### Functionality:
- Send random photo from API 'https://api.thecatapi.com/v1/images/search'
- Saying hi to the user

### How to run the project:

Clone repository to you PC and go to it with your terminal using CD command:

```
git clone https://github.com/yandex-praktikum/kittygram.git
```

```
hw_kittybot
```

Create and activate virtual environment:

```
python3 -m venv env
```

```
source env/bin/activate
```

Install dependencies from the file requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```
It is needed to create a file `.env` in the root folder to add your TOKKEN.
Your token you can become by @BotFather:
`/start
/newbot`

The Procfile specifies the start file when hosting.
