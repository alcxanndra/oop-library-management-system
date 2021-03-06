**Denumire proiect**

<b>LIB+</b> (Sistem de gestiune a unei biblioteci online).

**Descriere proiect**

<b>LIB+</b> este un sistem de gestiune a unei biblioteci online, destinat utilizării de către bibliotecarul responsabil de conducerea bibliotecii.

**_Tipuri de obiecte definite:_**

**1)** Persoana = reprezintă o clasă de bază care va fi extinsă de către clasele Autor, Cititor, și AngajatBibliotecă. O persoană are un ID unic, un nume și un prenume.

**2)** Autor = reprezintă autorul unei cărți (moștenește clasa Persoana), având nume, prenume, respectiv o listă de cărți scrise din sistem.

**3)** Carte = reprezintă o carte din bibliotecă, identificată printr-un ID unic. O carte are un titlu, aparține unei secțiuni, este scrisă de un autor,
   un atribut de tip bool "esteImprumutata" reprezentând statutul actual al cărții (true = cartea este împrumutată / false = cartea nu este împrumutată), respectiv o listă de Rezervări efectuate de către cititori pentru această carte.

**4)** Cititor = reprezintă un membru cititor al bibliotecii (moștenește clasa Persoana). Este identificat printr-un ID unic, nume, prenume, o listă cu împrumutările *actuale* de cărți, respectiv o listă cu rezervări de cărți.

**5)** AngajatBiblioteca = reprezintă un angajat al bibliotecii (moștenește clasa Persoana). Este identificat printr-un ID unic, având de asemenea un nume, un prenume, respectiv un salariu de tip double.

**6)** Imprumut = reprezintă un împrumut al unei cărți efectuat de către un cititor. Un împrumut este definit de către cititorul care a efectuat împrumutul, cartea împrumutată, data efectuării împrumutului, data limită pentru a returna cartea, respectivă data actuală a returnării cărții de către cititor. 
   În sistem se vor păstra toate împrumuturile (atât cele active, cât și cele vechi, cele active având câmpul dataActualaReturnare setat ca null).

**7)** Sectiune = reprezintă o secțiune din cadrul bibliotecii. O secțiune are un ID unic, un nume, respectiv o listă de cărți conținute.

**8)** Rezervare = reprezintă o rezervare pentru păstrarea unei anumite cărți efectuate de către un cititor. O rezervare este reprezentată de cititorul care a efectuat rezervarea, cartea pentru care a fost efectuată rezervarea, respectiv data rezervării. 

**_Acțiuni/interogări implementate în cadrul sistemului:_**
1) Afișarea tuturor cărților din sistem (în ordinea adăugării în sistem).
2) Adăugarea unei cărți noi în sistem.
3) Ștergerea unei cărți existente în sistem.
4) Afișarea informațiilor (titlu, secțiune, autor, status) despre o carte cu un ID introdus.
5) Afișarea rezevărilor existente pentru o carte din sistem.
6) Modificarea titlului/autorului/secțiunii unei cărți existente în sistem.
7) Afișarea tuturor autorilor din sistem (în ordine alfabetică după numele de familie).
8) Adăugarea unui autor nou în sistem.
9) Ștergerea unui autor existent în sistem.
10) Afișarea tututor cărților din sistem scrise de către un autor având numele și prenumele introduse.
11) Afișarea tuturor secțiunilor existente în sistem (ordonate alfabetic).
12) Afișarea tuturor secțiunilor existente în sistem (ordonate descrescător după numărul de cărți conținute).
13) Adăugarea unei secțiuni noi în sistem.
14) Ștergerea unei secțiuni existente în sistem.
15) Modificarea unei secțiuni existente în sistem.
16) Afișarea tuturor angajaților din bibliotecă.
17) Adăugarea unui angajat nou al bibliotecii în sistem.
18) Actualizarea salariului unui angajat existent în sistem.
19) Afișarea tuturor cititorilor existenți în sistemul bibliotecii.
20) Adăugarea unui cititor nou în sistemul bibliotecii.
21) Ștergerea unui cititor existent din sistem.
22) Afișarea cărților împrumutate în prezent de către un cititor cu un ID introdus.
23) Efectuarea unui nou împrumut al unei cărți disponibile din sistem către un cititor.
24) Efectuarea returnării unei cărți împrumutate anterior de către un cititor în sistem.
25) Efectuarea unei rezervări pentru o anumită carte de către un cititor din sistem.
26) Ștergerea unei rezervări existente în sistem.


**Autori proiect**

Căldărușe Bianca Alexandra, grupa 244, FMI UniBuc.
