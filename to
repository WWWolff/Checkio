# write your code here
a=int(2); b=int(5)

#ex2

def checkio(data: str) -> bool:
    components = data.split()
    for i in range(len(components) - 2):
        if (components[i].isalpha() and
            components[i + 1].isalpha() and
            components[i + 2].isalpha()):
            return True

    return False

#ex3

def beginning_zeros(s: str) -> int:
    count = 0
    for char in s:
        if char == '0':
            count += 1
        else:
            break

    return count

#ex4

def longest_word(sentence: str) -> str:
    words = sentence.split()
    if not words:
        return ""

    longest = max(words, key=len)

    return longest

#ex5
def mult_two(a: int, b: int) -> int:
    return a * b


print("Example")
print(mult_two(1, 2))

assert mult_two(3, 2) == 6
assert mult_two(0, 1) == 0

print("The first mission is done! Click 'Check' to earn cool rewards!")

#ex6
def rectangle_perimeter(length: int, width: int) -> int:
    per = (length + width)*2
    return per


print("Example:")
print(rectangle_perimeter(3, 2))

# These "asserts" are used for self-checking
assert rectangle_perimeter(2, 4) == 12
assert rectangle_perimeter(3, 5) == 16
assert rectangle_perimeter(10, 20) == 60
assert rectangle_perimeter(7, 2) == 18
assert rectangle_perimeter(1, 1) == 4
assert rectangle_perimeter(1, 5) == 12
assert rectangle_perimeter(4, 1) == 10
assert rectangle_perimeter(100, 100) == 400
assert rectangle_perimeter(0.5, 2) == 5

print("The mission is done! Click 'Check Solution' to earn rewards!")

#ex7

def is_even(num: int) -> bool:
    # your code here
    if num%2==0:
        return True
    else:
        return False
    return None

#ex8
def determine_sign(num: int) -> str:
    # your code here
    if num>0:
        sign = "positive";
    elif num==0:
        sign = "zero";
    else:
        sign = "negative";
    return sign

#ex9
def determine_sign(num: int) -> str:
    # your code here
    if num>0:
        sign = "positive";
    elif num==0:
        sign = "zero";
    else:
        sign = "negative";
    return sign

#ex10
def find_remainder(dividend: int, divisor: int) -> int:
    # your code here
    rem = dividend % divisor
    return rem

#ex11
def backward_string(val: str) -> str:
    # your code here
    return val[::-1]


print("Example:")
print(backward_string("val"))

#ex12
def checkio(num: int) -> str:
    if num%3==0:
        return "Fizz"
    else:
        return str(num)

#ex13
def first_word(text: str) -> str:
    # your code here
    lista = str.split(text)
    return lista[0]


print("Example:")
print(first_word("Hello world"))

#ex14
def number_length(value: int) -> int:
    # your code here
    a = str(value)
    return len(a)


print("Example:")
print(number_length(10))

#ex15
def checkio(num: int) -> str:
    if num%3==0 and num%5==0:
        return "Fizz Buzz"
    elif num%3==0:
        return "Fizz"
    elif num%5==0:
        return "Buzz"
    else:
        return str(num)

#ex16
def count_vowels(text: str) -> int:
    # your code here
    vowels=("a","e","i","o","u")
    count = 0
    text = text.lower()
    for char in text:
        if char in vowels:
            count += 1
    return count


print("Example:")
print(count_vowels("Hello"))

#ex17
def sum_upto_n(N: int) -> int:
    # your code here
    count = 0
    for i in range(1, N+1):
        count += i
    return count

#ex18
def to_title_case(sentence: str) -> str:
    # your code here
    sen = sentence.split()
    for i in range(0, len(sen)+1):
        obj = map(str.capitalize, sen)
    return " ".join(obj)

#ex19
def replace_all(mainText: str, target: str, repl: str) -> str:
    return mainText.replace(target, repl)


print("Example:")
print(replace_all("hello world", "world", "TypeScript"))

# These "asserts" are used for self-checking
assert replace_all("hello world", "world", "TypeScript") == "hello TypeScript"
assert (
    replace_all("hello world world", "world", "TypeScript")
    == "hello TypeScript TypeScript"
)

#ex20
def factorial(n: int) -> int:
    # your code here
    st = 1
    if n==0:
        return 1
    elif n==1:
        return 1
    else:
        return n*factorial(n-1)


print("Example:")
print(factorial(4))

#ex21
def between_markers(text: str, start: str, end: str) -> str:
    # your code here
    inizio = text.find(start) +1
    fine = text.find(end)

    return text[inizio:fine]


print("Example:")
print(between_markers("What is >apple<", ">", "<"))

#ex22
def goes_after(word: str, first: str, second: str) -> bool:
    # Ensure that the symbols are different
    if first == second:
        return False

    # Check if both symbols are present in the string
    if first not in word or second not in word:
        return False

    # Check if the second symbol immediately follows the first symbol
    for i in range(len(word) - 1):
        if word[i] == first and word[i + 1] == second:
            return True

    return False

#ex23
def max_digit(value: int) -> int:
    # your code here
    return max(map(int, str(value)))


print("Example:")
print(max_digit(10))

#ex24
def sum_numbers(text: str) -> int:
    # your code here
    result = []
    for i in text.split():
        if i.isdigit()==True:
            result.append(int(i))
        else:
            pass
    return result

#ex25
def checkio(data: str) -> bool:
    components = data.split()
    for i in range(len(components) - 2):
        if (components[i].isalpha() and
            components[i + 1].isalpha() and
            components[i + 2].isalpha()):
            return True

    return False


#ex26
def beginning_zeros(s: str) -> int:
    count = 0
    for char in s:
        if char == '0':
            count += 1
        else:
            break

    return count

#ex27
