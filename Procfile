web: PORT=4000 npm start --prefix client --disableHostCheck true
api: gunicorn -b 127.0.0.1:5555 --chdir ./server app:app