1. Charlie merupakan salah satu data scientist di sebuah perusahaan musik 
di Indonesia. Dia diminta untuk membuat sebuah aplikasi yang membantu perusahaan untuk 
menentukan apa fitur yang penting dalam membedakan suara anjing dan kucing (binary 
classification). 
Tim data memberikan dataset yang dapat diunduh di: https://tinyurl.com/UTSaudio1 
Dalam dataset tersebut terdapat informasi penting mengenai suara anjing dan kucing. Buatlah model 
klasifikasi biner dengan algoritma machine learning: decision tree dan random forest untuk membedakan suara anjing dan kucing. Dalam soal ini tentunya yang paling penting adalah mengekstrak fitur-fitur suara yang penting dari suara tersebut sehingga model yang dihasilkan menjadi akurat. 
a. Lakukan eksplorasi data terlebih dahulu untuk memahami permasalahan yang 
dihadapi terlebih dahulu. Sebutkan pola apa saja yang kalian temukan dari data yang diberikan, berikan penjelasan mengenai pendekatan apa yang kalian gunakan untuk melakukan eksplorasi dan kenapa memilih pendekatan yang dipilih? 
b. Ekstrak semua fitur-fitur audio yang penting di domain waktu (time 
domain) dan domain frekuensi (frequency domain) terutama yang berkaitan dengan intensitas suara dan fundamental frekuensi (f0). Selanjutnya lakukan analisa apakah ada perbedaan yang terlihat dalam fitur tersebut yang membedakan suara anjing dan suara kucing? Kemudian pilihlah 
fitur yang paling menjanjikan dan berikan penalarannya! 
c. Setelah mengetahui hasil dari nomor (1b), buatlah model decision 
tree dan random forest untuk mengklasifikasikan suara anjing dan suara kucing (kalian harus melakukan tuning pada hyperparameter untuk mendapatkan model yang optimal). Jelaskan alasan kalian dalam pemilihan fitur dan penentuan hyperparameter yang kalian lakukan. 
d. Lakukan evaluasi unjuk kerja dari model random forest dan 
decision tree pada test set dengan mencari nilai accuracy, precision, recall dan F1-Score. 
Bandingkan hasil dari kedua model tersebut dan berikan analisa penjelasan mengenai hasil tersebut dengan mengamati sampel suara anjing dan suara kucing. 
e. Buatlah video presentasi yang menjelaskan model yang dibangun 
untuk mengklasifikasikan suara ini. 