# Samplebot
Config files for my GitHub profile.
VPS:

    sudo apt-get install heroku

    sudo pip install line-bot-sdk

    sudo pip install flask

    curl https://cli-assets.heroku.com/install... | sh

    git clone https://github.com/Aditmadzs/oalinebot

    EDIT TOKEN + SECRET DULU

    Buka folder git kalian

cd oalinebot

    Login Ke Heroku

heroku login

    Buat aplikasi di heroku

heroku apps:create nama

    Git Remote Ke Heroku

heroku git:remote nama

    Init ke git

git init

    Tambahkan git

git add .

    Lalu commit

git commit -m "Aditmadzs"

    Push ke heroku

git push heroku master

    Masukan Webhook URL, tambahkan /callback dibelakang link webhook URL

nama-aplikasi-di-heroku.herokuapp.com/callback

    Jalankan app.py

$ python3 app.py
