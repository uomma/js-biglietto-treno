Il programma dovrà chiedere all’utente (1)il numero di chilometri che vuole percorrere
(2) e l’età del passeggero.
Sulla base di queste informazioni dovrà calcolare il prezzo totale del viaggio, secondo queste regole:
(3)il prezzo del biglietto è definito in base ai km (0.21 € al km)
(4)va applicato uno sconto del 20% per i minorenni
(5)va applicato uno sconto del 40% per gli over 65.
(6)L’output del prezzo finale va messo fuori in forma umana (con massimo due decimali, per indicare centesimi sul prezzo).

1prompt richiesta km tratta 
2prompt età passeggero
3 ('1'*0.21€)
4 se età < 18 applicare sconto 20%
5 se età > 65 applicare sconto 40%
6 utilizzare (Math.round(num * 100) / 100).toFixed(2); per output prezzo finale
