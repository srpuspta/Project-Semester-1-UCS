# Project Semester I UCS

**Nama =** "Sera Puspita Sari"

**NIM =** "552012610011"

**Prodi =** "Teknik Informatika"

**Harapan =** "Harapan saya kedepannya yaitu saya ingin mempelajari dan dapat mampu membuat sebuah website yang sederhana dahulu, dengan isi websitenya berupa profil perusahaan (company profile). "

**Langkah_Langkah =**
  - Merancang konsep awal misal : apa aja yang ada diwebsitenya nanti.
  - Menentukan konsep tampilannya bagaimana.
  - Menyusun kode c++ atau menulis kode programnya untuk menghasilkan file HTML.
  - Menjalankan programnya C++ apakah sudah benar dan juga untuk mengolah input.
  - Memastikan file index.html berhasil dibuat.
  - Melakukan testing dengan cara membuka dibrowser chrome/edge.
  - Mengunggah file proyek ke GitHub untuk dijadikan portofolio.
___

### Kode Program (source code)

<details>
<summary><b>▶ Klik di sini untuk melihat Kode Program C++ (main.cpp)</b></summary>
    '''cpp
    #include <iostream>

    using namespace std;
    int main () {
        string Nama = "Sera Puspita Sari";
        string NIM = "552012610011";
        string Prodi = "Teknik Informatika";
        string Harapan = "Harapan saya kedepannya yaitu saya ingin mempelajari dan dapat mampu membuat sebuah website yang sederhana dahulu, dengan isi websitenya berupa profil perusahaan (company profile). ";
        string Langkah_Langkah =
                "- Merancang konsep awal misal : apa aja yang ada diwebsitenya nanti.\n"
                "- Menentukan konsep tampilannya bagaimana.\n"
                "- Menyusun kode c++ atau menulis kode programnya untuk menghasilkan file HTML.\n"
                "- Menjalankan programnya C++ apakah sudah benar dan juga untuk mengolah input.\n "
                "- Memastikan file index.html berhasil dibuat.\n"
                "- Melakukan testing dengan cara membuka dibrowser chrome/edge.\n"
                "- Mengunggah file proyek ke GitHub untuk dijadikan portofolio.\n";


        cout << "===== PROJECT SEMESTER 1 PDK =====" << endl;
        cout << "Nama                          : " << Nama << endl;
        cout << "NIM                           : " << NIM << endl;
        cout << "Deskripsi Project (Harapan)   : " << Harapan << endl << endl;
        cout << "Langkah-Langkah               :\n " << Langkah_Langkah << endl << endl;
        cout << "Semangat Semoga Bisa Menjalankan Targetnya";

        return 0;
    }

