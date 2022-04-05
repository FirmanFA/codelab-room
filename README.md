## Hal Baru Yang Saya Dapatkan Dalam Run Through Codelab


### Android Architecture

Dalam codelab, implementasi kode dari room menggunakan arsitektur MVVM sebagai dasarnya.

### LiveData & Flow
Dalam codelab terdapat implementasi liveData dan Flow untuk melakukan perubahan data secara asyncronous, sehingga memudahkan dalam menghandle perubahan data secara realtime


### Repository
Dalam codelab, terdapat sebuah class Repository yang digunakan untuk berkomunikasi dengan data, seperti mengakses dan merubah. repository sebenarnya tidak termasuk dalam arsitektur MVVM, namun disarankan untuk menggunakan repository untuk memisahkan class yang mengakses data dan class yang berkomunikasi dengan UI

### ViewModel
Dalam codelab, terdapat sebuah class viewModel yang berguna untuk memberi data kepada tampilan/UI dan memberi sebuah ketahanan terhadap perubahan konfigurasi dari UI itu sendiri.

### ListAdapter
Dalam codelab, terdapat sebuah implementasi ListAdapter dalam sebuah adapter, ini merupakan sebuah class bawaan unutk memudahkan dalam menghandle diffutil dan list dari datanya