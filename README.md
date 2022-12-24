# Riak-KV-Kelompok-3-IF-A
Implementasi CRUD dengan menggunakan DBMS Riak-KV dan NodeJS
Untuk memenuhi tugas akhir mata kuliah Manajemen Basis Data dan Praktikum Manajemen Basis Data

Anggota Kelompok 3:
- Abdullah - 1207050001
- Arham Syuhada - 1207050017
- Ayuni Tia Sari - 1207050020

Link Youtube :

# Langkah Instalasi Riak-KV Menggunakan Docker
1. Mendownload Docker
2. Mendownload image basho/riak-kv di hub.docker.com
```
docker image pull basho/riak-kv -d
```
3. Membuat container dari image basho/riak-kv dengan nama container dbriak
```
docker container create --name dbriak --publish 8087:8087 --publish 8098:8098 basho/riak-kv
```
4. Menjalankan container dbriak
```
docker container start dbriak
```
5. Mengecek koneksi pada port 8098
```
localhost:8098/admin
```
6. Mengkonfigurasi koneksi Riak-KV dengan NodeJS
7. Membuat CRUD
