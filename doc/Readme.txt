MONOPOLEE GAME - README FILE
Kelompok OOP STI 2017 - Ucul Banget Lah
Version 2. 21 April 2019


A. Asumsi yang digunakan selama pengembangan game
	1. Jumlah pemain hanya 2 orang.
	2. Kartu bebas penjara bisa didapatkan player ketika mengambil kartu Chance / Community Chest. Masing-masing kartu Chance / Community Chest terdapat 1 buah kartu bebas penjara. Ketika seorang pemain mendapatkannya, diasumsikan kartu bebas penjara yang ada di Chance / Community Chest tidak berkurang, hanya menambahkan atribut jumlah kartu penjara milik player, sehingga jumlah deck cards tetap 16 buah untuk masing-masing Chance / Community Chest.
	3. Diasumsikan ketika seorang pemain mendarat di Free Parking maka ia akan mendapatkan tambahan uang 100, namun pemain tersebut hanya diam saja tanpa perintah pindah posisi.
	4. Ketika seorang player mendapatkan perintah untuk mendarat di suatu tempat, baik itu dari perintah Card, ataupun setelah bebas dari penjara, giliran/turn pemain tersebut dilimit hanya 1x saja. Misalnya ketika player mendapatkan kartu ”Go To Kopo”, maka player tersebut hanya pergi ke Tile Kopo tanpa bisa melakukan perintah untuk membelinya.

	5. Diimplementasikan fitur menjual property (bukan mortgage) dimana seorang player dapat menjual property yang dimilikinya (beserta rumah yang dibangun di Lot jika ada). Penjualan property ditetapkan mendapatkan harga penuh property beserta rumah pada Lot. Misalnya sebuah Lot harga belinya 200, maka ketika seorang player menjual Lot tersebut, ia akan mendapat tambahan uang 200.
	6. Kondisi menang seorang player terjadi ketika pemain tersebut tidak dapat membayar lagi harga sewa suatu property yang sudah dimiliki dan juga tidak memiliki property untuk dijual. Maka player tersebut akan bangkrut.
	7. Untuk melakukan pembelian rumah, pemain cukup mendapatkan 1 kompleks terlebih dahulu kemudian nanti ketika pemain berada pada salah satu petak yang telah ia punyai maka otomatis akan ada pilihan mau beli rumah/tidak. Pembelian rumah hanya bergantung pada sudah punya 1 kompleks/belum dan hanya ketika pemain tersebut berada di petak itu sehingga dimungkinkan satu daerah tertentu bisa memiliki 3 rumah sekaligus tetapi daerah lainnya yang masih ada dalam satu kompleks belum memiliki rumah.
	8. Untuk keluar dari penjara dengan memilih pilihan roll dadu, tidak ada kesempatan berapa kali di penjara maksimalnya sehingga apabila seorang pemain tidak memiliki uang yang cukup atau tidak memiliki kartu bebas penjara, maka pemain tersebut harus meroll dadu seterusnya untuk mendapatkan double


B. Cara bermain game yang perlu diperhatikan
	1. Klik dua kali pada file "Monopolee - Kelompok Ucul Banget Lah.jar"
	2. Setelah muncul layar welcome screen, akan tampak tampilan awal dari game, terdiri dari 3 button (start game, bantuan, exit)
	3. Untuk memulai permainan silahkan klik tombol "Main Dong !"
	4. Pada layar baru yang muncul, silahkan isikan 2 nama pemain yang akan bermain, klik pada tombol "Start Game !"
	5. Kemudian tampilan map game akan muncul, pada sisi kiri permainan merupakan tampilan papan permainan game Monopolee dengan pemain 1 direpresentasikan oleh kotak berwarna HITAM, dan pemain 2 direpresentasikan oleh kotak berwarna BIRU
	6. Pada sisi kanan layar, terdapat bagian interaksi permainan dengan pemain, terdapat 6 buah tombol yang dapat digunakan oleh pemain untuk bermain, terdiri dari (Roll Dadu, Move, Buy Tempat, List Properti, Sell Tempat, dan End Turn)dan juga GameLog yang tersedia bagi pemain untuk melihat informasi detil
	7. Tiap pemain memiliki waktu 30 detik untuk menyelesaikan giliran bermainnya, tiap 1 turn dibatasi dengan klik 1 tomboll roll dadu dan berpindah tempat. Informasi terkait nama pemain, uang, dan lokasi terkini terdapat pada tiap bilah yang tersedia. 
	8. Setelah 30 detik berlalu, turn akan selesai dan pemain akan berganti giliran, oleh karena itu mohon untuk selalu menyelesaikan hal yang ingin dilakukan sebelum 30 detik berlalu.
	9. Tiap turn pemain, terdapat urutan menekan tombol yang wajib diikuti, dimulai dari tombol "Roll Dadu" baru kemudian "Move Position".
	10. Untuk membeli suatu properti tekan tombol "Buy Tempat", apabila pada momen yang tepat maka akan muncul pop-up menu lebih lanjut terkait validasi pembelian.
	11. Untuk menjual suatu properti tekan tombol "Sell Tempat", apabila dalam kondisi idle dan masih dalam turn yang benar, maka akan muncul form penjualan properti yang dimiliki suatu pemain.
	12. Untuk melihat list properti yang dimiliki oleh pemain, tekan tombol "List Props" maka akan muncul pop-up informasi terkait dengan semua properti dimiliki pemain
	13. Untuk mengakhiri suatu turn bermain, maka tekan tombol "End Turn" maka otomatis turn pemain kana berakhir dan berganti pemain selanjutnya
	14. Tiap ada kondisi chance, community chest, atau kekurangan uang untuk membayar denda, maka akan muncul form penjualan properti yang dimiliki untuk menanggulangi kekurangan uang tersebut
	15. Apabila masuk penjara, pemain memiliki 3 pilihan yaitu membayar uang sebanyak 100, menggunakan kartu bebas penjara, atau melakukan roll dadu apabila double maka bisa keluar
	16. Permainan berkahir apabila seorang pemain tidak dapat membayar suatu tagihan dalam game dan tidak memiliki properti satu pun, baik itu Lot, Stasiun, atau Utility.
