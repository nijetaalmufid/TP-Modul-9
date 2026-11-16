<img width="1280" height="800" alt="Screenshot 2026-11-16 190452" src="https://github.com/user-attachments/assets/168bbb7a-e2ef-4630-a32c-096a2b175df4" />
<img width="1280" height="800" alt="Screenshot 2026-11-16 190440" src="https://github.com/user-attachments/assets/9ed15d43-daee-4a2e-9603-ca9275170e67" />

Kodingan query
CREATE DATABASE modul19;
USE modul19;

CREATE TABLE data_diri (
  id INT AUTO_INCREMENT PRIMARY KEY,
  nama_lengkap VARCHAR(100) NOT NULL,
  tanggal_lahir DATE NOT NULL,
  hobi VARCHAR(255)
);
