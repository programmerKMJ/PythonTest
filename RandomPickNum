import random

# 1부터 100사이의 랜덤 숫자 1개 뽑기
random_num = random.randint(1, 100)
print(f"1부터 100사이의 랜덤 숫자: {random_num}")

# 0부터 9사이의 숫자 5개를 중복 없이 뽑기
random_nums = []
while len(random_nums) < 5:
    random_num = random.randint(0, 9)
    if random_num not in random_nums:
        random_nums.append(random_num)
print(f"0부터 9사이의 숫자 5개 (중복 없이): {random_nums}")

# 로또 6개 번호 뽑기
lotto_nums = []
while len(lotto_nums) < 6:
    random_num = random.randint(1, 45)
    if random_num not in lotto_nums:
        lotto_nums.append(random_num)
lotto_nums.sort()
print(f"로또 6개 번호: {lotto_nums}")
