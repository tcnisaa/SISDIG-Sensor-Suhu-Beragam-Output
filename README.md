Power pada rangkaian menggunakan enable pada ic supaya logika aktif, pake logika human presence dan power “AND”,
yang dimana jika kalau keduanya nilai 1, ambil logika “window LDR temp”.

Terdapat 4 Output
- ac
- ⁠kipas
- ⁠lampu
- ⁠alarm: indikator misal suhu panas, jendela terbuka. ac mati, ganti ke kipas

Logika Rangkaian
- logika ac: akan nyala saat suhu 1, saat jendela 0
- kipas: jika power human 1, kipas 1
- kipas: jendela 1, kipas 1
- suhu dan jendela 1, kipas 1, ac 0
- lampu: ldr 1, lampu 1
- pada IC, E1 harus 1 supaya kebaca dan rangkaian jalan.

Seluruh pengerjaan dilakukan di Proteus.

Tangguh Chairunnisa
