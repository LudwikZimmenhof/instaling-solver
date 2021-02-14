## About the project
instaling-solver is a small project that automates the process of answering [instaling.pl](https://instaling.pl/) questions.


## dependencies
- [geckodriver-autoinstaller](https://pypi.org/project/geckodriver-autoinstaller/)
- [selenium](https://pypi.org/project/selenium/)
- [firefox](https://www.mozilla.org/firefox/new/)

## Installation
`pip install instaling-solver`

or

`git clone https://github.com/SmellyN3rd/instaling-solver`\
`cd instaling-solver`\
`python setup.py install`

## Usage
`python -m instaling-solver [options]`

## Options

option        | description
------------- | -------------
--user    -u        | specify the instaling account to use
--password    -p    | password for the given account
--sessions -s    | specify the amount of sessions to complete
--file    -f        | specify the file to which to read/write the known words
--headless    -h    | toogle headless mode (without browser gui)
--config    -c    | dump all settings into a file which will be loaded automaticly in the future

# Showcase
<img src="https://media.giphy.com/media/njjiYq0zcxNpkfeV02/giphy.gif" >
