# white-pro
Remember to fork and to star 🌟 
envVars:
  - key: NODE_ENV
    value: staging

  - key: APP_SECRET
    generateValue: true

  - key: DB_URL
    fromDatabase:
      name: mydb
      property: connectionString

  - key: MINIO_ROOT_PASSWORD
    fromService:
      type: pserv
      name: minio
      envVarKey: MINIO_ROOT_PASSWORD

  - key: STRIPE_API_KEY
    sync: false

  - fromGroup: my-env-group
https://whatsapp.com/channel/0029Vb6IcZm9sBIFqpWHKE1Q
