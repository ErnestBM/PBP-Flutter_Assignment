# counterku - seharusnya counter_7


## Jelaskan apa yang dimaksud dengan _stateless widget_ dan _stateful widget_ dan jelaskan perbedaan dari keduanya!

_Stateless widget_ adalah _widget_ yang bentuknya tidak bisa diubah setelah dibuat. 
_Stateful widget_, di sisi lain, memberikan kemampuan bagi pengguna untuk mengubah _widget_ yang dibuat.

## Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya!
- AppBar(), sebagai judul dari halaman
- Center(), untuk perataan tengah elemen-elemen _widget_ 
- Text(), menampilkan teks dan _styling_
- Icon(), menampilkan ikon pada _widget_
- Scaffold, sebagai landasan halaman

## Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut!
Fungsi setState() adalah adalah memberikan informasi pada _widget_ akan perubahan pada _State_ dengan tujuan me-_refresh_ aplikasi dengan nilai baru setelah perubahan. Pada aplikasi ini, variabel yang terdampak adalah [counter]

## Jelaskan perbedaan antara const dengan final!
Pada inisialisasi **const**, harus ada variabel pada kompilasi yang bersifat konstan dan secara langsung/eksplisit, sedangkan **final** dapat diinisialisasi tanpa memiliki nilai secara eksplisit.

## Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas!
- membuat _if-else clause_ berdasarkan nilai [counter]
- membuat _text widget_ genap dan ganjil
- menambahkan fungsi decrementCounter()
- membuat _widget_ _FloatingActionButton_ di bagian bawah kiri
