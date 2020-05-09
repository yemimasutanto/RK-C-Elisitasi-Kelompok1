# RK-C-Kelompok1
Repo Tugas Rekayasa Kebutuhan Kelas C Kelompok 1 </br> </br>

Nama Anggota kelompok: 
* Yemima Sutanto (05111740000049) 
* Celia Chintara Yuwine (05111740000058) 
* Ayu Mutiara Sari (05111740000149) </br>
</br>
Topik yang digunakan: Sistem informasi Presensi Online (presensi.its.ac.id) </br>
Teknik Prioritisasi : Analytical Hierarchy Process (AHP) </br>
Stakeholder : </br>
- Kelompok 3 : Isnaini Nurul K (05111740000010), Rizky Asei Narni (05111740000014), Zahrul Zizki Dinanto (05111740000168)</br>
- Kelompok 5: Patrick Sungkharisma (05111740000041), Elkana Hans Widersen (05111740000127), I Gede Agung K. P (05111740000135)</br>
- Kelompok 6: Kholishotul Amalia (05111740000030), Najatul Muslim Dinatra(05111740000079), Meila Kamilia (05111740000189)</br>

## Perhitungan Prioritas dengan Analytical Hierarchy Process (AHP)
Analytical Hierarchy Process (AHP) adalah suatu metode pengambilan keputusan dengan melakukan perbandingan berpasangan antara kriteria pilihan dan juga perbandingan berpasangan antara pilihan yang ada.
</br>

Pada studi kasus Sistem Informasi Presensi Online ITS, dari tugas elisitasi kebutuhan sebelumnya, telah kami dapatkan 19 kebutuhan pengguna dari Sistem Informasi Presensi Online ITS.
</br>

Kami menggunakan variable Value dan Cost untuk mengukur tingkat prioritas dari kebutuhan pengguna Sistem Informasi Presensi Online ITS tersebut.
</br> 

Perhitungan bobot Value kami lakukan dengan membuat kuesioner berisikan 19 kebutuhan pengguna, yang diberikan kepada client untuk dijawab dengan skala likert 1(*very low*)-5(*very high*).
</br>

Perhitungan bobot Cost kami lakukan dengan membuat kuesioner berisikan 19 kebutuhan pengguna, yang diberikan kepada client untuk dijawab dengan skala likert 1(*very low*)-5(*very high*) 
</br>

Hasil dari pengumpulan kuisioner dapat diakses pada file [Kuisioner Pengukuran Tingkat Value (Responses).xlsx](https://github.com/yemimasutanto/RK-C-Kelompok1/blob/master/Penugasan%20Prioritisasi%20(FP)/Kuisioner%20Pengukuran%20Tingkat%20Value%20(Responses).xlsx) dan file [Mengukur Cost (Responses).xlsx](https://github.com/yemimasutanto/RK-C-Kelompok1/blob/master/Penugasan%20Prioritisasi%20(FP)/Mengukur%20Cost%20(Responses).xlsx)

Setelah itu melakukan perhitungan dengan teknik AHP. Data hasil kuisioner diolah dengan mencari nilai dan skala dari tiap-tiap kebutuhan, setelah itu membuat matrix perbandingan (*n x n*) dari kebutuhan dengan skalanya yang digunakan sebagai perhitungan elemen matrix. Setelah itu melakukan estimasi eigenvalue, dan didapatkan persentase dari tiap-tiap kebutuhan untuk cost dan valuenya. langkah selanjutnya adalah membuat kesepakatan antara developer dan stakeholder untuk menentukan nilai *high margin* dan *low margin* dengan mempertimbangan ketersediaan *resource*. Diperoleh ratio value/cost >2.0 (high) dan <0.5 (low), didapatkan tingkat prioritas dari masing-masing  kebutuhan seperti yang tertera di file [AHP Cost & Value.xlsx](https://github.com/yemimasutanto/RK-C-Kelompok1/blob/master/Penugasan%20Prioritisasi%20(FP)/AHP%20Cost%20%26%20Value.xlsx)
</br>

Selanjutnya adalah membuat Dokumen Spesifikasi Kebutuhan Perangkat Lunak (SKPL). Dokumen ini digunakan sebagai panduan bagi pengembang dan stakeholder selama dalam pengembangan perangkat lunak dibangun. Di dalamnya berisi hasil kebutuhan yang telah diseleksi oleh developer dan stakeholder dengan mempertimbangkan kebutuhan yang SMART(*Specific, Measurable, Attainable, Realizable, Time Bounded, dan Tracable*) beserta hasil perhitungan prioritas kebutuhannya.
