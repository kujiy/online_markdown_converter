# Online Text to Markdown Converter

## Demo
https://online-markdown-converter.herokuapp.com/

Paste you text into the top left box and click `Markdown with quotes`.  
If you don't need auto reset textarea, click the `off` button on the right top position of the screen.

## Screen 
![](https://raw.githubusercontent.com/kujiy/online_markdown_converter/master/0421-01.png)

## Features
- Paste your email to your groupware with quoted marks of markdown.
- Add line breaks for markdown automatically.
- Insert your program with program-language quoting.
- Including some convinient features

## Useful features only for multi-byte language users
- Embolden or italicize one-byte strings automaticaly
- Convert typical symbols(e.g. ■□○●・) to markdown symbols

### How to push to heroku
Thanks [dzuelke/heroku-multipack-nodejs-php-example](https://github.com/dzuelke/heroku-multipack-nodejs-php-example) for deploying on heroku php app with bower.
```
$ heroku create your-app-name
$ heroku buildpacks:add heroku/nodejs 
$ heroku buildpacks:add heroku/php
$ git push heroku master
```

## Welcome
I made this tool only for Gitlab. Feel free to ask anything.
