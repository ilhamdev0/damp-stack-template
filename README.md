# Docker+Apache+MYSQL+PHP Local Development Template

### Warning!
Template ini hanya digunakan untuk kebutuhan development lokal bukan untuk production

## Requirement
- make

## Cara Install
### Otomatis

1. Clone repo
2. Masuk ke dalam folder yang telah di clone lalu jalankan command

```
make generate
```
3. Tunggu sampai selesai
4. Untuk mengetahui command lainnya ketik

```
make help
```

### Manual
1. Clone repo
2. Masuk ke dalam folder yang telah di clone lalu buat folder bernama `source` dan `log`
3. Copy file `.env.base` dengan nama `.env`
4. Edit file `.env` ganti nilai UID dengan hasil dari command

```
id -u
```

5. Modifikasi file lainnya sesuai kebutuhan
6. Build seluruh docker container

## Cara Pakai

letakkan project anda dalam folder `source`