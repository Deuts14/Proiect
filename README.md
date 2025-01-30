	Program pentru administrarea unui cont de client de telefonie mobila. Contul este creat in ziua 0 si s-a considerat ca fiecare luna are 30 de zile.
	In codul de fata se considera ca un client are abonamenul care costa X lei si din ziua 0  are ca beneficii incluse:
convorbiri in retea nelimitate
NC minute de convorbiri in alte retele
NS mesaje SMS in orice retea (inclusiv in cea proprie)
NT trafic internet in MB

Facturarea, in care sunt incluse costul abonamentului si costurile serviciilor ce depasesc atributele abonamentului, este scadenta la 30 de zile, iar daca nu este platit la timp se aplica o penalizare in valoare de P% din valoarea facturii.  Dupa ce este platita factura, clientul reprimeste beneficiile pentru urmatoarele 30 de zile.

Serviciile ce pot fi folosite de client, precum și costul în cazul depășirii:
A) Convorbire în rețea proprie: cost 0.
B) Convorbire în alte rețele, după depășirea celor NC minute incluse în abonament: 
mai puțin de 5 minute: 0.5 lei/minut;
între 5 - 30 minute: 0.3lei/minut;
mai mult de 30 minute: 0.2 lei/minut. 
C) Mesaje text (SMS), după depășirea celor NS mesaje incluse în abonament:
mai puțin 20 caractere: 0.1 lei/caracter;
între 20 - 50 caractere: 0.05 lei/caracter;
mai mult de 50 caractere: 0.02 lei/caracter.
D) Trafic internet, după depășirea celor NT MB incluși în abonament:
mai puțin de 1000 MB: 0.3 lei/MB;
între 1000 - 10000 MB: 0.2 lei/MB;
mai mult de 10000 MB: 0.1 lei/MB. 
E) Plata factura. Factura este plătită în întregime, clientul primește toate beneficiile iar termenul de 30 de zile este resetat. 

Date de intrare
Pe prima linie, separate prin spațiu, N X NC NS NT P Z, cu semnificația din cerință.
Pe următoarele N linii, informațiile despre serviciile apelate, sub una din formele
A Ziua Durata
B Ziua Durata
C Ziua NrCaractere
D Ziua CantitateTrafic
E Ziua

Date de ieșire
Al câtelea serviciu costă cel mai mult, fără să țineți cont de beneficiile din abonament.
