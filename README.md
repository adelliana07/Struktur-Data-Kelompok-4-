mahasiswa = ("4400", "muhammad ucup")

nilai = [80, 85, 90]

print("Data Mahasiswa")
print("NIM  :", mahasiswa[0])
print("Nama :", mahasiswa[1])

print("\nDaftar Nilai Awal :", nilai)

nilai.append(88)

print("Daftar Nilai Setelah Ditambah :", nilai)

rata_rata = sum(nilai) / len(nilai)
print("Rata-rata Nilai :", rata_rata)
