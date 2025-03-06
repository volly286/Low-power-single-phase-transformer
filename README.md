# Transformatorul Monofazat de Mică Putere

 
 
 
 
- 1 - 
 
 
 
UNIVERSITATEA „POLITEHNICA” DIN BUCUREȘTI 
Facultatea de Electronică, Telecomunicații și Tehnologia Informației 
 
 
 
 
 
 
 
Proiect 
Componente și Circuite Pasive 
 
Transformatorul monofazat de mică putere 
 
 
 
 
 
Marin Valentin-Gabriel 
Grupa 424D 
 
 
 
 
 
Bucuresti 2023 
 
 
 
 
 
 
- 2 - 
 
 
 
 
 
 
 
 
 
 
 
 
Cuprins  
Date inițiale de proiectare............................................................................................................................ 3 
Rezumat ............................................................................................................................................... 4 
Abstract............................................................................................................................................... 5 
Aspecte generale....................................................................................................................................... 6 
Calculul și dimensionarea ansamblului.................................................................................................................. 7 
Alegerea rezistoarelor................................................................................................................................. 10 
Calculul puterii transformatorului și dimensionarea acestuia........................................................................................... 11 
Concluzii ............................................................................................................................................. 15 
Bibliografie........................................................................................................................................... 16 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
- 3 - 
 
 
 
 
 
 
 
 
Date inițiale de proiectare: 
Se va proiecta un transformator monofazat de mică putere,utilizand tehnologia SMD, ce  va 
alimenta circuitul de mai jos. Tensiunea principală fiind urmatoarea U1 = 110 [V],  temperatura mediului 
ambiant este de 10...80 grade Celsius, frecvența f = 60 [Hz], tensiunea de intrare  U21 = 9 [V] iar 
rezistoarele au urmatoarele rezistente R1 = 7.5 [Ω], R2 = 15 [Ω], R3 = 10 [Ω], R4 = 12 [Ω], R5 = 8.2 [Ω] 
și R6 = 22 [Ω].  
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
- 4 - 
 
 
 
Rezumat: 
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
- 
Carcasa electroizolantă: Aceasta oferă protecție împotriva contactului direct cu componentele 
electrice și ajută la prevenirea accidentelor. 
- 
Bobinajul: Acesta constă în înfășurări de fire conductoare, fiind divizat în bobina primară și cea 
secundară, fiecare având rolul său specific în procesul de transformare a energiei electrice. 
- 
Miezul feromagnetic: Este elementul central al transformatorului, prin care fluxul magnetic 
generat de bobina primară este transferat eficient către bobina secundară. 
- 
Sistemul de strângere a miezului magnetic și de fixare a transformatorului: Aceste mecanisme 
asigură stabilitatea structurală a transformatorului și mențin componentele în poziția corectă. 
Funcționarea transformatorului se bazează pe principiul inducției electromagnetice. Curentul 
electric care circulă prin bobina primară generează un câmp magnetic. Datorită configurației 
transformatorului, acest câmp magnetic străbate miezul feromagnetic și ajunge la bobina secundară. 
În funcție de numărul de spire și de intensitatea câmpului magnetic, se induce o tensiune electrică în 
bobina secundară. Această tensiune poate fi mai mare sau mai mică decât tensiunea inițială, în funcție 
de raportul dintre numărul de spire din bobinele primară și secundară. 
Astfel, transformatorul reprezintă un instrument esențial în sistemele moderne de distribuție și 
utilizare a energiei electrice, fiind un exemplu clar de inginerie eficientă și sigură. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
- 5 - 
 
 
 
 
Abstract: 
 
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
- 
Electro-insulating Casing: This provides protection against direct contact with electrical 
components and helps prevent accidents. 
- 
Winding: This consists of windings of conductive wires, divided into the primary and secondary 
coils, each having its specific role in the process of transforming electrical energy. 
- 
Ferromagnetic Core: This is the central element of the transformer, through which the magnetic 
flux generated by the primary coil is efficiently transferred to the secondary coil. 
- 
System for Tightening the Magnetic Core and Fixing the Transformer: These mechanisms 
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
 
 
 
 
 
 
 
 
 
 
 
 
 
