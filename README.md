# PYTHON_5

1. Aplikasi Terbilang

```y
numbers = input("masukan angka :")

numbers_mapping = {
    "1": "satu",
    "2": "dua",
    "3": "tiga",
    "4": "empat",
    "5": "lima",
    "6": "enam",
    "7": "tujuh",
    "8": "delapan",
    "9": "sembilan",
}

output = ""

for n in numbers:
    terbilang = numbers_mapping.get(n, "invalid")

    output = output + terbilang + " "

print(output)    
```
![image](https://user-images.githubusercontent.com/93015185/141058666-a68f4e34-3388-4f34-95e5-fc8c78c845e6.png)

2. Emoji Converter

```y
message = input(">>> ")

emoji_mapping = {
    ":)": "🙂",
    ":D": "😀",
    ":|": "😐",
}
words = message.split(" ")

output = ""
for w in words:
    output = output + emoji_mapping.get(w, w) + " "

print(output)
```
![image](https://user-images.githubusercontent.com/93015185/141058824-05dab449-1626-41bb-9f63-5d1df7e8bdce.png)

3. Fungsi

```y
def hallo_user():
    print("hallo fahroji")
    print("selamat anda mendapatkan uang 5 jt")


input("start")
hallo_user()
print("finish")
```
![image](https://user-images.githubusercontent.com/93015185/141058929-48812bda-6f22-4f0f-bff9-066985a9edd0.png)

4. Parameter Fungsi

```y
def hallo_user(nama, level):
    print(f"hallo {nama} - {level}")
    print("selamat anda mendapatkan uang 5 jt")


input("start")
hallo_user("fahroji",10)       #posisional argumen
print("===============")
hallo_user("lepang",5)
print("finish")
```
![image](https://user-images.githubusercontent.com/93015185/141059070-f85f6df5-806d-4f2f-8d05-d0d322b6ff8f.png)

5. Keyword Argument

```y
def hallo_user(nama, level):
    print(f"hallo {nama} {level}")
    print("selamat anda mendapatkan uang 5 jt")


input("start")
hallo_user(level=1, nama="fahroji")
print("finish")
```
![image](https://user-images.githubusercontent.com/93015185/141059246-7cdab1c3-a919-43cc-a76f-51a0876c990e.png)

6. Return Value

```y
def multiply(a, b):
    result = a*b
    return result

#input
#proses
#output

result = multiply(2,10)
print(result)
```
![image](https://user-images.githubusercontent.com/93015185/141059392-2f7fe215-60e7-423a-8b11-e66dc0042465.png)


