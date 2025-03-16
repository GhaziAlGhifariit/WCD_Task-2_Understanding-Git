attachments/assets/c94bc163-3fd2-4bfe-88ec-a3528097405b)
## Implement GIT and Explaination

1. **Initializing a Repository**

a.**Buat Direktori File**
   Langkah pertama anda harus memastikan sudah membuat folder.
   ```
   mkdir nama_folder //digunakan jika anda belum membuat folder yang akan dipakai
   cd nama_folder  // untuk mengakses folder yang kamu buat
   ```
b.**Inisialisasi Repository Git**
    Jalankan perintah berikut untuk menginisialisasi repository Git di folder tersebut:
    
     ```
     git init 
     ```
     
c. **Menambahkan File**
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

  

d.**Cek Status Repository**
  ```
  git status
  ```

  perintah git status digunakan untuk menampilkan status dari repositori Git yang sedang aktif. Dengan perintah ini, kamu bisa melihat:
  
      1.Perubahan pada file – Apakah ada file yang dimodifikasi, baru ditambahkan, atau dihapus.
      2.Status staging area – Apakah ada file yang sudah masuk ke staging area (siap untuk di-commit) atau masih dalam working directory.
      3.Branch saat ini – Menampilkan cabang (branch) mana yang sedang aktif.
      4.Perbedaan dengan remote repository – Apakah ada commit yang belum di-push atau perlu di-pull dari remote repository.


e.**Lakukan Commit Pertama Simpan perubahan dengan membuat commit pertama**
    ```
    git commit -m "Feat : Inisialisai commit!"
    ```

    
2. **Making Changes and Pushing to GitHub**

   a.Lakukan perubahan pada file

   ```
   console.log("Try Repository");
   console.log("Hello, World!");
   ```

   ```
   console.log("Mencoba repository");
   console.log("Halo,dunia!");
   ```

   ![Screenshot 2025-03-16 085731](https://github.com/user-attachments/assets/ea98c449-fa77-4d91-8581-d4b33f02eca6)

   b.lalu jalankan perintah
   
   ```
   git add.
   ```

   c. Lakukan commit ulang file yang telah dirubah
      dengan menjalankan perintah

      ```
      git commit - m "Feature : transalte bahasa"
      ```

   <img width="579" alt="image" src="https://github.com/user-attachments/assets/48f81528-7dea-4aae-857c-3ba1a7ccf101" />



   








  

