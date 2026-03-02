# Remote Instance with SSH Putty

1. Pastikan sudah install Putty

![alt text](image-3.png)

2. Konversi file Public key dari .pem menjadi .ppk di putty
- buka puttyGen
- load File .pem
- Save as .ppk

![alt text](image-4.png)

3. Set Up Putty untuk Remote SSH
- buka apps Putty
- Isi IP Public sesuai instance
- Isi Nama session agar saat connect lagi tinggal load saja
- load file .ppk (Klik SSH-> Auth -> Credentials ->load file .ppk)
- kembali ke session klik save
- klik open
- masukan username ssesuai instance

![alt text](image-5.png)
![alt text](image-6.png)

4. "sudo apt-get update" (update OS) lanjut "sudo apt-get upgrade"

![alt text](image-7.png)

5. pembuktian remote SSH secara visual
- Copy public IP Address instance paste ke browser

![alt text](image-8.png)

- install web server seperti Apache/Nginx
- sudo apt install apache2
- Reload Browser

![alt text](image-9.png)

6. Matikan Instance agar tidak kena tagihan
- sudo shutdown now 

![alt text](image-10.png)