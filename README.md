curl -i -X POST \
  'https://www.google-analytics.com/mp/collect?measurement_id=G-875FB98E54&api_secret=Y_ZO8f0TSLKk1VmfinpowQ' \
  -H 'Content-Type: application/json' \
  --data-raw '{
    "client_id": "1794853811.564448801",
    "events": [
      {
        "name": "login",
        "params": {
          "method": "email",
          "engagement_time_msec": 1
        }
      }
    ]
  }'