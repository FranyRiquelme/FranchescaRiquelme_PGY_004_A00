# FranchescaRiquelme_PGY_004_D00
print("Bienvenido a Creativo.cl");
("--------------------------------");
print("Estas comprando una entrada vip para el concierto de Michael Jam");

asientos[[1,2,3,4,5,6,7,8.9,10]
[11,12.13,14,15,16,17,18,19,20]
[21,22,23,24,25,26,27,28,29,30]
[31,32,33,34,35,36,37,38,39,40]
[41,42,43,44,45,46,47,48,49,50]
[51,52,53.54,55,56,57,58,59,60]
[61,62,63,64,65,66,67,.68,69,70]
[71,72,73,74,75,76,77,78,79,80]
[81,82,83,84,85.86,87,88,89,90]
[91,92,93,94,95,96,97,98,99,100]]



Platinum=120000
gold=80000
silver=50000


menu=0
total=0
TotalParcial=0
QuiereOtraMas=0


while menu<1 or menu>3

print("Indique la entrada a pedir: ");
print("1:Platinum $120.000" (asiento <=1 al 20=>));
print("2.Gold $80.000" (asiento <=21 al 50=>));
print("3.Silver $50.000" (asiento <=51 al 100=>));
menu=int(input("Elija opción: "));


if menu==1 or menu==2 or menu==3:

    cantidad=0;

    QuiereOtraMas=0;

 while cantidad<1:

    cantidad=int(input("Ingrese cantidad: "));

if menu==1

    totalParcial=($120.000)*cantidad;

        total=total+totalParcial;

        totalParcial=0;
elif menu==2
    totalParcial=($80.000)*cantidad;

        total=total+totalParcial;

        totalParcial=0;

elif menu==3
    totalParcial=($50.000)*cantidad;

        total=total+totalParcial;

        totalParcial=0;

 else:

    print("Opción inválida, ingrese otra vez");

while quiereMas<1 or quiereMas>2:

    quiereMas=int(input("¿Quiere pedir algo más 1->Si 2->No?"));

    if quiereMas==1:

      menu=4;

    elif quiereMas==2:

      print(f"Su total es de ${total}");

      print("Gracias por su compra");

    else:

      print("opcion invalida");

print("Gracias por su compra")
