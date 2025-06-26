# 🐍 Day 1 – Python Basics

## 🗒️ Comments

```python
# This is a comment in Python
```

---

## 🧮 Variables

```python
print('Hello World')
print('George')

name = 'George'
age = 32

print(name)
print(age)

full_name = 'George Piner'
print(full_name)

width, height = 400, 500
print(width)
print(height)
```

---

## 👤 User Input

```python
your_name = input('Please enter your name: ')
print('Hi ' + your_name)
```

---

## 🔢 Simple Calculator

```python
num1 = input('Enter a number: ')
num2 = input('Enter another number: ')
print(int(num1) + int(num2))
```

---

## 📚 Data Types

- **Strings** – `'hello'`, `"cookie"`  
  - `'10' + '20'` = `'1020'`
- **Integers / Floats** – `1`, `2.5`, `100`
- **Operators**: `+`, `-`, `*`, `/`, `//`, `%`, `**`

---

## 💸 Tip Calculator App

```python
food_amount = float(input('Enter food amount $: '))
tip_percentage = float(input('Enter your tip percentage %: ')) / 100
tip_amount = food_amount * tip_percentage
total = food_amount + tip_amount

print('-------------------------------')
print(f'Food Amount: ${food_amount}')
print(f'Tip Amount: ${tip_amount}')
print('\n')
print('Total Amount: $' + str(total))
print('-------------------------------')
```

---

## 🔡 String Formatting

```python
name = 'George'
print(f'Hello, {name}!')
```

---

## ✅ Booleans and If-Else

```python
# If withdrawal amount > balance:
#   don't allow withdraw
# Else:
#   allow withdrawal
```

---

## ☔ Baby Weather App

```python
weather = input('How is the weather? ')

if weather == 'rain':
    print('☔')

if weather == 'cloudy':
    print('☁️')

if weather == 'thunderstorm':
    print('⛈️')

else:
    print('😎')
```

---

## 🔁 Comparison Operators

- `==` equal to  
- `!=` not equal to  
- `<`, `>`, `<=`, `>=`

---

✍️ **End of Day 1**