# python-17-masala
#agar global o'zgaruvchini qiymatini funksiya ichida o'zgartirmoqchi bo'lsangiz ham global ishlatiladi
x="shirin"
def funksiya():
    global x
    x= "foydali"
    print("Olma "+ x)
funksiya()
print("Olma "+x)
