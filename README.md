# 📄 Tugas Pertemuan 3 - Formulir Interaktif dengan Streamlit

## 🎯 Deskripsi Tugas
Tugas ini bertujuan untuk melatih penggunaan **widget input interaktif di Streamlit** dalam bentuk halaman formulir. Mahasiswa diminta untuk merancang dan mengimplementasikan halaman web yang memungkinkan pengguna untuk:

- Mengisi nama tim (text input)
- Menentukan jumlah anggota (numeric input)
- Memilih tanggal pendaftaran (date input)
- Memilih jam presentasi (time input)
- Memilih kategori lomba (selection input)
- Mengirim formulir melalui tombol (button)

Semua input akan ditampilkan kembali secara terstruktur setelah pengguna menekan tombol **"Daftar"**.

---

## 🛠️ Teknologi yang Digunakan
- [Streamlit](https://streamlit.io/) untuk pembuatan antarmuka aplikasi web berbasis Python
- Python `datetime` untuk menangani waktu dan tanggal

---

## 🧾 Struktur Formulir
Formulir ini terdiri dari elemen berikut:

| Elemen             | Tipe Widget           | Deskripsi                                      |
|--------------------|------------------------|------------------------------------------------|
| Nama Tim           | `st.text_input`        | Input nama tim peserta                        |
| Jumlah Anggota     | `st.number_input`      | Input angka jumlah anggota tim                |
| Tanggal Daftar     | `st.date_input`        | Memilih tanggal pendaftaran                   |
| Jam Presentasi     | `st.time_input`        | Memilih waktu presentasi yang diinginkan      |
| Kategori Lomba     | `st.selectbox`         | Memilih salah satu kategori lomba             |
| Tombol Daftar      | `st.form_submit_button`| Mengirim formulir                             |

---

## ✅ Output Setelah Submit
Jika pengguna menekan tombol **"Daftar"**, maka aplikasi akan:
- Menampilkan notifikasi bahwa pendaftaran berhasil
- Menampilkan kembali semua informasi yang telah diisi oleh pengguna

---

## 📸 Cuplikan 

```markdown
#Berikut adalah halaman Home untuk aplikasi ini:
![image] (https://github.com/user-attachments/assets/559ebc5a-9142-4671-9072-f5dad7defb14)

#Contoh Pertemuan 3:
![image](https://github.com/user-attachments/assets/b60442fa-1368-4a4c-a76d-7e41180184e1)
![image](https://github.com/user-attachments/assets/0bf4661a-7003-4768-830f-257cad324616)

#Latihan Pertemuan 3:
![image](https://github.com/user-attachments/assets/70bc7fc2-aab1-4f69-a28a-1fa6f151b719)

#Tugas Pertemuan 3:
![image](https://github.com/user-attachments/assets/299371d3-6465-4838-b981-ea84ec04b8c1)
Hasil Outputnya :
![image](https://github.com/user-attachments/assets/2885d2fe-d3fa-4a6e-81be-8c8746598326)




