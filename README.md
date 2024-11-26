## BUAT REPO BARU BIAR GAMPANG AJA MAS HEHE

Nama : Mochamad Gilang Fadil Hakim 

NIM  : H1D022082 

Shift : B

![image](https://github.com/user-attachments/assets/c68fb02b-582d-4e54-848e-f69f27898e14)

1. Create 
![image](https://github.com/user-attachments/assets/aa59f31c-230b-4470-a379-1f301397c4d6)

Gambar tersebut menunjukkan proses pembuatan ketika pengguna menambahkan todo baru melalui tombol tambah di pojok kanan bawah aplikasi. Setelah tombol ditekan, modal input muncul, memungkinkan pengguna memasukkan judul dan deskripsi. Data yang dimasukkan akan dikirim ke fungsi handleSubmit, yang memanggil firestoreService.addTodo untuk menyimpan data ke Firestore. Jika berhasil, daftar todo diperbarui melalui fungsi loadTodos.

2. Update
![Screenshot 2024-11-26 212559](https://github.com/user-attachments/assets/4efa7aa1-0eff-48e9-a4f0-7af849203c4f)

Kemudian terdapat juga untuk proses Update, pengguna dapat mengubah data atau status todo. Ketika tombol edit ditekan, fungsi handleEdit dipanggil untuk membuka modal input dengan data yang sudah ada. Setelah perubahan disimpan, fungsi handleSubmit memanggil firestoreService.updateTodo untuk memperbarui data di Firestore. Selain itu, pengguna juga dapat mengubah status tugas (aktif atau selesai) melalui tombol status, yang memanggil fungsi handleStatus untuk memperbarui status tugas di Firestore.

3. Delete 
![image](https://github.com/user-attachments/assets/2c8b219c-5547-4282-ab36-1d817d10d93f)

Gambar ini menunjukkan proses penghapusan tugas, di mana pengguna dapat menghapus todo. Ketika tombol hapus ditekan, fungsi handleDelete dijalankan untuk menghapus data todo melalui firestoreService.deleteTodo. Setelah selesai, daftar tugas diperbarui dengan memanggil fungsi loadTodos. Proses ini dilengkapi dengan notifikasi (toast) sebagai umpan balik kepada pengguna, memberikan pengalaman yang informatif dan responsif. Selain itu, proses penyelesaian todo juga ditampilkan, di mana data diperbarui, dan tugas secara otomatis berpindah dari activeTodos ke completedTodos.
