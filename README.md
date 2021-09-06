# Fadhil Zuhairsyah 191402138
<br>
Tampilan Depan :
![image](https://user-images.githubusercontent.com/66856996/131910375-caf2bc2c-0b25-4078-b7c5-43d2343d6fc1.png) 
<br>
<br>
langkah :
1. Install docker
2. Container Registry, daftar ke dockerhub agar bisa memakai image yg sudah ada disana ![image](https://user-images.githubusercontent.com/66856996/132238996-24805853-65f8-47bc-98fe-0172b217c262.png)

3. Buat Images, saya pakai apl golang v.1.11.4 untuk menampilkan "hello padel" berupa website
4. Kemudian buat Dockerfile, letakkan di dalam satu folder bersama main.go yaitu folder app. Isi dari Dockerfile nya![image](https://user-images.githubusercontent.com/66856996/132239270-5a50d98a-df3d-43b4-9630-6ad38fc49c63.png)
<br>
FROM > kita buat image dari image yg sudah ada
<br>
COPY > copy semua file yg dibutuhkan
<br>
CMD > kita beritahu ke image bagaimana cara nge run aplikasi kita
<br>
5. Kemudian build image nya dari Dockerfile tadi  ![image](https://user-images.githubusercontent.com/66856996/132240033-9af2fc8f-b3f8-4ed1-8042-e6e386cc0842.png)
<br>
6. Kemudian buat container dari image yang dibuat dengan port 8080:8080  ![image](https://user-images.githubusercontent.com/66856996/132240124-a3adbbd3-6bb3-49e6-92be-8e9d1588e578.png)
<br>
7. Lalu jalankan > Docker container start
<br>
8. Buka di browser > localhost:8080
