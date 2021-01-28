## Django Boilerplate
Django-Boilerplate is minimimal pre-configure django framework for development.

## Requirements
- [Python Pip](https://pip.pypa.io/en/stable/installing/)
- [Virtualenv](https://virtualenv.pypa.io/en/latest/installation.html)

## Get started
- Clone this repo
```bash
$~ git clone https://github.com/ibnuhalimm/django-boilerplate.git <your-project-name>
```

- Install the virtualenv into your project
```bash
$~ virtualenv <your-project-name>
```

- Go to your project
```bash
$~ cd <your-project-name>
```

- Activate the virtualenv
```bash
$~ source bin/activate
```

- Install all of the dependencies
```bash
$~ pip install -r requirements.txt
```

- Setup .env file
```bash
$~ cp config/.env.example config/.env
```

- Generate new SECRET KEY
```bash
$~ python manage.py shell -c 'from django.core.management import utils; print(utils.get_random_secret_key())'
```
When we run above code, it will printed 50 characters random string. Please copy it into .env file as `SECREY_KEY`

- Great, you're ready!


## License
The code is available under the [MIT License](LICENSE.txt)