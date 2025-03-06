# UNIVERSITATEA „POLITEHNICA” DIN BUCUREȘTI
## Facultatea de Electronică, Telecomunicații și Tehnologia Informației  
### Proiect Componente și Circuite Pasive  
**Transformatorul monofazat de mică putere**  
*Marin Valentin-Gabriel*  
**Grupa 424D**  
București 2023  


## Cuprins

1. [Date inițiale de proiectare](#date-initiale-de-proiectare)  
2. [Rezumat](#rezumat)  
3. [Abstract](#abstract)  
4. [Aspecte generale](#aspecte-generale)  
5. [Calculul și dimensionarea ansamblului](#calculul-si-dimensionarea-ansamblului)  
6. [Alegerea rezistoarelor](#alegerea-rezistoarelor)  
7. [Calculul puterii transformatorului și dimensionarea acestuia](#calculul-puterea-transformatorului-si-dimensionarea-acestuia)  
8. [Concluzii](#concluzii)  
9. [Bibliografie](#bibliografie)

---

## Date inițiale de proiectare

Se va proiecta un transformator monofazat de mică putere, utilizând tehnologia SMD, ce va alimenta circuitul de mai jos. Parametrii de proiectare sunt următorii:

- **Tensiunea principală**: U1 = 110 [V]
- **Temperatura mediului ambiant**: 10...80 grade Celsius
- **Frecvența**: f = 60 [Hz]
- **Tensiunea de intrare**: U21 = 9 [V]

Rezistoarele au următoarele valori de rezistență:
- **R1** = 7.5 [Ω]
- **R2** = 15 [Ω]
- **R3** = 10 [Ω]
- **R4** = 12 [Ω]
- **R5** = 8.2 [Ω]
- **R6** = 22 [Ω]

![1.](img/p1.jpg?raw=true "Title")

## Rezumat

Scopul principal al proiectului este conceperea și construirea unui transformator monofazat de
mică putere, un dispozitiv crucial în gestionarea și manipularea energiei electrice. Transformatorul are
două funcții cheie: prima este ajustarea nivelului de tensiune electrică - fie pentru a crește tensiunea
pentru transmiterea eficientă a energiei electrice pe distanțe lungi, fie pentru a reduce tensiunea pentru
utilizări specifice, cum ar fi alimentarea unui telefon. A doua funcție este izolația galvanică între circuitul
primar (de intrare) și cel secundar (de ieșire), asigurând protecția utilizatorilor împotriva șocurilor
electrice.
Transformatorul prezintă avantaje semnificative datorită designului său simplu, care oferă o
fiabilitate ridicată și emisii electromagnetice minime, un aspect esențial în comparație cu alte surse de
alimentare care pot genera interferențe electromagnetică deranjante.
Din punct de vedere constructiv, transformatorul de mică putere este alcătuit din următoarele
componente principale:
• Carcasa electroizolantă: Aceasta oferă protecție împotriva contactului direct cu componentele
electrice și ajută la prevenirea accidentelor.
• Bobinajul: Acesta constă în înfășurări de fire conductoare, fiind divizat în bobina primară și cea
secundară, fiecare având rolul său specific în procesul de transformare a energiei electrice.
• Miezul feromagnetic: Este elementul central al transformatorului, prin care fluxul magnetic
generat de bobina primară este transferat eficient către bobina secundară.
• Sistemul de strângere a miezului magnetic și de fixare a transformatorului: Aceste mecanisme
asigură stabilitatea structurală a transformatorului și mențin componentele în poziția corectă.
Funcționarea transformatorului se bazează pe principiul inducției electromagnetice. Curentul
electric care circulă prin bobina primară generează un câmp magnetic. Datorită configurației
transformatorului, acest câmp magnetic străbate miezul feromagnetic și ajunge la bobina secundară.
În funcție de numărul de spire și de intensitatea câmpului magnetic, se induce o tensiune electrică în
bobina secundară. Această tensiune poate fi mai mare sau mai mică decât tensiunea inițială, în funcție
de raportul dintre numărul de spire din bobinele primară și secundară.
Astfel, transformatorul reprezintă un instrument esențial în sistemele moderne de distribuție și
utilizare a energiei electrice, fiind un exemplu clar de inginerie eficientă și sigură.

## Abstract

The primary objective of the project is the design and construction of a low-power single-phase
transformer, a crucial device in the management and handling of electrical energy. The transformer has
two key functions: the first is the adjustment of the electrical voltage level - either to increase the voltage
for efficient transmission of electrical energy over long distances, or to reduce the voltage for specific
uses, such as powering a laptop. The second function is the galvanic isolation between the primary
(input) and secondary (output) circuits, ensuring user protection against electric shocks.
The transformer offers significant advantages due to its simple design, which provides high
reliability and minimal electromagnetic emissions, an essential aspect compared to other power sources
that can generate annoying electromagnetic interference.
From a construction perspective, the low-power transformer consists of the following main
components:
• Electro-insulating Casing: This provides protection against direct contact with electrical
components and helps prevent accidents.
• Winding: This consists of windings of conductive wires, divided into the primary and secondary
coils, each having its specific role in the process of transforming electrical energy.
• Ferromagnetic Core: This is the central element of the transformer, through which the magnetic
flux generated by the primary coil is efficiently transferred to the secondary coil.
• System for Tightening the Magnetic Core and Fixing the Transformer: These mechanisms
ensure the structural stability of the transformer and keep the components in the correct
position.
The operation of the transformer is based on the principle of electromagnetic induction. The
electric current flowing through the primary coil generates a magnetic field. Due to the configuration of
the transformer, this magnetic field passes through the ferromagnetic core and reaches the secondary
coil. Depending on the number of turns and the intensity of the magnetic field, an electrical voltage is
induced in the secondary coil. This voltage can be higher or lower than the initial voltage, depending on
the ratio between the number of turns in the primary and secondary coils.
Thus, the transformer represents an essential tool in modern systems for the distribution and
use of electrical energy, being a clear example of efficient and safe engineering.

## Aspecte Generale

Utilizare Transformator:
• Din punct de vedere al utilizării: Putere, construcție specială (mare intensitate, mai multe înfășurări,
schimbarea numărului de faze, autotransformatoare, pentru măsură, pentru sudare).
• Număr de faze: Monofazate, Polifazate.
• Răcire: Cu aer, cu ulei (naturală sau forțată).
Componente Principale:
Carcasă electroizolantă, bobinaj, miez feromagnetic din tole de tablă silicioasă, sistem de strângere a
miezului magnetic și de fixare.
Eficiența Transformatorului:
Depinde de calitatea și geometria miezului magnetic, forma și dimensiunea înfășurărilor, diametrul
conductoarelor.
Tehnologie și Proiectare:
Generalități:
Structura constructivă, tehnologia de fabricație, metodologia de proiectare pentru
transformatoarele monofazice de mică putere (<500W) utilizate în aparatura electronică.
Structura și Funcția: Transformatorul monofazic de mică putere este folosit în multe scheme de
alimentare electronică, modificând tensiunea și curentul și oferind izolare galvanică.
Procesul Tehnologic de Realizare:
• Obținerea tolelor, tratament termic, realizarea carcasei.
• Bobinarea înfășurărilor, introducerea tolelor în carcasă.
• Strângerea miezului magnetic, impregnarea transformatorului.
• Controlul tehnic de calitate.
Proiectare:
Evaluarea puterii totale absorbită, calculul puterii în primar.
Dimensionarea secțiunii în fier a miezului magnetic.
Calculul numărului de spire pe volt, determinarea numărului de spire din înfășurările primare și secundare.
Evaluarea curentului din primar, dimensionarea diametrelor conductoarelor de bobinaj.
Calculul ariilor ocupate de înfășurări, dimensionarea tolei și grosimii pachetului de tole.
Exemplu Practic: Proiectarea unui transformator cu specificații detaliate, inclusiv alegerea tolelor, evaluarea
puterii și dimensionarea componentelor.
Aceasta este o sinteză concentrată a informațiilor detaliate despre tehnologia și proiectarea transformatorului de
rețea monofazic de mică putere.

## Calculul și dimensionarea ansamblului

- Detalii despre dimensionarea transformatorului și calcularea componentelor vor fi prezentate într-un capitol ulterior.

![2.](img/p2.jpg?raw=true "Title")

![3.](img/p3.jpg?raw=true "Title")

![4.](img/p4.jpg?raw=true "Title")


## Alegerea rezistoarelor

- **R1**: Rezistor SMD, 7.5 [Ω], 20 [W], toleranță ±5%
- **R2**: Rezistor SMD, 15 [Ω], 2 [W], toleranță ±5%
- **R3**: Rezistor SMD, 10 [Ω], 2 [W], toleranță ±5%
- **R4**: Rezistor SMD, 12 [Ω], 0.2 [W], toleranță ±0.5%
- **R5**: Rezistor SMD, 8.2 [Ω], 1.5 [W], toleranță ±5%
- **R6**: Rezistor SMD, 22 [Ω], 2 [W], toleranță ±1%

Am ales componentele de pe site-ul [www.ro.farnell.com](http://www.ro.farnell.com) ținând cont de disponibilitate, raportul calitate-preț, puterea nominală și toleranță.


## Calculul puterii transformatorului și dimensionarea acestuia

Calculul puterii și dimensionarea ansamblului vor fi prezentate în continuare. Detaliile complete sunt incluse în documentația tehnică a proiectului.

![5.](img/p5.jpg?raw=true "Title")

![6.](img/p6.jpg?raw=true "Title")

![7.](img/p7.jpg?raw=true "Title")

![8.](img/p8.jpg?raw=true "Title")

## Concluzii

Concluzia acestei lucrări evidențiază mai multe aspecte importante în domeniul ingineriei
electrice și, în special, în procesul de construcție și proiectare a circuitelor electrice. În primul rând,
lucrarea subliniază importanța alegerii condițiilor adecvate de circuit și a respectării normelor de
siguranță. Aceasta este o remarcă crucială, deoarece condițiile inadecvate sau nerespectarea
normelor de siguranță pot duce la defecțiuni ale circuitului sau chiar la accidente.
În al doilea rând, lucrarea recomandă studenților să se familiarizeze cu procesul de
construcție a unui circuit electric. Acest lucru este valoros pentru învățarea practică și dobândirea
unei înțelegeri profunde a principiilor de funcționare ale circuitelor electrice.
Mai departe, autorul subliniază diversitatea transformatoarelor disponibile pe piață și remarcă
faptul că acestea nu întotdeauna îndeplinesc cerințele specifice ale utilizatorilor. Acest aspect scoate
în evidență importanța adaptabilității și personalizării în ingineria electrică. Construirea unui
transformator personalizat permite nu doar satisfacerea cerințelor specifice, dar și o înțelegere
aprofundată a componentelor și a modului în care acestea funcționează împreună.
În final, lucrarea accentuează necesitatea respectării standardelor tehnice în construcția
transformatoarelor, precum grosimea sârmelor de bobinaj și decizia de a include sau nu izolație între
straturi. Aceste detalii tehnice sunt esențiale pentru performanța și siguranța transformatoarelor.
În concluzie, lucrarea oferă o perspectivă valoroasă asupra importanței detaliilor tehnice,
siguranței și personalizării în proiectarea și construcția circuitelor electrice și a componentelor
acestora, cum ar fi transformatoarele. Aceasta încurajează studenții să se angajeze activ în învățarea
practică și să acorde o atenție deosebită standardelor tehnice și de siguranță.

## Bibliografie

1. Cursuri din cadrul disciplinei „Componente și Circuite Pasive” accesibile pe platforma Moodle.
2. [https://www.cetti.ro/v2/ccp.php](https://www.cetti.ro/v2/ccp.php) – Resurse referitoare la „Rezistoare liniare fixe”.
3. [https://ro.farnell.com/](https://ro.farnell.com/) – Platformă pentru procurarea rezistoarelor de tip SMD.
4. [Wikipedia: Surface-mount technology](https://en.wikipedia.org/wiki/Surface-mount_technology) – Informații despre tehnologia montării pe suprafață.

