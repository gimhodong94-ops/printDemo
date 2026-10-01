# Python Print Examples — Quick Guide

이 저장소는 Python에서 다양한 출력 방법을 소개하는 간단한 예제 코드입니다.  
변수 선언부터 여러 가지 출력 형식과 옵션을 포함한 다양한 출력 방식을 보여줍니다.

---


```python
name = "김호동"
age = 20
score = 99.9
```

```python
print("Hello, Python!")
print("Name:", name, "Age:", age)
print(f"My name is {name}, age {age}")
print("Name: {}, Age: {}".format(name, age))
print("Name: %s, Age: %d" % (name, age))
print("Hello", end=" ")
print("2026", "09", "29", sep="-")
```

`main_print_v2.py`는 `rich`로 Panel, Table, 색상 출력을 보여줍니다.