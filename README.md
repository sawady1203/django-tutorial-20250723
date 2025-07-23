# これは何
Django Tutorial をやっていくリポジトリです。

```sh
$ uv init .
$ uv pip install -U pip
$ uv add django

# djangoプロジェクトの作成
$ uv run django-admin startproject mysite . 

# 開発用サーバーの起動
$ uv run python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
July 23, 2025 - 04:24:29
Django version 5.2.4, using settings 'mysite.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.

WARNING: This is a development server. Do not use it in a production setting. Use a production WSGI or ASGI server instead.
For more information on production servers see: https://docs.djangoproject.com/en/5.2/howto/deployment/
```