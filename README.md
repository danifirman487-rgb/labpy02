MENEMUKAN BILANGAN 

C:\Users\admin\PyCharmMiscProject\.venv\Scripts\python.exe "C:\Users\admin\PyCharmMiscProject\latihan 1.py" 
masukan bilangan pertama: 70
masukan bilanagan kedua: 50
masukan bilangan ketiga: 90
masukan bilangan keempat: 60
bilangan terbesar adalah 90

Process finished with exit code 0

=========================================================


Flowchart
        ┌─────────┐
        │  START  │
        └────┬────┘
             │
        ┌────▼────────────────────┐
        │ Input tipe_tiket        │
        │ Input status_member     │
        └────┬────────────────────┘
             │
        ┌────▼─────────────────┐
        │ tipe_tiket ==        │
        │ "reguler"?           │
        └─┬────────────────┬───┘
      Ya  │                │ Tidak
          │                │
    ┌─────▼─────┐    ┌─────▼─────┐
    │ harga =   │    │ tipe ==   │
    │ 50000     │    │ "vip"?    │
    └─────┬─────┘    └─┬───────┬─┘
          │         Ya │       │ Tidak
          │       ┌────▼────┐  │
          │       │ harga = │  │
          │       │ 100000  │  │
          │       └────┬────┘  │
          │            │    ┌──▼──────┐
          │            │    │ harga = │
          │            │    │ 0       │
          │            │    └──┬──────┘
          └────────┬───┴───────┘
                   │
            ┌──────▼──────────┐
            │ status_member   │
            │ == "y"?         │
            └──┬──────────┬───┘
           Ya  │          │ Tidak
         ┌─────▼────┐  ┌──▼──────┐
         │ diskon = │  │ diskon =│
         │ 0.2      │  │ 0       │
         └─────┬────┘  └──┬──────┘
               └──────┬───┘
                      │
            ┌─────────▼─────────┐
            │ total = harga -   │
            │ (harga × diskon)  │
            └─────────┬─────────┘
                      │
            ┌─────────▼─────────┐
            │ Tampilkan detail  │
            │ dan total harga   │
            └─────────┬─────────┘
                      │
                 ┌────▼────┐
                 │   END   │
                 └─────────┘
