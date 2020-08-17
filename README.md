# news-crawler
news crawler

# install lib
pip install -r requirements.txt

# build
pyinstaller -w -F --add-data "templates:templates" --add-data "static:static" app.py
