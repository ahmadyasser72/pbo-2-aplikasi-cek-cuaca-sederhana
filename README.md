# Tugas 6 - Aplikasi Cek Cuaca Sederhana ([screenshot](#screenshot))

Aplikasi ini memungkinkan pengguna untuk memeriksa cuaca saat ini di kota yang dipilih menggunakan API dari OpenWeatherMap. Fitur utama dari aplikasi ini mencakup:

- Pencarian cuaca berdasarkan nama kota.
- Menyimpan dan menampilkan kota favorit.
- Mengimpor dan mengekspor data cuaca dalam format JSON.
- Menampilkan ikon cuaca sesuai dengan kondisi cuaca terkini.

## Fitur

- **Cek Cuaca**: Pilih kota dari dropdown dan tekan tombol "Cek Cuaca" untuk melihat cuaca terkini.
- **Kota Favorit**: Kota yang sering dicari bisa disimpan sebagai favorit.
- **Impor Data**: Impor data cuaca dari file JSON yang sudah ada.
- **Ekspor Data**: Ekspor data cuaca yang ada ke file JSON.
- **Tampilan Cuaca**: Menampilkan nama cuaca, deskripsi, dan ikon cuaca yang sesuai.

## Instalasi

1. Pastikan Anda memiliki **Java** versi 8 atau lebih tinggi yang terinstal.
2. Pastikan Anda memiliki **NetBeans IDE** atau IDE lain yang mendukung proyek Java Swing.
3. Masukkan **API Key** Anda dari [OpenWeatherMap](https://openweathermap.org/api) ke dalam variabel `apiKey` dalam kode.

## Penggunaan

1. Pilih kota yang ingin Anda cek cuacanya pada dropdown.
2. Klik tombol **Cek Cuaca** untuk mendapatkan cuaca terkini untuk kota tersebut.
3. Anda dapat menambahkan kota favorit dengan memilihnya dari dropdown dan menyimpannya untuk akses cepat di masa mendatang.
4. Untuk mengimpor atau mengekspor data, gunakan tombol **Import Data** dan **Export Data**.

## Dependencies

- **Moshi**: Digunakan untuk parsing JSON.
- **OkHttp**: Digunakan untuk melakukan permintaan HTTP ke API OpenWeatherMap.
- **Swing**: Digunakan untuk GUI.

## Detail tugas

1. Deskripsi Program:

   - Integrasi dengan API cuaca eksternal (misalnya OpenWeatherMap) untuk mendapatkan data cuaca secara real-time
   - Tampilkan data cuaca dalam bentuk gambar berdasarkan kondisi cuaca (cerah, berawan, hujan, dan sebagainya)

2. Komponen GUI: JFrame, JPanel, JLabel, JTextField, JButton, JComboBox

3. Logika Program: API eksternal, penampilan gambar

4. Events:

   - ActionListener untuk tombol Cek Cuaca
   - ItemListener pada JComboBox untuk memilih lokasi cuaca

5. Variasi:

   - Tambahkan kemampuan untuk menyimpan kota yang sering dicek ke dalam daftar lokasi favorit, sehingga dapat dipilih dengan cepat dari JComboBox
   - Sediakan tombol untuk menyimpan data dari tabel ke dalam file CSV atau teks agar data cuaca dapat diakses kembali
   - Tambahkan fitur untuk memuat data cuaca yang tersimpan dan menampilkannya di JTable.

## Screenshot

Nama : Ahmad Yasser

NPM  : 2210010525

Kelas: 5A REGULER BJB TI

1. Tampilan awal
![image](https://github.com/user-attachments/assets/135b6c83-dc2f-45ee-b0ab-f3f251b542ce)

2. Cek cuaca banjarbaru
![image](https://github.com/user-attachments/assets/d0059394-45a3-442b-86bf-8eea16892766)

3. Cek cuaca paris
![image](https://github.com/user-attachments/assets/8f2887bb-7a43-42f3-81e6-d0f6fbe8a519)

4. Cek cuaca dari memilih combobox banjarbaru
![image](https://github.com/user-attachments/assets/a26d61b2-d78a-4ab0-9fbb-465e96781db0)
![image](https://github.com/user-attachments/assets/fd6e2074-dcd5-423f-8a3c-f791e0acf844)

5. Export data ke file (json)
![image](https://github.com/user-attachments/assets/feb00efa-f91b-47fd-a4e7-a54b2daa7741)
![image](https://github.com/user-attachments/assets/220d2645-0eb6-4d68-b549-9ae8eab2a3cc)

6. Import data dari file (json)
![image](https://github.com/user-attachments/assets/e123e2f0-e96e-4f5c-9925-ae3edbfb58c6)
![image](https://github.com/user-attachments/assets/2c333f1b-a27d-4126-8dfb-6c2eaf04d5ab)
