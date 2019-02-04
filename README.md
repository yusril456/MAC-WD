
MAC-WD (Module of Automatic Faucet For Convensional Water Dispanser) merupakan sebuah modul keran air berteknologi cerdas pada water dispanser yang didesain untuk melakukan putaran otomatis dan mengisi air pada gelas sesuai volume-nya. Prediksi volume air ini menggunakan logika fuzzy dengan mengatur kecepatan putaran aktuator servo yang dipasang pada keran air. Kecepatan putaran dikonversikan sebagai keputusan durasi waktu (saat servo berubah arah putaran/ posisi buka) yang dihasilkan oleh Logika fuzzy terhadap parameter ketinggian air gallon dan ketinggian obyek gelas. Dataset ketinggian yang diolah tersebut diperoleh dari tangkapan sensor ultrasonic terhadap jarak permukaan air pada gallon dan obyek gelas. 

Cara kerja MAC-WD :
Perubahan posisi motor servo berbanding lurus terhadap volume gelas yaitu apabila nilai volume gelas berada pada posisi lebih kecil maka durasi waktu servo semakin cepat. Saat sensor mendeteksi ketinggian air galon dan ketinggian air gelas , sistem akan melakukan evaluasi rule yaitu fuzzy akan menentukan letak input data sesuai variabel parameter yang telah ditentukan. Hasilnya akan  di-defuzifikasi untuk menghasilkan keputusan berupa durasi waktu servo saat keran terbuka.


 
