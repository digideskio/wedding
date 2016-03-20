web: ./setup_caddy.sh && ./caddy -conf="HerokuCaddyfile"
python: gunicorn -b 0.0.0.0:8000 api/wedding_api/wsgi.py --log-file -
