## Youtuber-academy

[![Deploy on Railway](https://railway.app/button.svg)](https://youtubers-academy.up.railway.app/)


## getting started


## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [About Author](#about-author)
- [Gallery](#gallery)


## Description

This website helps users to hire creators. Also they can perform some tasks like download youtube video,getting details about creator and their videos.It uses youtube APIS and web Scrapping.

## Features

- Login With Google
- Contact Form
- User Authentication
- User dashboard
- Responsive Design


## Installation

- Clone the repository
```
git clone https://github.com/Suraj1089/Heart-Charity.git
```
- Setup Virtual Environment 
to know more about virtual enviroment in python visit - https://docs.python.org/3/library/venv.html
```
    virtualenv env 
```
- Activate virtual enviroment
```
    cd env/Scripts
    .\activate
```

- Install the requirements
```
pip install -r requirements.txt
```
- Setup secrets
- Create .env file in main project directory and add the following secrets.
```
SECRET_KEY=your_project_secrest_key
DATABASE_NAME='project database name'
DATABASE_USER='project database user name'
DATABASE_PASSWORD='project database password'
```
- You can add other secrets key also. Note- <p style="color:#fcba03;">Take care while adding secrets in .env file their shoud not be space between '=' sign in both sides. </p>

- Database Setup
visit django project to know about database connectivity in django - https://docs.djangoproject.com/en/4.1/ref/databases/
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': env('DATABASE_NAME'),
        'USER': env('DATABASE_USER'),
        'PASSWORD': env('DATABASE_PASSWORD'),
        'HOST': 'localhost'
    }
}


Here, you can use any database you want. I have used PostreSQL database.


```

- Migrate the database
```
python manage.py make migrations
python manage.py migrate

```

- Create a superuser
```
python manage.py createsuperuser

```

- Run the server
```
python manage.py runserver

```

## Usage

- You can use this website contact with creators
- Also you can download youtube short videos,long videos,whole playlist and many more from this website.

## Contributing

You can clone the repository and make changes to it. It is open for all.


## License

[MIT](https://choosealicense.com/licenses/mit/)

## About Author

<a href="https://github.com/Suraj1089" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>

<a href="https://linkedin.com/in/surajpisal" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://surajpisal.netlify.com" target="_blank">
<img src=https://img.shields.io/badge/-Portfolio-red alt=linkedin style="margin-bottom: 5px;width:80px" />
</a>

<a href="https://instagram.com/suraj_pisal9" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</a>  

## Gallery
```
Home - http://127.0.0.1:8000/
```

![image](https://user-images.githubusercontent.com/85509795/205471938-d09a233b-7532-4e66-ba9f-83076e7c921e.png)


```
Services - http://127.0.0.1:8000/services/
```
![image](https://user-images.githubusercontent.com/85509795/205471959-03458f3f-b998-456e-a9de-d992fcc38685.png)




```
    download youtube video - http://127.0.0.1:8000/youtubedownload
```
![image](https://user-images.githubusercontent.com/85509795/205472183-b469a4c8-e921-4558-95bf-9de6f4f9ed6e.png)