- 6 - 
 
 
Aspecte Generale: 
Utilizare Transformator: 
- 
Din punct de vedere al utilizării: Putere, construcție specială (mare intensitate, mai multe înfășurări, 
schimbarea numărului de faze, autotransformatoare, pentru măsură, pentru sudare). 
- 
Număr de faze: Monofazate, Polifazate. 
- 
Răcire: Cu aer, cu ulei (naturală sau forțată). 
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
- 
Obținerea tolelor, tratament termic, realizarea carcasei. 
- 
Bobinarea înfășurărilor, introducerea tolelor în carcasă. 
- 
Strângerea miezului magnetic, impregnarea transformatorului. 
- 
Controlul tehnic de calitate. 
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
 
 
 
 
 
 
 
 
 
 
- 7 - 
 
 
Calculul și dimensionarea ansamblului: 
 
 
 
 
 
 
 
- 8 - 
 
 
 
 
 
 
 
- 9 - 
 
 
 
 
 
 
 
- 10 - 
 
 
 
Alegerea rezistoarelor: 
 
Pentru R1, am ales un rezistor de tip SMD de rezistență 7.5 [Ω], putere nominală 20 [W] > P1 , 
toleranta ±5%; 
Pentru R2, am ales un rezistor de tip SMD de rezistență 15 [Ω], putere nominală 2 [W] > P2  ,toleranta 
±5%; 
Pentru R3, am ales un rezistor de tip SMD de rezistență 10 [Ω], putere nominală 2 [W] > P3 , toleranta 
±5%; 
Pentru R4, am ales un rezistor de tip SMD de rezistență 12 [Ω], putere nominală 0,2 [W] > P4 , 
toleranta ±0.5%; 
Pentru R5, am ales un rezistor de tip SMD de rezistență 8.2 [Ω], putere nominală 1.5 [W] > P5 , 
toleranta ±5%; 
Pentru R6, am ales un rezistor de tip SMD de rezistență 22 [Ω], putere nominală 2 [W] > P6 , toleranta 
±1%; 
Am ales componentele de pe site-ul www.ro.farnell.com. Am ținut cont de disponibilitatea produselor 
din stoc, raportul calitate-preț, de puterea nominală, toleranță, dar și de cantitatea minimă care poate 
să fie achiziționată în acest moment. 
 
 
 
 
 
 
- 11 - 
 
Calculul puterii transformatorului și dimensionarea acestuia: 
 
 
 
 
 
 
 
- 12 - 
 
 
 
 
 
 
 
 
- 13 - 
 
 
 
 
 
 
 
 
- 14 - 
 
 
 
 
 
 
 
 
- 15 - 
 
 
 
 
 
Concluzii: 
 
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
 
 
 
 
 
 
- 16 - 
 
 
 
Bibliografie: 
 
Bibliografia lucrării include mai multe surse esențiale pentru cercetare și studiu. În primul 
rând, sunt menționate cursurile din cadrul disciplinei „Componente și Circuite Pasive”, accesibile pe 
platforma Moodle. Aceste cursuri au oferit o bază teoretică solidă și materiale de referință importante. 
 
Apoi, lucrarea face referire la site-ul web al disciplinei https://www.cetti.ro/v2/ccp.php, de 
unde autorul a extras informații relevante pentru lucrarea de laborator, în special pentru secțiunea 
despre „Rezistoare liniare fixe”. 
 
În plus, lucrarea a utilizat resurse de pe site-ul https://ro.farnell.com/, o platformă web de 
unde au fost procurate rezistoarele de tip SMD utilizate în construcția transformatorului. Aceasta 
sugerează că rezistoarele alese au fost specifice pentru tehnologia montării pe suprafață (Surface-
Mount Technology), o metodă importantă în construcția de circuite. 
 
În cele din urmă, lucrarea include și referințe de pe pagina Wikipedia despre tehnologia 
montării pe suprafață, https://en.wikipedia.org/wiki/Surface-mount_technology, ceea ce indică o 
cercetare suplimentară pentru înțelegerea mai profundă a acestei tehnici în construcția de circuite. 
Aceste surse diverse asigură o bază solidă de cunoștințe și resurse pentru lucrare. 
