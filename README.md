# Tugas 7 : Elemen Dasar Flutter


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

# Tugas 8 : Flutter Form 

## Jelaskan perbedaan Navigator.push dan Navigator.pushReplacement!
Navigator.push menambahkan Route ke top of stack dari Navigator. Navigator.pushReplacement juga menambahkan Route ke top of stack namun juga menghilangkan Route sebelumnya.

## Sebutkan widget yang digunakan pada proyek ini dan fungsinya! 
(selain yang telah dijelaskan di readme Tugas 7)
- TextFormField, field teks untuk input pengguna
- Form, container untuk melakukan grouping widget field form
- DropdownButtonFormField, menu dropdown atau hamburger menu
- Card, panel tempat informasi
- Navigator, untuk mengelola child widgets menggunakan prinsip stack

## Sebutkan jenis-jenis event pada Flutter!
- onPressed
- onLongPress
- onSaved
- onTap

## Jelaskan cara kerja Navigator dalam "mengganti" halaman dari aplikasi Flutter!
Navigator menggunakan prinsip stack dalam mengganti halaman. Halaman yang ditampilkan adalah yang berada pada top of stack.

## Jelaskan cara implementasi checklist di atas.
- membuat form
- membuat field input sesuai soal
- menyimpan data yang diinput ke dalam list
- menyimpan data dalam bentuk card
- menampilkan data yang disimpan pada halaman Data Budget dengan mengakses list yang telah dibuat
