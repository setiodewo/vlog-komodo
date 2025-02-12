[![DevOps Komodo](https://img.youtube.com/vi/8Unym6iYkf8/0.jpg)](https://www.youtube.com/watch?v=8Unym6iYkf8)

# KOMODO

Referensi: https://komo.do
Instalasi: https://komo.do/docs/setup/mongo

Download docker-compose & env. Edit sesuaikan dengan kebutuhan:
```
wget -P komodo https://raw.githubusercontent.com/moghtech/komodo/main/compose/mongo.compose.yaml && \
  wget -P komodo https://raw.githubusercontent.com/moghtech/komodo/main/compose/compose.env
```


Jalankan:
```
docker compose -p komodo -f mongo.compose.yaml --env-file compose.env up -d
```

Untuk install node server:
```
curl -sSL https://raw.githubusercontent.com/moghtech/komodo/main/scripts/setup-periphery.py | sudo python3
```

## Xenara Cafe and Coworking Space
Ruko Citra Grand, Blok London C-08, Semarang, Indonesia
