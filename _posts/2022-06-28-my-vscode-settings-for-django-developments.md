---
title: My VSCode settings for Django Developments
layout: post
date: '2022-06-28 09:04:24'
categories:
- vscode
---

Copy kode dibawah ke pengaturan VSCode per project Django.

Contoh: `myproject > .vscode/settings.json`

{% highlight json %}

{
    "python.defaultInterpreterPath": "venv/bin/python3",
    "files.associations": {
        "**/*.html": "html",
        "**/templates/**/*.html": "django-html",
        "**/templates/**/*": "django-txt",
        "**/requirements{/**,*}.{txt,in}": "pip-requirements"
    },
    "emmet.includeLanguages": {
        "django-html": "html"
    },
    "python.terminal.activateEnvironment": true,
    "python.linting.flake8Args": ["--max-line-length=120", "--ignore=E501,W503,F601"],
    "python.linting.pylintEnabled": false,
    "python.linting.flake8Enabled": true,
    "python.linting.enabled": true,
    "python.formatting.provider": "black",
    "editor.formatOnSave": true,
    "python.formatting.blackArgs": [
        "--line-length",
        "120"
    ],
    "python.testing.unittestEnabled": false
}

{% endhighlight %}
