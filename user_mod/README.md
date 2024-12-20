## 1. User Management

Pada bagian ini, saya mempelajari cara menggunakan Ansible untuk mengelola pengguna di sistem. Ini mencakup pembuatan, penghapusan, dan modifikasi pengguna serta pengaturan hak akses.


## Create User

Playbook `create_user2.yml` digunakan untuk membuat pengguna baru di sistem.

- **File**: [create_user2.yml](create_user2.yml)
- **Deskripsi**: Membuat pengguna baru dengan parameter yang dapat disesuaikan seperti nama pengguna dan grup.

## Reset Password

Playbook `reset_passwd.yml` digunakan untuk mereset kata sandi pengguna.

- **File**: [reset_passwd.yml](reset_passwd.yml)
- **Deskripsi**: Mereset kata sandi pengguna yang ada dengan kata sandi baru yang ditentukan.

## Create User with Expired date

Playbook `create_expires2.yml` digunakan untuk membuat pengguna baru dengan masa aktif tertentu.

![image](https://github.com/user-attachments/assets/0bf4aba8-a584-4665-b47f-fba5cdb1eea3)

- **File**: [create_expires2.yml](%create_expires2.yml)
- **Deskripsi**: Membuat pengguna baru dengan tanggal kedaluwarsa yang ditentukan, setelah itu akun akan dinonaktifkan.

## Extend User Expired

![image](https://github.com/user-attachments/assets/e5f4d0c5-db4a-404c-8012-1d06ce735a0c)

Playbook `extend_user2.yml` digunakan untuk memperpanjang masa aktif pengguna yang sudah ada.

- **File**: [extend_user2.yml](%extend_user2.yml)
- **Deskripsi**: Memperpanjang masa aktif pengguna dengan menyesuaikan tanggal kedaluwarsa.
