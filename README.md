# POLITEHNICA UNIVERSITY OF BUCHAREST
## Faculty of Electronics, Telecommunications, and Information Technology
### Project: Passive Components and Circuits
**Single-Phase Low-Power Transformer**  
*Marin Valentin-Gabriel*  
**Group 424D**  
Bucharest 2023

## Table of Contents

1. [Initial Design Data](#initial-design-data)  
2. [Summary](#summary)  
3. [Abstract](#abstract)  
4. [General Aspects](#general-aspects)  
5. [Calculation and Dimensioning of the Assembly](#calculation-and-dimensioning-of-the-assembly)  
6. [Resistor Selection](#resistor-selection)  
7. [Transformer Power Calculation and Dimensioning](#transformer-power-calculation-and-dimensioning)  
8. [Conclusions](#conclusions)  
9. [Bibliography](#bibliography)

---

## Initial Design Data

A single-phase low-power transformer using SMD technology will be designed to power the circuit below. The design parameters are as follows:

- **Primary Voltage**: U1 = 110 [V]
- **Ambient Temperature**: 10...80 degrees Celsius
- **Frequency**: f = 60 [Hz]
- **Input Voltage**: U21 = 9 [V]

Resistors have the following resistance values:
- **R1** = 7.5 [Ω]
- **R2** = 15 [Ω]
- **R3** = 10 [Ω]
- **R4** = 12 [Ω]
- **R5** = 8.2 [Ω]
- **R6** = 22 [Ω]

![1.](Img/p1.jpg?raw=true "Title")

## Summary

The main goal of the project is to design and build a single-phase low-power transformer, a crucial device in managing and manipulating electrical energy. The transformer has two key functions: the first is to adjust the electrical voltage level—either to increase the voltage for efficient transmission over long distances or to decrease it for specific uses, such as powering a phone. The second function is to provide galvanic isolation between the primary (input) and secondary (output) circuits, ensuring user protection against electric shocks.

The transformer offers significant advantages due to its simple design, which provides high reliability and minimal electromagnetic emissions—an essential aspect compared to other power supplies that may generate disruptive electromagnetic interference.

Structurally, the low-power transformer consists of the following main components:

- **Electro-insulating case**: Provides protection against direct contact with electrical components and prevents accidents.
- **Windings**: Consist of conductor wire coils divided into primary and secondary windings, each with a specific role in the energy transformation process.
- **Ferromagnetic core**: The central element of the transformer through which the magnetic flux generated by the primary coil is efficiently transferred to the secondary coil.
- **Core clamping and transformer fastening system**: Ensures the structural stability of the transformer and maintains components in the correct position.

The operation of the transformer is based on the principle of electromagnetic induction. The electric current passing through the primary coil generates a magnetic field. Due to the transformer's configuration, this magnetic field traverses the ferromagnetic core and reaches the secondary coil. Depending on the number of turns and the intensity of the magnetic field, an electric voltage is induced in the secondary coil. This voltage can be higher or lower than the initial voltage, depending on the ratio between the number of turns in the primary and secondary windings.

Thus, the transformer is an essential tool in modern electrical energy distribution and utilization systems, serving as a clear example of efficient and safe engineering.

## General Aspects

**Transformer Usage:**
- Based on usage: Power, special construction (high intensity, multiple windings, phase changing, autotransformers, measurement, welding).
- Number of phases: Single-phase, poly-phase.
- Cooling: Air-cooled, oil-cooled (natural or forced).

**Main Components:**
- Electro-insulating case, windings, ferromagnetic core made of silicon steel sheets, core clamping and fastening system.

**Transformer Efficiency:**
- Depends on the quality and geometry of the magnetic core, the shape and size of the windings, and the conductor diameters.

**Technology and Design:**

**General Information:**
- Construction structure, manufacturing technology, and design methodology for single-phase low-power transformers (<500W) used in electronic equipment.

**Structure and Function:**
- The single-phase low-power transformer is used in many electronic power supply circuits, modifying voltage and current while providing galvanic isolation.

**Technological Manufacturing Process:**
- Obtaining steel sheets, heat treatment, case manufacturing.
- Winding the coils, inserting the sheets into the case.
- Clamping the magnetic core, transformer impregnation.
- Quality control inspection.

**Design Process:**
- Evaluating the total absorbed power, calculating the primary power.
- Dimensioning the magnetic core cross-section.
- Calculating the number of turns per volt, determining the number of turns for the primary and secondary windings.
- Evaluating the primary current, dimensioning the winding conductor diameters.
- Calculating the areas occupied by the windings, dimensioning the steel sheets and the sheet package thickness.

## Calculation and Dimensioning of the Assembly

Details on transformer dimensioning and component calculations will be presented in a subsequent chapter.

![2.](Img/p2.jpg?raw=true "Title")

![3.](Img/p3.jpg?raw=true "Title")

![4.](Img/p4.jpg?raw=true "Title")

## Resistor Selection

- **R1**: SMD resistor, 7.5 [Ω], 20 [W], tolerance ±5%
- **R2**: SMD resistor, 15 [Ω], 2 [W], tolerance ±5%
- **R3**: SMD resistor, 10 [Ω], 2 [W], tolerance ±5%
- **R4**: SMD resistor, 12 [Ω], 0.2 [W], tolerance ±0.5%
- **R5**: SMD resistor, 8.2 [Ω], 1.5 [W], tolerance ±5%
- **R6**: SMD resistor, 22 [Ω], 2 [W], tolerance ±1%

Components were selected from the [www.ro.farnell.com](http://www.ro.farnell.com) website, considering availability, price-performance ratio, rated power, and tolerance.

## Transformer Power Calculation and Dimensioning

Power calculation and assembly dimensioning will be presented further in the technical documentation of the project.

![5.](Img/p5.jpg?raw=true "Title")

![6.](Img/p6.jpg?raw=true "Title")

![7.](Img/p7.jpg?raw=true "Title")

![8.](Img/p8.jpg?raw=true "Title")

## Conclusions

The conclusion of this work highlights several important aspects of electrical engineering and the process of designing and constructing electrical circuits. Firstly, the paper emphasizes the importance of selecting appropriate circuit conditions and adhering to safety standards. Inadequate conditions or failure to follow safety norms can lead to circuit malfunctions or even accidents.

Secondly, it encourages students to become familiar with the process of building an electrical circuit, providing valuable practical learning and a deeper understanding of how electrical circuits operate.

Finally, the work underscores the necessity of adhering to technical standards when constructing transformers, such as the wire thickness for windings and whether to include insulation between layers. These technical details are essential for transformer performance and safety.

## Bibliography

1. Course materials from the "Passive Components and Circuits" discipline available on the Moodle platform.
2. [https://www.cetti.ro/v2/ccp.php](https://www.cetti.ro/v2/ccp.php) – Resources on "Fixed Linear Resistors."
3. [https://ro.farnell.com/](https://ro.farnell.com/) – Platform for sourcing SMD resistors.
4. [Wikipedia: Surface-mount technology](https://en.wikipedia.org/wiki/Surface-mount_technology) – Information on surface-mount technology.
