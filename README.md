# 3DPrint
Memahami secara menyeluruh alur manufaktur aditif, menghubungkan software desain dengan eksekusi di printer 3D.

# Alur Kerja 3D Printing (SolidWorks ke Mesin)
Repository ini mendokumentasikan keseluruhan proses pencetakan 3D (*3D Printing*), mulai dari tahap pemodelan 3D di komputer hingga proses manufaktur aditif menggunakan *printer* 3D. 
Proyek ini mendemonstrasikan pembuatan gantungan kunci nama kustom, dan sangat cocok bagi Anda yang sedang mempelajari fundamental CAD (*Computer-Aided Design*) dan CAM (*Computer-Aided Manufacturing*) untuk mesin cetak 3D.

## Tentang Proyek Ini
Mencetak objek 3D memerlukan jembatan komunikasi yang baik antara perangkat lunak desain dan bahasa mesin. Proyek ini membedah alur tersebut secara transparan, menunjukkan bagaimana desain mekanis yang solid dikonversi menjadi pergerakan mesin yang presisi lapis demi lapis.

## Alur Kerja (Workflow)

### 1. Desain CAD (SolidWorks)
Tahap pemodelan bentuk fisik menggunakan *software* SolidWorks:
* Pembuatan dasar (*base*) gantungan kunci.
* Penggunaan fitur teks yang dikombinasikan dengan perintah **Extrude** untuk menghasilkan huruf timbul.
* Pembuatan lubang presisi (*Hole/Cut-Extrude*) untuk ring gantungan.

### 2. Slicing CAM (Bambu Lab Studio / Flashprint)
Tahap persiapan manufaktur di mana model 3D diubah menjadi bahasa mesin:
* Penyesuaian orientasi dan penempatan objek (*Move*).
* Penyesuaian ukuran dimensi akhir (*Scaling*).
* Proses *Slicing* untuk menghasilkan *file* G-Code.

### 3. Eksekusi (*3D Printer*)
Tahap operasional perangkat keras di dunia nyata:
* Transfer *file* menggunakan kartu SD.
* Pemanasan awal (*pre-heating*) pada *nozzle* dan meja cetak (*bed*).
* Eksekusi pencetakan lapis demi lapis hingga objek terbentuk sempurna.

                                                  
