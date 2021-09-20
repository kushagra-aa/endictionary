# En Dictionary

<img src="static/assets/en-dictionary.png" alt="logo" width="200"/>

[Click Here To Visit](https://github.com/kushagra-aa/endictionary)

A Fast Dictionary for English language,

It shows The Meaning,Synonym and Antonym of the searched word.

> shows nothing if no synonyms or antonyms found

Made using PyDictonary and Django (of course)

Built with 🤍 For You!

## Screenshots

![image](https://user-images.githubusercontent.com/68841296/134009930-79118b76-80f0-439b-baca-820be58cab74.png)
![image](https://user-images.githubusercontent.com/68841296/134009970-731cdf59-56ea-488d-9de2-a512bb9dd9f9.png)
![image](https://user-images.githubusercontent.com/68841296/134009975-043946c2-78d0-46ec-afae-ff53155cecc6.png)

## Run Locally

Clone the project

```bash
  git clone https://github.com/kushagra-aa/endictionary.git
```

Go to the project directory

```bash
  cd endictonary
```

Install dependencies

```bash
  pip install -r requirements.txt
```

then run

```bash
python manage.py migrate
```

create admin account

```bash
python manage.py createsuperuser
```

then

```bash
python manage.py makemigrations
```

to makemigrations for the app

then again run

```bash
python manage.py migrate
```

to start the development server

```bash
python manage.py runserver
```

and open localhost:8000 on your browser to view the app.
