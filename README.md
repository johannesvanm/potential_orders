# potential_orders
# kensho
print("***Kensho-Masala***")
voorgerechten_en_tapas = ["Dimsum kip (6 stuks)","Dimsum mix (6 stuks)", "Dimsum mix (12 stuks)", "Edamame (sojaboontjes)", "Yakitori kip", "Loempia kip (4 stuks)", "Loempia vegetarisch (4 stuks)", "Tempura scampi (3 stuks)", "Zeewiersalade", "Tomaten erwtensoep", "Soep van de chef", "Nepalese kip momo (6 stuks)", "Samosa (2 stuks)", "Onion bhaji", "Kip tikka saté", "Scampi tandoori", "Mix tapas"]
prijzen_voorgerechten_en_tapas = [7.00, 8.00, 14.00, 6.00, 5.50, 5.50, 5.00, 6.50, 8.00, 5.70, 6.00, 7.00, 6.50, 6.50, 8.50, 13.70, 12.00]
print("---Voorgerecht:---")
z = 0
prijs = 0
while z < 4:
  import random
  a = random.randint(0,16)
  print(voorgerechten_en_tapas[a])
  prijs += prijzen_voorgerechten_en_tapas[a]
  z += 1
kindergerechten = ["Kip loempia", "Kip tikka saté", "1/2 Kip tikka masala"]
prijzen_kindergerechten = [8.00, 10.00, 11.00]
print("---Kindergerecht:---")
import random
a = random.randint(0,2)
print(kindergerechten[a])
prijs += prijzen_kindergerechten[a]
print("Prijs: €", prijs)
