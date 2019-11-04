#latihan 1
#labpy02


Cara Membuat Programsederhana.
yang dibutuhkan hanyalah

statmen IF.

Struktur Algoritma

    1. Mulai
    2. Inisiasi Bil1, Bil2, Bil3 Sebagai Integer
    3. Baca Bil1.
    4. Baca Bil2.
    5. Baca Bil3.
    6. Jika Bil1>Bil2 dan Bil1>Bil3 maka kerjakan langkah 8, selain itu
    7. Jika Bil2>Bil1 dan Bil2>Bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10
    8. Cetak "Bilangan Terbesar Bilangan Pertama"
    9. Cetak "Bilangan Terbesar Bilangan Kedua"
    10. Cetak "Bilangan Terbesar Bilangan Ketiga"
    11. SELESAI
  
STEP PADA SOURCE CODE
  
Print ('program untuk menentukan bilangan terbesar dan terkecil')

def pengulangan():

    print ('masukkan 3 bilangan yang diinginkan !')
    a=int(input('bilangan1 = '))
    b=int(input('bilangan2 = '))
    c=int(input('bilangan3 = '))
    
    if a>b and a>c:
      if b>c:
        print (a, 'terbesar dan', c, 'terkecil')
      else:
        print (a, 'terbesar dan', b, 'terkecil')
    elif b>a and b>c:
      if a>c:
        print (b, 'terbesar dan', c, 'terkecil')
      else:
        print (b, 'terbesar dan', a, 'terkecil')
    else:
      if a>b:
        print (c, 'terbesar dan', b, 'terkecil')
      else:
        print (c, 'terbesar dan', a, terkecil')
        
    print ('')
    print ('ingin coba lagi? (ya/tidak)')
    x=input()
    if x=='ya'
         return pengulangan()
    if x=='tidK':
         print('Teriamkasih Telah Menggunakan Program Ini.')
         
   Pengulangan()
   
   GAMBAR FLOWCHART
   
   
                  
   ![Screenshot (63)](https://user-images.githubusercontent.com/53387786/68129860-e66cd400-ff4c-11e9-961b-814ba012aca0.png)
   
   
   Screenshoot Code 1
	 
	 
![Screenshot (65)](https://user-images.githubusercontent.com/53387786/68130178-7c086380-ff4d-11e9-866d-a118a92df8fe.png)


   Screenshoot Code 2
	 
	 

![Screenshot (66)](https://user-images.githubusercontent.com/53387786/68130361-cd185780-ff4d-11e9-807b-da053ee055f0.png)



   Screenshoot Hasil
	 
 ![Screenshot (67)](https://user-images.githubusercontent.com/53387786/68130573-27191d00-ff4e-11e9-8fdc-51adb07ac4e0.png)



SEMOGA BERMANFAAT
	
	
   
      
        
      
