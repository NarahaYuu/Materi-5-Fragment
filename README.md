# Materi-5-Fragment
Sebuah Fragment merupakan kombinasi sebuah layout XML dan kelas java yang mirip dengan sebuah Activity.
Dengan menggunakan support library, fragment dapat mendukung hampir semua versi Android.
Fragment dapat dipakai berulang kali di dalam activity.

Fragment memiliki banyak method yang dapat di override seperti halnya Activity:

    onAttach() dipanggil saat sebuah fragment terhubung ke activity.
    onCreate() diapnggil saat sebuah fragment dibuat (objeknya di memori).
    onCreateView() dipanggil saat fragment sudah siap membaca sebuah layout.
    onViewCreated() dipanggil setelah onCreateView() dan memastikan layout yang dibaca fragment adalah non-null. Semua pengaturan view seperti pembacaan findViewById, menambah onClickListener dapat dilakukan di sini.
    onActivityCreated() dipanggil setelah activity pembaca sudah menyelesaikan onCreate()-nya.
    onStart() dipanggil setelah fragment siap untuk ditampilkan di layar.
    onResume() - Dipakai untuk melakukan pembacaan data yang lebih “rumit” seperti lokasi, sensor, dll.
    onPause() - Tempat melepas data “rumit”. Lakukan commit di sini.
    onDestroyView() dipanggil saat layout sebuah fragment akan dihapus dari memori, namun fragmentnya masih ada di memori.
    onDestroy() dipanggil jika fragment sudah tidak dipakai.
    onDetach() dipanggil saat fragment tidak lagi terhubung ke sebuah activity.

![lifecycle fragmetn](https://user-images.githubusercontent.com/62680911/109180584-99ee7d00-77bd-11eb-81b0-daae8c3da5a4.png)


![Materi-5-Fragment1](https://user-images.githubusercontent.com/62680911/109179369-65c68c80-77bc-11eb-8d5d-698a1a79b515.jpg)
![Materi-5-Fragment2](https://user-images.githubusercontent.com/62680911/109179712-c1911580-77bc-11eb-94aa-a497b3abdf4d.jpg)

