# django3-with-examples-mysite

Learning repo to implement example codes from "Django 3 with examples", by Antonio Melé. This repo implements chapters 1, 2 and 3.

## Running project

After cloning the repo, run this inside the project folder:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

**OBS:** You need to have PostgreSQL installed to run this project.

## Environment variables

Environment configurations are customized and are not presented by the book.

Environment file (`.env`) template:

```
ENVIRONMENT="development"
DATABASE_URL="postgres://postgres:postgres@localhost:5432/mysite"
SECRET_KEY="django-insecure-*nzi603mpw3_k=-$*txx9izuos)oo+@xpleuh%b)zx5^d7ox1)"
EMAIL_HOST_USER='"
EMAIL_HOST_PASSWORD=""
```

The `.env` file must be placed on project's root folder.
