# sekar
uji cobsa

nama = str(input("Masukan Nama : "))
umur = int(input("Masukan Umur : "))
pekerjaan_orang_tua = str(input("Masukan Pekerjaan Orang Tua : "))
gaji_orang_tua= int(input("Masukan Gaji Orang Tua : "))
ipk= float(input("Masukan IPK : "))

print("Nama:", nama)
print("Umur:", umur)
print("Pekerjaan Orang Tua:", pekerjaan_orang_tua)
print("Gaji Orang Tua:", gaji_orang_tua)
print("IPK:", ipk)

list = ['PNS', 'Karyawan Swasta', 'Wiraswasta']

if pekerjaan_orang_tua not in list and gaji_orang_tua <= 1000000 and ipk >= 2.7 and umur < 25:
    print("Selamat")
else:
    print("Maaf,", nama, "tidak  memenuhi syarat.")
