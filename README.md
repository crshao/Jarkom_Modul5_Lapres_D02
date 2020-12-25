# Jarkom_Modul5_Lapres_D02
## Laporan Resmi Praktikum Modul 5 Jaringan Komputer 2020
**Kelompok D02**

-Calvin Wijaya 05111840000086

-Alie Husaini R. 05111840000097

### Konfigurasi VLSM
![alt vlsm_topo](images/vlsm_topo.png)
![alt vlsm_tree](images/vlsm_tree.png)

##### 1. Mengkonfigurasi SURABAYA menggunakan iptables, namun bukan menggunakan MASQUERADE.
![alt img1](images/1.PNG)

##### 2. Mendrop semua akses SSH dari luar topologi pada server yang memiliki IP DMZ pada SURABAYA.
![alt img2](images/2.PNG)

##### 3. Membatasi DHCP dan DNS server dengan hanya boleh menerima 3 koneksi ICMP pada saat bersamaan.
![alt img3](images/3a.PNG)
![alt img3](images/3b.PNG)

##### 4. Akses dari subnet SIDOARJO hanya diperbolehkan pada pukul 07.00 - 17.00 pada hari Senin sampai Jumat.
##### 5. Akses dari subnet GRESIK hanya diperbolehkan pada pukul 17.00 hingga pukul 07.00 setiap harinya.
![alt img4](images/4.PNG)
![alt img45](images/4_5.PNG)
![alt img5](images/5.PNG)

##### 6. SURABAYA disetting sehingga setiap request dari client yang mengakses DNS Server akan didistribusikan secara bergantian pada PROBOLINGGO port 80 dan MADIUN port 80.
![alt img6](images/6.PNG)

##### 7. Semua paket didrop oleh firewall (dalam topologi) tercatat dalam log pada setiap UML yang memiliki aturan drop.
![alt img7](images/7.PNG)
![alt img7](images/7b.PNG)
