# Postaw-na-milion
Pierwszy wspólny projekt



pytanie1 = ("Pytanie1?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")
pytanie2 = ("Pytanie2?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")
pytanie3 = ("Pytanie3?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")
pytanie4 = ("Pytanie4?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")
pytanie5 = ("Pytanie5?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")
pytanie6 = ("Pytanie6?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")
pytanie7 = ("Pytanie7?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")
pytanie8 = ("Pytanie8?\n a. odpowiedz | b. odpowiedz\n c. odpowiedz | d. odpowiedz\n ")

pytania = [pytanie1, pytanie2, pytanie3, pytanie4, pytanie5, pytanie6, pytanie7, pytanie8]

odpowiedz1 = ("Coś1")
odpowiedz2 = ("Coś2")
odpowiedz3 = ("Coś3")
odpowiedz4 = ("Coś4")
odpowiedz5 = ("Coś5")
odpowiedz6 = ("Coś6")
odpowiedz7 = ("Coś7")
odpowiedz8 = ("Coś8")

odpowiedzi = [odpowiedz1, odpowiedz2, odpowiedz3, odpowiedz4, odpowiedz5, odpowiedz6, odpowiedz7, odpowiedz8]

imie = input("Jak masz na imię? ")
print("Witaj, ", imie, ", w programie 'Postaw na milion'!")


def gra(x):

    odpowiedzGracza = input(pytania[x])

    if odpowiedzGracza == odpowiedzi[x]:
        print("Prawidłowa odpowiedź.")
        if pytanie1:
            print("Komentarz1.")  ### komentarze trzeba poprawić, bo zawsze wyświetla komentarz1, pewnie musimy dodać coś w stylu "if pytanie1 == ?:"
        elif pytanie2:
            print("Komentarz2.")
        elif pytanie3:
            print("Komentarz3.")
        elif pytanie4:
            print("Komentarz4.")
        elif pytanie5:
            print("Komentarz5.")
        elif pytanie6:
            print("Komentarz6.")
        elif pytanie7:
            print("Komentarz7.")
        elif pytanie8:
            print("Komentarz8.")
    else:
        print("Zła odpowiedź.")

for x in range(len(pytania)):
    gra(x)
