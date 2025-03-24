# Data Wrangling Assessment
Below you can see the task provided by the company in both [English](#L4) and [Spanish](). Just note that the data sample provided is available only in Spanish.

## Introduction
As part of an assessment by a local company, I was tasked with transforming an SPSS database file into a more analysis-friendly format.

<ins>SPSS database sample</ins>:

| responseID | FF2 | FF3 | FF4 | FF5_1 | FF7 | FF7_1 | FF7_2 | FF7_3 | FF7_4 | FF7_5 | FF7_6 | FF7_7 | FF7_8 | A2_1 | A2_2 | A3_1 | A3_2 | A9_1.Banco.1 | A9_2.Banco.2 | A9_3.Banco.3 | A9_4.Banco.4 | A9_5.Banco.5 | A9_6.Banco.6 | A9_7.Banco.7 | A9_9.Banco.9 | A9_10.Banco.10 | A9_13.Banco.13 | A9_15.Banco.15 | A9_16.Banco.16 | A9_17.Banco.17 | A9_20.Banco.20 | A9_24.Banco.24 | A9_25.Banco.25 | A9_29.Banco.29 | A9_42.Banco.42 | A9_71.Banco.71 | A9_84.Banco.84 | A9_74.Banco.74 | A9_44.Banco.44 | A9_90.Banco.90 | A9_91.Banco.91 | A10 | A13_1.Banco.1 | A13_2.Banco.2 | A13_3.Banco.3 | A13_4.Banco.4 | A13_5.Banco.5 | A13_6.Banco.6 | A13_7.Banco.7 | A13_9.Banco.9 | A13_10.Banco.10 | A13_13.Banco.13 | A13_15.Banco.15 | A13_16.Banco.16 | A13_17.Banco.17 | A13_20.Banco.20 | A13_24.Banco.24 | A13_25.Banco.25 | A13_29.Banco.29 | A13_42.Banco.42 | A13_71.Banco.71 | A13_84.Banco.84 | A13_74.Banco.74 | A13_44.Banco.44 | A13_90.Banco.90 | A13_91.Banco.91 |																																																																		
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |																																																																		
| 56020150 | SI | SI. Duenoo o Socio/ Gerente/ Contador | Servicios no Profesionales | ENTRE $ 600.001 Y $ 1.000.000 | AMBA | GBA SUR |  |  |  |  |  |  |  | Banco.90 | Banco.15 | NS/NC |  |  |  |  |  |  |  |  |  |  |  | Banco.15 |  |  |  |  |  |  |  |  |  |  |  | Banco.90 |  | Banco.15 |  |  |  |  |  |  |  |  |  |  | 8 |  |  |  |  |  |  |  |  |  |  |  | 10 |  |																																																																		
| 56024025 | SI | SI. Duenoo o Socio/ Gerente/ Contador | Servicios  Profesionales | ENTRE $ 600.001 Y $ 1.000.000 | AMBA | GBA NORTE |  |  |  |  |  |  |  | Banco.3 | Banco.2 | Banco.7 | Banco.1 |  | Banco.2 | Banco.3 |  |  |  |  |  |  | Banco.13 |  |  |  |  |  |  |  |  |  |  |  |  | Banco.90 |  | Banco.2 |  | 10 | 10 |  |  |  |  |  |  | 8 |  |  |  |  |  |  |  |  |  |  |  |  | 10 |  |																																																																		
| 54638665 | SI | SI. Duenoo o Socio/ Gerente/ Contador | Servicios  Profesionales | ENTRE $ 1.000.001 Y $ 2.000.000 | AMBA | CABA NORTE |  |  |  |  |  |  |  | NS/NC |  | NS/NC |  |  |  | Banco.3 |  |  |  | Banco.7 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Banco.3 |  |  | NS/NC |  |  |  | NS/NC |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |																																																																		



