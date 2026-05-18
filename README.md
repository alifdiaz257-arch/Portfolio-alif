# matrix_glitch.py
import random, time, os

while True:
    os.system('cls' if os.name == 'nt' else 'clear')
    for _ in range(25):
        line = ''.join(random.choice("01!@#$%^&*") for _ in range(60))
        print(f"\033[32m{line}\033[0m")
    time.sleep(0.08)
