### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1266.4<br />
<br />
Final Rank Value (1266.4) = Starting Rank Value (1151.6) + Head To Head Adjustments (114.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.354[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.364<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.6
- 400 + ( ( 0.364 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1151.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |       67 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.721 (0.360)    | 0 (0.000) |     4.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           69 |      121 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | -                | 0 (0.000) |    24.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           68 |      137 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           67 |      159 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.167 (0.073)    | 0.879 (0.382)    | 0 (0.000) |    13.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      173 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.799 (0.347)    | 0 (0.000) |     4.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      288 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      388 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      517 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -16.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      531 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.167 (0.083)    | 0.879 (0.440)    | 0 (0.000) |    13.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      625 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      642 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | -                | 0.596 (0.298)    | 0 (0.000) |     8.22 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           59 |     1070 | 2024-06-09 | KOI               | W   | 0.852      | -            | -                | -                | 0 (0.000) |     9.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |     1136 | 2024-06-08 | SINNERS           | W   | 0.846      | 0.500        | -                | 0.721 (0.305)    | -         |     6.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |     1189 | 2024-06-07 | Aurora            | W   | 0.839      | 0.500        | 0.429 (0.180)    | 0.800 (0.335)    | -         |    23.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |     1256 | 2024-06-06 | 3DMAX             | W   | 0.832      | 0.500        | 0.499 (0.208)    | 1.000 (0.416)    | -         |    23.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |     1316 | 2024-06-05 | SAW               | W   | 0.826      | 0.500        | 0.107 (0.044)    | -                | -         |    15.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1367 | 2024-06-04 | 9 Pandas          | W   | 0.819      | -            | -                | -                | -         |    11.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1480 | 2024-05-31 | SAW               | L   | 0.792      | -            | -                | -                | -         |    -8.85 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1483 | 2024-05-31 | FAVBET            | W   | 0.792      | -            | -                | -                | -         |     3.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1487 | 2024-05-31 | fnatic            | L   | 0.791      | -            | -                | -                | -         |    -2.94 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1515 | 2024-05-30 | MOUZ NXT          | L   | 0.784      | -            | -                | -                | -         |   -14.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1687 | 2024-05-22 | Zero Tenacity     | W   | 0.732      | 0.500        | 0.138 (0.050)    | 1.000 (0.366)    | -         |    11.03 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1734 | 2024-05-21 | Monte             | W   | 0.724      | -            | -                | -                | -         |     8.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1769 | 2024-05-20 | PARIVISION        | W   | 0.718      | -            | -                | -                | -         |    10.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1784 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.713      | 0.500        | 0.256 (0.091)    | -                | -         |    20.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1791 | 2024-05-19 | Endpoint          | W   | 0.711      | -            | -                | -                | -         |     6.88 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1826 | 2024-05-18 | Rare Atom         | W   | 0.704      | -            | -                | -                | -         |     1.83 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1868 | 2024-05-17 | Permitta          | W   | 0.697      | -            | -                | -                | -         |     5.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1881 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.693      | -            | -                | -                | -         |    -1.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1948 | 2024-05-15 | Verdant           | L   | 0.684      | -            | -                | -                | -         |   -15.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2011 | 2024-05-14 | DMS               | L   | 0.677      | -            | -                | -                | -         |   -15.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2257 | 2024-05-02 | Metizport         | L   | 0.598      | -            | -                | -                | -         |   -13.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2290 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.590      | -            | -                | -                | -         |   -13.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2300 | 2024-04-30 | Zero Tenacity     | W   | 0.585      | 0.500        | -                | 1.000 (0.293)    | -         |     7.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2332 | 2024-04-29 | SINNERS           | W   | 0.577      | -            | -                | -                | -         |     6.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2339 | 2024-04-28 | 1WIN              | W   | 0.572      | -            | -                | -                | -         |     4.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2363 | 2024-04-27 | PARIVISION        | L   | 0.565      | -            | -                | -                | -         |   -10.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2397 | 2024-04-26 | Nemiga            | W   | 0.558      | 0.435        | 0.322 (0.078)    | -                | -         |    10.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2469 | 2024-04-23 | Grannys Knockers  | W   | 0.537      | -            | -                | -                | -         |     2.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2474 | 2024-04-22 | BLEED             | L   | 0.532      | -            | -                | -                | -         |    -9.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2485 | 2024-04-22 | ex-Guild Eagles   | L   | 0.530      | -            | -                | -                | -         |   -13.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2500 | 2024-04-21 | Alliance          | W   | 0.524      | -            | -                | -                | -         |     2.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2519 | 2024-04-20 | brazylijski luz   | W   | 0.519      | -            | -                | -                | -         |     2.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2535 | 2024-04-20 | JANO              | W   | 0.517      | -            | -                | -                | -         |     1.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2554 | 2024-04-19 | TSM               | W   | 0.513      | -            | -                | -                | -         |     1.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2566 | 2024-04-19 | Nemiga            | L   | 0.512      | -            | -                | -                | -         |    -7.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2674 | 2024-04-17 | 9 Pandas          | W   | 0.497      | -            | -                | -                | -         |     5.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2686 | 2024-04-16 | Zero Tenacity     | W   | 0.492      | -            | -                | -                | -         |     6.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2707 | 2024-04-15 | B8                | W   | 0.486      | 0.500        | 0.167 (0.041)    | -                | -         |     6.38 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2711 | 2024-04-15 | Aurora Young Blud | W   | 0.485      | -            | -                | -                | -         |     2.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2752 | 2024-04-12 | Monte             | L   | 0.465      | -            | -                | -                | -         |    -9.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     3005 | 2024-04-04 | EYEBALLERS        | W   | 0.413      | -            | -                | -                | -         |     3.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     3088 | 2024-04-02 | 9 Pandas          | L   | 0.399      | -            | -                | -                | -         |    -8.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     3445 | 2024-03-13 | KOI               | L   | 0.266      | -            | -                | -                | -         |    -4.57 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           16 |     3554 | 2024-03-09 | Zero Tenacity     | L   | 0.238      | -            | -                | -                | -         |    -4.12 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           15 |     3603 | 2024-03-07 | 500               | L   | 0.225      | -            | -                | -                | -         |    -6.47 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           14 |     3623 | 2024-03-06 | TSM               | W   | 0.220      | -            | -                | -                | -         |     0.48 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     3693 | 2024-03-04 | Sampi             | W   | 0.204      | -            | -                | -                | -         |     1.26 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3719 | 2024-03-03 | Rebels            | L   | 0.199      | -            | -                | -                | -         |    -4.30 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3746 | 2024-03-02 | HAVU              | W   | 0.190      | -            | -                | -                | -         |     0.49 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3767 | 2024-02-29 | Rebels            | L   | 0.179      | -            | -                | -                | -         |    -3.92 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3788 | 2024-02-28 | Alliance          | L   | 0.171      | -            | -                | -                | -         |    -4.53 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3795 | 2024-02-27 | 9INE              | W   | 0.166      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3841 | 2024-02-25 | Sashi             | W   | 0.153      | -            | -                | -                | -         |     2.51 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     4017 | 2024-02-18 | 500               | W   | 0.104      | -            | -                | -                | -         |     0.25 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     4220 | 2024-02-08 | AURA              | L   | 0.038      | -            | -                | -                | -         |    -1.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     4242 | 2024-02-06 | ex-Preasy         | L   | 0.024      | -            | -                | -                | -         |    -0.67 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4276 | 2024-02-04 | ALTERNATE aTTaX   | W   | 0.010      | -            | -                | -                | -         |     0.10 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4297 | 2024-02-03 | Entropiq          | L   | 0.005      | -            | -                | -                | -         |    -0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4305 | 2024-02-03 | Metizport         | L   | 0.004      | -            | -                | -                | -         |    -0.09 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,650.66)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.852 | $16,500.00     | $14,058.76      |
| 2024-05-22 |      0.732 | $50,000.00     | $36,591.90      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
