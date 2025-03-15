import random

def guess_number():
    target = random.randint(1, 100)
    attempts = 0

    print("猜数字游戏！目标数字在1到100之间。")

    while True:
        guess = int(input("请输入你的猜测："))
        attempts += 1

        if guess < target:
            print("猜小了！")
        elif guess > target:
            print("猜大了！")
        else:
            print(f"恭喜！你用了{attempts}次猜中了数字{target}！")
            break

if __name__ == "__main__":
    guess_number()# Hello
