# blog-asgi
Django Blog App in ASGI

## Running Django in Uvicorn
```angular2html
gunicorn blog.asgi:application -k uvicorn.workers.UvicornWorker
```