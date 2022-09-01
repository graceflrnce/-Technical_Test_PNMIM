Program yang digunakan adalah Python. Program tersebut dapat dijalankan di https://colab.research.google.com 
kemudian file dapat di run di link tersebut.

#pada TASK 1
penjelasan program:
-def containLetter(param1, param2): #function yang bisa menerima 2 parameter
-hasil = True #hasil akan True apabila pengecekan bener
-for i, v in enumerate(param1): #looping terhadap param1, misal param1 adalah 'iet' akan dilakukan pengulangan sebanyak 3 kali
-lokasiChar = param2.lower().find(v) #untuk melakukan letak lokasi. misal 'iet' pada 'investment', dimana i ada di urutan pertama, e ada diurutan keempat, dan t ada diurutan berikutnya. apabila hasil tidak terdeteksi maka akan menghasilkan FALSE
maka, containLetter("ieg","investment") menghasilkan FALSE karena huruf 'g' tidak ada pada kalimat 'investment'

#pada TASK 2
penjelasan:
seseorang melakukan investasi dengan melihat timestamp keberapa NAB yang akan dia pakai. apabilan timestamp/pengecekkan waktu beli lebih dari jam 13.00 WIB maka menggunakan NAB update, apabila kurang dari jam 13.00 WIB maka memakai NAB jam 20.00 WIB
maka Unit Pe
