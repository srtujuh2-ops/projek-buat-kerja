print("selamat datang di toko mobil")
saldo = int(input("masukkan saldo anda "))
if saldo >= 1000000000:
    print("anda membeli toyota alphard")
elif saldo >= 600000000:
    print("anda membeli toyota fortuner")
elif saldo >= 400000000:
    print("anda membeli toyota innova")
elif saldo >= 250000000:
    print("anda membeli toyota avanza")
elif saldo >= 150000000:
    print("anda membeli toyota agya")
else:
    print("saldo anda tidak cukup")