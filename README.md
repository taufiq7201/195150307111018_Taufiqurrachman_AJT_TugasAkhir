Taufiqurrachman

195150307111018

Arsitektur Jaringan Terkini


# Tugas 1

Instance
Spesifikasi:
-Nama : Tugas Akhir
-OS Image : Ubuntu Server 22.04 LTS 64-bit
-Instance type : t2.medium
-Keypair : vockey
-Edit network settings : allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081
-Konfigurasi penyimpanan : 30 GiB, gp3

![ajt1](https://user-images.githubusercontent.com/57854253/172640680-a804b284-ae64-493d-93ba-54a18f84d2da.png)
![ajt2](https://user-images.githubusercontent.com/57854253/172640715-34c724c9-4773-4354-9675-1cf243192d32.png)
![ajt3](https://user-images.githubusercontent.com/57854253/172640725-dcf4a86d-6265-47ce-8e76-b8b2bbe5d0e5.png)
![ajt4](https://user-images.githubusercontent.com/57854253/172640734-240f376d-20a6-4166-93b7-de004a8de16a.png)
![ajt5](https://user-images.githubusercontent.com/57854253/172640899-9e954ee2-30c1-46f3-917c-7088c8dd3684.png)

Tampilan Saat Masuk Instance

![ajt6](https://user-images.githubusercontent.com/57854253/172640980-f8668f59-6710-405c-a4d7-f90880369c1e.png)

Upgrade Ubuntu

![ajt7](https://user-images.githubusercontent.com/57854253/172641169-3f811928-20c3-4ab9-bed7-0db7a35e04e1.png)

Instalasi Mininet Ryu dll

![ajt8](https://user-images.githubusercontent.com/57854253/172641100-b16803d6-7659-4403-ac2a-faf98e53f8aa.png)

# Tugas 2
Percobaan topology mininet 3 switch (loop) dengan 6 host

![image](https://user-images.githubusercontent.com/57854253/172644740-09853674-bbc3-4723-84ee-9cd9b374ae2d.png)

# Tugas 3
Tab Vocareum Labs untuk Mininet 

![image](https://user-images.githubusercontent.com/57854253/172650407-d98ec970-4808-4d8c-bcdc-986f38dc3286.png)

Tab Vocareum Labs untuk Ryu Manager 

![image](https://user-images.githubusercontent.com/57854253/172650507-e976ee30-cb16-4515-b19f-15520a69d4db.png)
![image](https://user-images.githubusercontent.com/57854253/172650537-542bb425-7d3e-4b8c-90d8-9bce24e05a63.png)


# Tugas 4

Menggunakan gitclone untuk menyalin repository dari https://github.com/abazh/learn_sdn.git pada terminal satu dan mengganti direktori ke learn_sdn/SPF pada terminal 1 

![image](https://user-images.githubusercontent.com/57854253/172647748-4c4dd487-dced-4a8e-a10b-b4cab86536fd.png)

Menulis kode ‘ryu-manager --observe-links dijkstra_Ryu_controller.py’ pada terminal 1 Screenshot tampilan terminal 1 : 

![image](https://user-images.githubusercontent.com/57854253/172647791-6b8da09a-ebf0-4ca7-b267-d14f27f97ed4.png)
![image](https://user-images.githubusercontent.com/57854253/172647829-bab7ee4e-0af8-4625-919c-c83fc2aa8c0c.png)

Mengganti direktori ke learn_sdn/SPF seperti pada terminal 1 dan menuliskan perintah ‘sudo python3 topo-spf_lab.py’ pada terminal 2 Screenshot tampilan terminal 2 : 

![image](https://user-images.githubusercontent.com/57854253/172647886-6ed354fc-dd11-4b0e-8c97-cb06376d7879.png)

Mengecek konektivitas dengan beberapa command 
 
a.	h1 ping -c 4 h4 
Tampilan terminal 1 : 

![image](https://user-images.githubusercontent.com/57854253/172647983-b2c7e711-3d12-4541-be9b-d7d2c611eec4.png)

Tampilan terminal 2 : 

![image](https://user-images.githubusercontent.com/57854253/172648045-25bacae2-7fb1-485c-9f9b-63d9d3542e42.png)

b.	h5 ping -c 4 h6 
Tampilan terminal 1 : 

![image](https://user-images.githubusercontent.com/57854253/172648115-11b46882-0ad2-42dc-83f5-f1d9b572e3f0.png)

Tampilan terminal 2 : 

![image](https://user-images.githubusercontent.com/57854253/172648149-4099abf9-fd41-4ceb-9316-3627c9000efe.png)


