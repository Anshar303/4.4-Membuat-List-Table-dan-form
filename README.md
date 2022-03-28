# Membuat List - Table dan form (HTML)
   ----------------------------------------
    Nama   : Ashar Rahmawan
    kelas  : TI.20.A2

    Langkah Langkahnya 
    


 •	Menyimpan file dengan format HTML

 ![image](https://user-images.githubusercontent.com/72779594/160318882-ecaaefa9-cbb7-4e5c-af9d-7e8bddc6c3a4.png)



      •	Memanggil Struktur HTML nya 

 ![image](https://user-images.githubusercontent.com/72779594/160318899-09bb747c-620b-4730-a11f-2e870b132db5.png)


            # MEMBUAT LIST
            
  •	Membuat ( header – oerered list dan unordered list )

 ![image](https://user-images.githubusercontent.com/72779594/160318969-1085bdfa-8790-4622-a0a7-f772aefebefc.png)

 
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

 ![image](https://user-images.githubusercontent.com/72779594/160319031-87fc19ff-51b6-4383-ab08-46da3f1fe3a3.png)

 

        # Description List
       Digunakan untuk membuat daftar dimana tiap daftar tersebut memiliki penjelasan (sub bagian). 
       Ada tiga tag yang digunakan untuk membuat description list,           
       yaitu:
       <dl> (description list) tag untuk memulai description list;
       <dt> (description term) tag untuk membuat kata yang akan dideskripsikan;
       <dd> (description description) tag untuk membuat penjelasan dari kata.
 

                                                    Maka akan menampilkan hasil seperti ini 


 ![image](https://user-images.githubusercontent.com/72779594/160319089-fffcad23-2eb7-4f5d-9fd1-ca830ad9280a.png)


 
                                                            # MEMBUAT TABLE

 •	Membuat file baru dan memanggil Struktur HTML nya 

 ![image](https://user-images.githubusercontent.com/72779594/160319151-1d8f34c5-73c3-4bf9-8753-f66353372f56.png)



      # Membuat kode untuk menampilkan table sederhana yang kita buat 
      
![image](https://user-images.githubusercontent.com/72779594/160319196-0b01f1fc-edd1-4112-a0ca-41b65fa626c6.png)

 
      •	Lalu mengisi data untuk di masukan ke dalam table 

 ![image](https://user-images.githubusercontent.com/72779594/160319217-32a64e0c-6fa2-40f8-9229-3d71a3c68189.png)


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

 ![image](https://user-images.githubusercontent.com/72779594/160319269-30c6b010-a4de-4677-82b6-5a0999a7607a.png)

 
 
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

![image](https://user-images.githubusercontent.com/72779594/160319316-7221930a-71c2-4074-93df-ad9a3bb18b12.png)



      •	Atribut action dapat diisi dengan url endpoint yang akan memproses data.
      •     Atribut enctype: Mendefinsikan cara encoding data sebelum dikirimkan. Biasanya digunakan
      jika ingin meng-upload file.
      •	 Atribut method: Metode pengiriman data.
      - GET: Data dikirimkan bersama URL.
      -  POST: Data dikirimkan terpisah dari URL.

      •	Menginputkan data dan membuat style pada form

 ![image](https://user-images.githubusercontent.com/72779594/160319333-5b4b16bb-92ca-4732-98a4-ed7b31e7d52d.png)


                                                       Maka akan menampilkan hasil seperti ini 

 
![image](https://user-images.githubusercontent.com/72779594/160319356-0ec98f2d-8ec0-4c20-8c69-49fb3a150822.png)



