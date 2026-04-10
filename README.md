1. Array itu aksesnya cepet banget (O(1)) karena datanya disusun berurutan di memori, jadi bisa langsung diambil pakai indeks. Nah kalau linked list lebih lambat (O(n)) karena harus jalan satu-satu dari awal buat nemuin datanya.
2. Linked list lebih enak dipakai kalau sering nambah atau hapus data, karena cuma perlu ubah pointer aja (O(1)). Kalau array, harus geser-geser data dulu, jadi lebih lama (O(n)).
3. Doubly linked list itu tiap node punya data, next, sama prev. Jadi bisa jalan maju dan mundur, tapi minusnya makan memori lebih banyak.
4. Circular linked list itu node terakhirnya nggak kosong, tapi balik lagi ke node pertama, jadi kayak lingkaran. Cocok buat sistem yang muter terus, kayak round robin.
5. Python list itu sebenarnya dynamic array. Kalau udah penuh, dia bakal bikin tempat baru yang lebih gede, terus data lama dipindahin, baru nambah data lagi. Walaupun kadang jadi agak lama (O(n)), tapi biasanya tetap kerasa cepet (O(1)).
