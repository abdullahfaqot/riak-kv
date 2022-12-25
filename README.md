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

# Screenshot
- localhost:8098/admin/
![localhost8098-admin-1](https://user-images.githubusercontent.com/85489329/209462457-c2ee8f17-c1a8-4877-b777-acd75fe895fb.jpg)

![localhost8098-admin-2](https://user-images.githubusercontent.com/85489329/209462475-2d284053-fb0a-49d9-ad3d-24b1ed81d18c.jpg)

![localhost8098-admin-3](https://user-images.githubusercontent.com/85489329/209462488-0a6d981e-f9e0-408c-9496-21452dd79d52.jpg)

- Contact App
![contact-app](https://user-images.githubusercontent.com/85489329/209462492-35530845-60c5-4507-8919-d47df8409516.jpg)

- Add
![contact-app-add](https://user-images.githubusercontent.com/85489329/209462512-93597be9-01d1-4566-87c7-a76a8bd8dfe0.jpg)

- Update/edit
![contact-app-update](https://user-images.githubusercontent.com/85489329/209462522-c035a6d2-e962-4f43-9d9c-c41dd05cec95.jpg)



