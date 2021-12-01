# Numguess
n = 20

guess_num = 9

while(guess_num<=9):

    print("guess the number")
    num = int(input())

    if num>20:
        print("you entered greater number")
        guess_num=guess_num-1
        print("no of guesses left", guess_num)
    elif num<20:
        print("you entered smaller number")
        guess_num = guess_num - 1
        print("no of guesses left", guess_num)
    else:

        print("you won ,entered correct number")
        print("you took ",9-guess_num,"attempts")

        break

else:

    print("gameover")

