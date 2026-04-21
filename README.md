# برنامج صغير جداً
name = input("ما اسمك؟ ")
age = int(input("كم عمرك؟ "))

print(f"مرحباً {name}!")
print(f"أنت عمرك {age} سنة")

if age >= 18:
    print("أنت بالغ")
else:
    print("أنت قاصر")
