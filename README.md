![image](https://github.com/user-attachments/assets/4dda65e6-db81-4391-be7f-eeb96674fa8e)


## Implement GIT and Explaination

 ## Initializing a Repository

1.**Buat Direktori File**
   Langkah pertama anda harus memastikan sudah membuat folder.
   ```
   mkdir nama_folder //digunakan jika anda belum membuat folder yang akan dipakai
   cd nama_folder  // untuk mengakses folder yang kamu buat
   ```
2.**Inisialisasi Repository Git**
    Jalankan perintah berikut untuk menginisialisasi repository Git di folder tersebut:
    
    git init 
     
3.**Menambahkan File**
   Jika anda ingin menambahkan file 
   ```
   git add <nama_file>
   ```
  contoh file yang dibuat bernama Tryrepository.js
  
   ```
   git add Tryrepository.js
   ```

   untuk menambahkan semua perubahan dalam direktori kerja saat ini ke staging area sebelum melakukan commit,
   anda bisa menjalankan 

   ```
   git add .
   ```

  

4.**Cek Status Repository**
  ```
  git status
  ```

  perintah git status digunakan untuk menampilkan status dari repositori Git yang sedang aktif. Dengan perintah ini, kamu bisa melihat:
  
      1.Perubahan pada file – Apakah ada file yang dimodifikasi, baru ditambahkan, atau dihapus.
      2.Status staging area – Apakah ada file yang sudah masuk ke staging area (siap untuk di-commit) atau masih dalam working directory.
      3.Branch saat ini – Menampilkan cabang (branch) mana yang sedang aktif.
      4.Perbedaan dengan remote repository – Apakah ada commit yang belum di-push atau perlu di-pull dari remote repository.


5.**Lakukan Commit Pertama Simpan perubahan dengan membuat commit pertama**
  ```
  git commit -m "Feat : Inisialisai commit!"
  ```  
    
6.**Hubungkan menghubungkan repositori lokal Anda dengan repositori jarak jauh (remote repository) yang biasanya berada di server seperti GitHub
lalu copy addres repository anda yang sudah dibuat**

```
git remote add origin https://github.com/GhaziAlGhifariit/WCD_Task-2_Understanding-Git.git
```
7.**Push the local changes to GitHub**

```
git push -u origin main
```


    
## Making Changes and Pushing to GitHub
1.**Lakukan perubahan pada file**

   ```
   console.log("Try Repository");
   console.log("Hello, World!");
   ```

   ```
   console.log("Mencoba repository");
   console.log("Halo,dunia!");
   ```

2.**lalu jalankan perintah**
   
   ```
   git add.
   ```

3.**Lakukan commit ulang file yang telah dirubah**
      Dengan menjalankan perintah

      
   git commit - m "Feature : transalte bahasa"
      

   <img width="579" alt="image" src="https://github.com/user-attachments/assets/48f81528-7dea-4aae-857c-3ba1a7ccf101" />

4.**Push perubahan ke Github**
   ```     
   git push origin main
   ```   

## Working with Branches and Pushing to GitHub
1. **Buat Branch baru yang akan digunakan**
    dengan menjalankan perintah :
```
git checkout -b nama-branch-baru
```

   contoh :

```
git checkout -b feature-baru 
```
![Screenshot 2025-03-16 092914](https://github.com/user-attachments/assets/45180c22-055a-4eb3-9749-fdbbf662a9ec)



    

2.**Lakukan perubahan pada file**

```
console.log("Mencoba membuat branch baru");//output baru untuk branch baru
console.log("Halo,bandung!"); // output baru untuk branch baru
```

3.**Cek kembali status**
       
```
git status
```

   ![Screenshot 2025-03-16 092914](https://github.com/user-attachments/assets/88e7b0e4-7fe4-493b-8967-6c8733cd13b9)
   
4.**Tambahkan File ke Staging Area**
 
   ```
   git add .
   ```
5.**Lakukan Commit ulang untuk branch baru**

   ```
   git commit -m "feature:fitur baru"
   ```
6.**Push Branch ke GitHub**

   ```
   git push origin feature-baru
   ```
<img width="566" alt="image" src="https://github.com/user-attachments/assets/5226e526-cd62-4255-bbce-c535d8239d9f" />

## Creating a Pull Request, Reviewing Code, and Merging Changes
**1.Buat Pull Request (PR)**
Setelah melakukan git push pada branch baru, ikuti langkah berikut untuk membuat Pull Request:

Buka repository Anda di GitHub.

Klik tab "Pull Requests" di bagian atas halaman.

Klik tombol hijau "New pull request".

Pada bagian "base", pilih branch utama (misalnya main).

Pada bagian "compare", pilih branch yang berisi perubahan Anda (misalnya feature/add-login).

Klik tombol "Create pull request".

Beri judul yang deskriptif dan tambahkan penjelasan singkat tentang perubahan yang Anda lakukan.

Klik tombol "Create pull request" untuk mengajukan PR.

**2.Review Kode**
Jika Anda atau rekan tim Anda ingin meninjau kode sebelum menggabungkannya:

✅ Klik pada file yang mengalami perubahan.

✅ Berikan komentar pada baris kode jika diperlukan.

✅ Pastikan kode sesuai standar dan tidak ada bug yang mencolok.

**3.Merge Perubahan ke Branch Utama**
Setelah kode direview dan disetujui, Anda bisa menggabungkan perubahan ke branch utama:

 1. Klik tombol hijau "Merge pull request".
 2. Klik tombol "Confirm merge" untuk menyelesaikan proses.
 3. Setelah merge selesai, Anda bisa menghapus branch yang sudah digabung dengan klik tombol "Delete branch" (opsional untuk menjaga repository tetap rapi).

**4. Sinkronisasi Repository Lokal (Opsional)**
Setelah merge dilakukan di GitHub, sinkronkan branch utama Anda dengan perintah berikut:

```
git checkout main
git pull origin main
```
   





   
     



  

