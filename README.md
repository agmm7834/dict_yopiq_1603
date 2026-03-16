# 1. Dictionary (lug‘at) tushunchasi

## Savol 1

```python id="dct101"
students = {"Ali": 85, "Vali": 90, "Hasan": 78, "Husan": 92}
```

Dictionary ichidagi **eng yuqori ball olgan talabaning ismini** chiqaradigan kod yozing.

---

## Savol 2

```python id="dct102"
sales = {"apples": 50, "oranges": 75, "bananas": 30, "pears": 45}
```

Dictionary qiymatlari **yig‘indisini** hisoblaydigan kod yozing.

---

## Savol 3

```python id="dct103"
grades = {"Math": 80, "Physics": 75, "Chemistry": 85, "Biology": 90}
```

Dictionary ichidagi fanlardan **75 dan katta bo‘lgan fanlarni** ekranga chiqaradigan kod yozing.

---

## Savol 4

```python id="dct104"
inventory = {"pen": 10, "pencil": 20, "notebook": 15, "eraser": 5}
```

Dictionarydagi **eng kam mahsulot miqdoriga ega kalit**ni chiqaradigan kod yozing.

---

## Savol 5

```python id="dct105"
products = {"A": 100, "B": 200, "C": 150, "D": 250}
```

Dictionary ichidagi qiymatlarning **o‘rtacha qiymatini** hisoblaydigan kod yozing.

---

# 2. Dictionary yaratish usullari

## Savol 1

```python id="dct201"
d = dict()
```

`d` dictionary ga **3 ta kalit-qiymat juftligi** qo‘shing: `"x":10, "y":20, "z":30` va ekranga chiqarib ko‘ring.

---

## Savol 2

```python id="dct202"
d = {"a": 5, "b": 10}
```

Dictionary ga `"c":15` va `"d":20` juftligini qo‘shing va yangi dictionary ni chiqaring.

---

## Savol 3

```python id="dct203"
d = dict(name="Ali", age=20)
```

`age` qiymatini **25 ga o‘zgartiring** va dictionary ni chiqaring.

---

## Savol 4

```python id="dct204"
d = {}
```

Dictionary ga foydalanuvchidan 3 ta kalit va qiymat kiritishni so‘rab qo‘shing (input orqali).

---

## Savol 5

```python id="dct205"
d1 = {"x":1, "y":2}
d2 = {"y":3, "z":4}
```

`d1` va `d2` ni **bitta dictionaryga birlashtiring** (agar kalit takrorlansa, `d2` qiymati ustun kelsin).

---

# 3. Dictionary metodlari

## Savol 1

```python id="dct301"
grades = {"Math": 80, "Physics": 90, "Chemistry": 85}
```

`keys()` metodi yordamida barcha fan nomlarini sikl orqali chiqaring.

---

## Savol 2

```python id="dct302"
grades = {"Math": 80, "Physics": 90, "Chemistry": 85}
```

`values()` yordamida barcha ballarni chiqarib, ularni **yig‘indisini hisoblang**.

---

## Savol 3

```python id="dct303"
grades = {"Math": 80, "Physics": 90, "Chemistry": 85}
```

`items()` yordamida **fan nomi va ballni birma-bir** chiqaring, agar ball > 85 bo‘lsa `"Excellent"` yozing.

---

## Savol 4

```python id="dct304"
inventory = {"pen": 10, "pencil": 20, "notebook": 15}
```

`get()` metodidan foydalanib, `"eraser"` kalitini tekshiring, agar mavjud bo‘lmasa, **0 chiqaring**.

---

## Savol 5

```python id="dct305"
scores = {"Ali": 85, "Vali": 90, "Hasan": 78}
```

Dictionary ichidagi **har bir talabaning ismi va ballini formatlangan jumla bilan** chiqaring, masalan: `"Ali scored 85 points"`.

---

# 4. Dictionary + List aralash amaliyot

## Savol 1

```python id="dct401"
students = {"Ali": [85, 90], "Vali": [78, 88], "Hasan": [92, 95]}
```

Har bir talabaning **o‘rtacha ballini** hisoblang va yangi dictionaryga joylang.

---

## Savol 2

```python id="dct402"
inventory = {"pens": [10, 15], "pencils": [5, 10], "notebooks": [20, 25]}
```

Har bir mahsulotning **umumiy miqdorini** hisoblab chiqaring.

---

## Savol 3

```python id="dct403"
grades = {"Math": [80, 85, 90], "Physics": [70, 75, 80]}
```

Har bir fan bo‘yicha **eng yuqori ballni** aniqlang.

---

## Savol 4

```python id="dct404"
students = {"Ali": [85, 90, 95], "Vali": [70, 75, 80]}
```

Har bir talaba uchun **ballar yig‘indisi 250 dan katta bo‘lsa `"Passed"`**, aks holda `"Failed"` deb chiqaring.

---

## Savol 5

```python id="dct405"
scores = {"Ali": [10, 20], "Vali": [5, 15], "Hasan": [20, 25]}
```

Har bir talaba uchun **ballar o‘rtacha qiymati > 15 bo‘lsa** `"A"`, <= 15 `"B"` deb chiqaradigan kod yozing.

---
