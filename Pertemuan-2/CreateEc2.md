# Membuat EC2 / Instance / VM

1. Pilih Menu All Services -> EC2

![alt text](image-11.png)

2. Di dalam Menu EC2 kita pilih instance

![alt text](image-12.png)

3. di dalam menu Instance pilih launch instance

![alt text](image-13.png)

4. Beri nama instance kita dengan format NIM_Server

![alt text](image-14.png)

5. Kita pilih OS Server untuk instance

![alt text](image-15.png)

6. Pilih resource instance T3.Micro (2VCPU, 1GB Memory)

![alt text](image-16.png)

7. Membuat Key Pair, Pilih new key pair, isi nama key, pilih RSA, format File .pem, create key pair

![alt text](image-17.png)

8. Setting Kebijakan keamanan / Security Group
   - Allow SSH -> Artinya membolehkan Remote SSH dari luar 
   - Allow HTTPS -> Artinya Instance bisa di akses dari protocol HTTPS
   - Allow HTTP -> Artinya instance bisa di akses dari protocol HTTP

![alt text](image-18.png)

9. selesai set-up pilih launch instance

![alt text](image-19.png)

10. pastikan launch instance sukses

![alt text](image-20.png)