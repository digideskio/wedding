web: ./setup_caddy.sh && ./caddy -conf="HerokuCaddyfile"
python: gunicorn -b 0.0.0.0:8000 wedding_api.wsgi --pythonpath ./api/wedding_api --log-file - --log-level debug --access-logfile -

