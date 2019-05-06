# hallo-welt
my first repository
siabada
import random
import time
wylosowana = random.randint(1,10)
print(wylosowana)
wylosowana = random.randrange(10) +1
print(wylosowana)
wylosowana = random.random()
zaokraglona = round(wylosowana ,2)
print(zaokraglona)
wylosowana = random.random()
print("%.2f" %wylosowana)
slowo = "Kognitywistyka"
wylosowana = random.choice(slowo)
print(wylosowana)
cyfra = 0
start = time.clock()
while cyfra != 1:
    cyfra = int(input("Nie wcisnąłeś '1'\n"))
koniec = time.clock()
czas_trwania = koniec - start
print("Na wciśnięcie 1 potrzebowałeś: ", czas_trwania)
print("Początek: ",time.ctime())
time.sleep(5)
print("Koniec: ", time.ctime())
print("Uwaga!", time.ctime())
time.sleep(1)
print("5",time.ctime())
time.sleep(1)
print("4",time.ctime())
time.sleep(1)
print("3",time.ctime())
time.sleep(1)
print("2",time.ctime())
time.sleep(1)
print("1",time.ctime())
time.sleep(1)
print("BOOM!")

#jak zrobić to w pętli?
print("Aby rzucić kością napisz 'rzut'")
rzut = input()
if rzut == 'rzut' :
    wylosowana = random.randint(1,6)
    print(wylosowana)


print("Losowanie liczb")
wylosowana1 = random.randrange(1,49)
print(wylosowana1)
time.sleep(2)
wylosowana2 = random.randrange(1,49)
print(wylosowana2)
time.sleep(2)
wylosowana3 = random.randrange(1,49)
print(wylosowana3)
time.sleep(2)
wylosowana4 = random.randrange(1,49)
print(wylosowana4)
time.sleep(2)
wylosowana5 = random.randrange(1,49)
print(wylosowana5)
time.sleep(2)
wylosowana6 = random.randrange(1,49)
print(wylosowana6)
print("To są wylosowane liczby", wylosowana1, wylosowana2, wylosowana3, wylosowana4, wylosowana5, wylosowana6)

'''slowo = "Kognitywistyka"
wylosowana = random.choice(slowo)
print(wylosowana)
print("Wciśnij wylosowaną literę")
litera = input()
if litera == wylosowana :
    start = time.time()
    while litera != wylosowana :
        print("To nie jest wylosowana litera")
    koniec = time.time()
    czas_trwania = koniec - start
    print("Na wciśnięcie wylosowanej litery potrzebowałeś: ", czas_trwania)'''
#popraw


wylosowana = random.randrange(1,100)
print("Podaj liczbę z zakresu od 1 do 100")
liczbauzytkownika = int(input())
print(wylosowana)
if liczbauzytkownika >= wylosowana :
    print("Twoja liczba jest większa, wygrałeś!")
elif liczbauzytkownika <= wylosowana :
    print("Twoja liczba jest mniejsza, przegrałeś!")

print("To jest generator przysłów\nAby wyświetlić jedno wpisz 'przyslowie'\n\n")
slowo = input()
przyslowia = "Bez pracy nie ma płacy", "Czas leczy rany", "Czas to pieniądz", "Fortuna kołem się toczy", "Apetyt rośnie w miarę jedzenia"
if slowo == 'przyslowie' :
    wylosowana = random.choice(przyslowia)
    print(wylosowana)
