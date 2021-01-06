## Cara Install
Jalankan Perintah berikut untuk mendownload data dari repository github

```sh
$ git clone https://github.com/KarelNatalia/karelnatalia.git && cd karelnatalia
```

# Cara Menjalankan
### Cara Pertama

```sh
$ docker build -t 195410094_Riski ./
$ docker run -dit --name 195410094_Riski_runapp -p 8000:80 195410094_Riski
```

lalu buka browser dengan url `http://locahost:8000` untuk melihat hasil nya.

## Cara Kedua
```sh
$ docker run -dit --name 195410094_Riski_runapp -p 8000:80 123Riski/195410094_Riski:latest
```
lalu buka browser dengan url `http://locahost:8000` untuk melihat hasil nya.
# Teknologi-Cloud
# RiskiRifaldi-main
