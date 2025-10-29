# kondisional-dan-perulangan-tuugasimport random

# Input jumlah bilangan acak
n = int(input("Masukkan jumlah n: "))

# Inisialisasi penghitung
count = 0

# Loop sampai jumlah bilangan yang ditampilkan = n
while count < n:
    angka = random.random()  # menghasilkan angka acak antara 0.0 dan 1.0
    if angka < 0.5:
        print(angka)
        count += 1
        # Program mencetak pola angka dengan nested loop

# Jumlah baris
for i in range(9):  # dari 0 sampai 8
    # Kolom dalam setiap baris
    for j in range(11):  # dari 0 sampai 10
        print(i + j, end="  ")
    print()  # pindah ke baris berikutnya
    
