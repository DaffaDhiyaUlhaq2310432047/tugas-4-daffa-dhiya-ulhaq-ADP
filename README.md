# tugas-4-daffa-dhiya-ulhaq-ADP

lirik = str(input("Masukkan lirik lagu : "))
vokal = 'AIUEOaiueo'
a = ' '
b = 'AIUEO'
for i in lirik:
    if i in vokal:
        if i in b:
            a += 'I'
        else :
            a += 'i'
    else :
        a += i
print()
print(f"Hasil :{a}")
