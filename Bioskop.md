Jawaban Pertanyaan Percobaan 1
1. Apakah pengisian elemen array harus dilakukan secara berurutan mulai dari indeks ke-0? Jelaskan!
Tidak harus berurutan. Array dalam Java memungkinkan pengisian elemen secara acak atau tidak berurutan. Kita bisa langsung mengakses dan mengisi elemen array dengan indeks tertentu, misalnya penonton[2][1] = "Budi" tanpa harus mengisi indeks sebelumnya terlebih dahulu. Namun, elemen yang tidak diisi akan memiliki nilai default (untuk String adalah null).
2. Mengapa terdapat null pada daftar nama penonton?
Nilai null muncul karena elemen array tersebut belum diinisialisasi atau diisi dengan nilai. Ketika array objek (seperti String) dideklarasikan, semua elemennya secara otomatis diinisialisasi dengan nilai default null. Hanya elemen yang sudah diisi secara eksplisit yang akan memiliki nilai selain null.
3. Done.
4. Jelaskan fungsi dari penonton.length dan penonton[0].length! Apakah penonton[0].length, penonton[1].length, penonton[2].length, dan penonton[3].length memiliki nilai yang sama? Mengapa?
penonton.length = mengembalikan jumlah baris dalam array 2 dimensi (dalam kasus ini = 4).
penonton[0].length = mengembalikan jumlah kolom pada baris ke-0 (dalam kasus ini = 2).
Ya, dalam kasus array penonton ini, penonton[0].length, penonton[1].length, penonton[2].length, dan penonton[3].length memiliki nilai yang sama yaitu 2, karena setiap baris memiliki jumlah kolom yang sama (2 kolom). Namun, Java mendukung jagged array di mana setiap baris bisa memiliki jumlah kolom yang berbeda.
5. Done.
6. Done.
7. Done.