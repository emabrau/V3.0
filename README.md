# V3.0

Tai yra programa, skirta apdoroti studentų namų darbų bei egzamino rezultatų duomenis. Vartotojui siūlomi keli studentų duomenų įvedimo būdai: rankinis įvedimas, skaitymas iš failo arba automatinis duomenų failų generavimas.

Naudojimosi instrukcija:
Pirmiausia vartotojas pasirenka duomenų įvedimo būdą: rankinis įvedimas (R), skaitymas iš failo (F) arba automatinis duomenų generavimas (G). Įvedame pasirinkimą atitinkančią raidę ir spaudžiame Enter. 

Pasirinkus rankinį įvedimą: Pirmiausia vartotojo paprašoma įvesti studento vardą ir paspausti Enter. Tuomet įvedama studento pavardė ir spaudžiama Enter. Vartotojas gali įvesti norimą skaičių namų darbų rezultatų, po kiekvieno iš jų paspausdamas Enter. Kai įvedus namų darbų rezultatą Enter paspaudžiamas du kartus, programa prašo įvesti studento egzamino rezultatą ir paspausti Enter. Tuomet galima lygiai taip pat įvesti kito studento duomenis arba vėl paspausti Enter ir baigti duomenų įvedimą. Programa apskaičiuoja kiekvieno studento galutinį balą pagal vidurkį ir pagal medianą ir išveda rezultatą lentelėje.

Pasirinkus duomenų nuskaitymą iš failo: Vartotojo paprašoma įvesti failo pavadinimą ir paspausti Enter. Programa apskaičiuoja kiekvieno studento galutinį balą pagal vidurkį ir pagal medianą ir išveda rezultatą lentelėje.

Pasirinkus automatinį failų generavimą: Pirmiausia vartotojas gali pasirinkti, ar failus generuoti naudojant vector ar list tipo konteinerius. Tuomet programa sugeneruoja 5 duomenų failus: ,,studentai_1000.txt", ,,studentai_10000.txt", ,,studentai_100000.txt", ,,studentai_1000000.txt" ir ,,studentai_10000000.txt", kuriuose yra pateikiami studentų vardas, pavardė, galutinis balas pagal vidurkį. Tuomet programa nuskaito studentų duomenis iš sugeneruotų failų ir apdoroja juos rūšiuodama pagal studentų vardus. Taip pat studentai skirstomi į dvi grupes: „kietiakai“ (aukštesnius pažymius turintys studentai) ir „nuskriaustukai“ (žemesnius pažymius turintys studentai). Po apdorojimo duomenys įrašomi į naujus failus, "nuskriaustukai_n.txt" ir "kietiakai_n.txt", čia n - skaičius, atitinkantis išrūšiuoto failo ,,studentai_n.txt" n skaičių. Programa taip pat matuoja failų generavimo, nuskaitymo, rūšiavimo ir išvedimo trukmę sekundėmis. Siekiant užtikrinti tikslų laiko matavimą, programa pakartoja kiekvieno studentų duomenų failo apdorojimą kelis kartus. Apskaičiuojamas vidutinis kiekvieno failo duomenų skaitymo, rūšiavimo ir rašymo laikas.

