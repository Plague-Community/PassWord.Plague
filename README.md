import webbrowser
from colorama import *
import string
import random
import pyfiglet


ascii_banner = pyfiglet.figlet_format("PassWord")
print(Fore.GREEN + ascii_banner)

print(Fore.LIGHTMAGENTA_EX + "[ " + Fore.RED + "https://github.com/Plague-Community" + Fore.LIGHTMAGENTA_EX + " ]\n \n")

PassWord = int(input(Fore.CYAN + "[1] Números \n[2] Letras \n" + Fore.BLUE + "Escribe Aqui > "))

if PassWord == 1:
    print(random.randint(11111111,99999999))
    
    open('[PassWord].txt', 'a+').write("PassWord > \n " + str(random.randint(11111111,99999999)) + "\n")

if PassWord == 2:
    Random_1 = random.choice(string.ascii_letters)
    Random_2 = random.choice(string.ascii_letters)
    Random_3 = random.choice(string.ascii_letters)
    Random_4 = random.choice(string.ascii_letters)
    Random_5 = random.choice(string.ascii_letters)
    Random_6 = random.choice(string.ascii_letters)
    Random_7 = random.choice(string.ascii_letters)
    Random_8 = random.choice(string.ascii_letters)
    Random_9 = random.choice(string.ascii_letters)
print(Random_1 + Random_2 + Random_3 + Random_4 + Random_5 + Random_6 + Random_7 + Random_8 + Random_9)
open('[PassWord].txt', 'a+').write("Password > \n " + Random_1 + Random_2 + Random_3 + Random_4 + Random_5 + Random_6 + Random_7 + Random_8 + Random_9)
