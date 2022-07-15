inputs = input().lower().split("\\n")
first_line = 0
for inp in set(inputs[1:]):
    first_line += 1
numbers_of_duplicates = {}
second_line = []
for i in inputs[1:]:
    numbers_of_duplicates[i] = inputs.count(i)
for i in numbers_of_duplicates:
    second_line.append(str(numbers_of_duplicates[i]))
print(f"{first_line}\n{' '.join(second_line)}")
