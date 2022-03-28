# Membuat List - Table dan form (HTML)
   ----------------------------------------
    Nama   : Ashar Rahmawan
    kelas  : TI.20.A2

    Langkah Langkahnya 
    


      •	Menyimpan file dengan format HTML

 


      •	Memanggil Struktur HTML nya 

 


            # MEMBUAT LIST

      •	Membuat ( header – oerered list dan unordered list )

 

      # List 
      HTML List memungkinkan untuk mengelompokkan sekumpulan item terkait dalam sebuah daftar.
      HTML sudah menyediakan elemen untuk membuat list. Ada tiga macam jenis list yang bisa dibuat
      di HTML, yaitu:
      • Ordered List adalah list yang terurut;
      • Unordered List adalah list yang tak terurut;
      • dan Descriptiona List adalah list yang berisi definisi.

      # ordered list 
      Digunakan untuk membuat daftar dimana tiap bagiannya ditandai dengan sebuah simbol. Ordered list dibuat dengan tag <ol>. 
      Lalu di dalamnya diisi dengan item - item yang akan dimasukkan ke dalam list. Item dibuat dengan tag <li> (list item).

      Secara default ordered list akan diurutkan berdasarkan angka 1,2,3,...dst. Angka tersebut dapat
      diubah sesuai dengan kebutuhan, misalnya ingin menampilkan urutan berdasarkan angka romawi
      atau huruf abjad seperti a,b,c,...dst. Untuk merubah jenis tampilan list tersebut dengan
      menambahkan atribut type pada tag ol dan berikan nilainya sesuai dengan yang diinginkan.

      • a untuk alfabet a, b, c, dan seterusnya;
      • A untuk alfabet A, B, C, dan seterusnya;
      • i untuk angka romwari i, ii, iii, dan seterusnya;
      • I untuk angka romwari I, II, III, dan seterusnya.


      # Unordered list 
      Digunakan untuk membuat daftar dimana tiap bagiannya memiliki nomor secara terurut. 
      Unordered list dibuat dengan tag <ul> dan untuk item-nya dibuat juga dengan tag <li>.

      Secara default simbol yang digunakan oleh unordered list adalah lingkaran kecil (disc). 
      Simbol tersebut dapat diubah sesuai dengan kebutuhannya, seperti kotak, lingkaran, atau tanpa simbol. 
      Untuk mengubahnya dengan menambahkan atribut type pada tag ul dan berikan nilainya sesuai dengan yang diinginkan.

     square untuk simbol persegi;
     • disc (default) untuk simbol lingkaran disc;
     • none tidak memakai simbol;
     • circle untuk simbol lingkaran;
 

   
      • Membuat descripsion List

 

        # Description List
       Digunakan untuk membuat daftar dimana tiap daftar tersebut memiliki penjelasan (sub bagian). 
       Ada tiga tag yang digunakan untuk membuat description list,           
       yaitu:
       <dl> (description list) tag untuk memulai description list;
       <dt> (description term) tag untuk membuat kata yang akan dideskripsikan;
       <dd> (description description) tag untuk membuat penjelasan dari kata.
 

                                                    Maka akan menampilkan hasil seperti ini 

 



 
                                                            # MEMBUAT TABLE

 •	Membuat file baru dan memanggil Struktur HTML nya 

 


      # Membuat kode untuk menampilkan table sederhana yang kita buat 

 
      •	Lalu mengisi data untuk di masukan ke dalam table 

 

      <table> 	Mendefinisikan sebuah tabel dalam dokumen HTML.
      Atribut: border, cellpadding, cellspacing
      <thead> 	untuk membungkus bagian kepala tabel
      <tbody> 	untuk membungkus bagian body dari tabel
      <th> 		Membuat judul kolom
      <tr> 	Mendefinisikan baris dalam tabel. Atribut: align (left, center, right), valign (top, middle, bottom)
      <td> 	Mendefinisikan kolom tabel. Atribut: align (left, center, right), valign (top, middle, bottom), colspan, rowspan.
      Tag yang paling penting untuk diingat adalah tag <table>, <tr>, dan <td>. 
      Sementara tag yang lain adalah tambahan (opsional), boleh digunakan boleh tidak.

      Menggabungkan Sel Data
      Sel data pada tabel dapat digambugkan untuk keperluan tertentu. 
      Untuk menggabungkan sel secara vertikal menggunakan atribut rowspan dan untuk menggabungkan sel secara horizontal menggunakan atribut colspan. 
      Atribut tersebut dapat ditambahkan pada tag td (tabel data) dengan nilai atributnya adalah jumlah sel yang akan digabungkan.
 
                                                   Maka akan menampilkan hasil seperti ini 

 
 
      # MEMBUAT FORM

•	Membuat file baru dan memanggil Struktir Data nya

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Membuat form</title>
      </head>
      <body>


•	Membuat header dan membuat kode untuk memanggil form 

 

      •	Atribut action dapat diisi dengan url endpoint yang akan memproses data.
      •     Atribut enctype: Mendefinsikan cara encoding data sebelum dikirimkan. Biasanya digunakan
      jika ingin meng-upload file.
      •	 Atribut method: Metode pengiriman data.
      - GET: Data dikirimkan bersama URL.
      -  POST: Data dikirimkan terpisah dari URL.

      •	Menginputkan data dan membuat style pada form

 

                                                       Maka akan menampilkan hasil seperti ini 

 



