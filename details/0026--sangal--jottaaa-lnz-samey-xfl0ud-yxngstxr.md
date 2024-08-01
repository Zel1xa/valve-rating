### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1243.1<br />
<br />
Final Rank Value (1243.1) = Starting Rank Value (1150.1) + Head To Head Adjustments (92.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.604[<sup>1</sup>](#table2)
- Bounty Collected: 0.495[<sup>2</sup>](#table1)
- Opponent Network: 0.359[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1150.1
- 400 + ( ( 0.365 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1150.1


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
|           70 |      103 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.768 (0.384)    | 0 (0.000) |     5.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           69 |      156 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.292 (0.127)    | -                | 0 (0.000) |    20.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           68 |      172 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           67 |      194 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.168 (0.073)    | 0.878 (0.381)    | 0 (0.000) |    13.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      208 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.801 (0.348)    | 0 (0.000) |     4.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      323 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      426 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |   -10.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      561 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -16.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      575 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.878 (0.439)    | 0 (0.000) |    14.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      675 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      693 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | -                | 0.635 (0.318)    | 0 (0.000) |     8.08 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           59 |     1113 | 2024-06-09 | KOI               | W   | 0.846      | -            | -                | -                | 0 (0.000) |     6.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |     1181 | 2024-06-08 | SINNERS           | W   | 0.840      | 0.500        | -                | 0.768 (0.323)    | -         |     7.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |     1241 | 2024-06-07 | Aurora            | W   | 0.833      | 0.500        | 0.431 (0.180)    | 0.798 (0.332)    | -         |    23.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |     1310 | 2024-06-06 | 3DMAX             | W   | 0.826      | 0.500        | 0.505 (0.209)    | 1.000 (0.413)    | -         |    23.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |     1373 | 2024-06-05 | SAW               | W   | 0.820      | 0.500        | 0.108 (0.044)    | -                | -         |    15.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1424 | 2024-06-04 | 9 Pandas          | W   | 0.813      | -            | -                | -                | -         |    11.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1538 | 2024-05-31 | SAW               | L   | 0.786      | -            | -                | -                | -         |    -8.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1541 | 2024-05-31 | FAVBET            | W   | 0.786      | -            | -                | -                | -         |     3.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1545 | 2024-05-31 | fnatic            | L   | 0.785      | -            | -                | -                | -         |    -5.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1573 | 2024-05-30 | MOUZ NXT          | L   | 0.777      | -            | -                | -                | -         |   -13.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1747 | 2024-05-22 | Zero Tenacity     | W   | 0.726      | 0.500        | 0.139 (0.050)    | 1.000 (0.363)    | -         |    10.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1809 | 2024-05-21 | Monte             | W   | 0.718      | -            | -                | -                | -         |     8.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1841 | 2024-05-20 | Passion UA        | L   | 0.713      | -            | -                | -                | -         |   -14.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1848 | 2024-05-20 | PARIVISION        | W   | 0.712      | -            | -                | -                | -         |    10.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1869 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.707      | 0.500        | 0.207 (0.073)    | -                | -         |    19.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1876 | 2024-05-19 | Endpoint          | W   | 0.705      | -            | -                | -                | -         |     7.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1912 | 2024-05-18 | Rare Atom         | W   | 0.698      | -            | -                | -                | -         |     1.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1954 | 2024-05-17 | Permitta          | W   | 0.691      | -            | -                | -                | -         |     5.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1967 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.687      | -            | -                | -                | -         |    -2.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2038 | 2024-05-15 | Verdant           | L   | 0.678      | -            | -                | -                | -         |   -15.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2104 | 2024-05-14 | DMS               | L   | 0.671      | -            | -                | -                | -         |   -15.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2355 | 2024-05-02 | Metizport         | L   | 0.592      | -            | -                | -                | -         |   -13.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2389 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.584      | -            | -                | -                | -         |   -13.34 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2400 | 2024-04-30 | Zero Tenacity     | W   | 0.579      | 0.500        | -                | 1.000 (0.290)    | -         |     7.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2432 | 2024-04-29 | SINNERS           | W   | 0.571      | -            | -                | -                | -         |     6.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2439 | 2024-04-28 | 1WIN              | W   | 0.566      | -            | -                | -                | -         |     4.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2463 | 2024-04-27 | PARIVISION        | L   | 0.559      | -            | -                | -                | -         |    -9.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2496 | 2024-04-26 | Nemiga            | W   | 0.552      | 0.435        | 0.324 (0.078)    | -                | -         |     9.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2571 | 2024-04-23 | Grannys Knockers  | W   | 0.531      | -            | -                | -                | -         |     2.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2577 | 2024-04-22 | BLEED             | L   | 0.526      | -            | -                | -                | -         |    -9.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2589 | 2024-04-22 | ex-Guild Eagles   | L   | 0.524      | -            | -                | -                | -         |   -13.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2604 | 2024-04-21 | Alliance          | W   | 0.517      | -            | -                | -                | -         |     3.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2625 | 2024-04-20 | brazylijski luz   | W   | 0.513      | -            | -                | -                | -         |     2.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2641 | 2024-04-20 | JANO              | W   | 0.511      | -            | -                | -                | -         |     1.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2661 | 2024-04-19 | TSM               | W   | 0.507      | -            | -                | -                | -         |     1.25 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2673 | 2024-04-19 | Nemiga            | L   | 0.506      | -            | -                | -                | -         |    -7.30 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2783 | 2024-04-17 | 9 Pandas          | W   | 0.491      | -            | -                | -                | -         |     4.95 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2795 | 2024-04-16 | Zero Tenacity     | W   | 0.486      | -            | -                | -                | -         |     6.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2817 | 2024-04-15 | B8                | W   | 0.480      | 0.500        | 0.168 (0.040)    | -                | -         |     6.30 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2821 | 2024-04-15 | Aurora Young Blud | W   | 0.479      | -            | -                | -                | -         |     2.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2862 | 2024-04-12 | Monte             | L   | 0.459      | -            | -                | -                | -         |    -9.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     3116 | 2024-04-04 | EYEBALLERS        | W   | 0.407      | -            | -                | -                | -         |     2.95 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     3207 | 2024-04-02 | 9 Pandas          | L   | 0.393      | -            | -                | -                | -         |    -8.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     3574 | 2024-03-13 | KOI               | L   | 0.260      | -            | -                | -                | -         |    -6.09 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           15 |     3684 | 2024-03-09 | Zero Tenacity     | L   | 0.232      | -            | -                | -                | -         |    -4.07 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           14 |     3733 | 2024-03-07 | 500               | L   | 0.219      | -            | -                | -                | -         |    -6.24 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     3753 | 2024-03-06 | TSM               | W   | 0.214      | -            | -                | -                | -         |     0.46 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3828 | 2024-03-04 | Sampi             | W   | 0.198      | -            | -                | -                | -         |     1.23 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3853 | 2024-03-03 | Rebels            | L   | 0.193      | -            | -                | -                | -         |    -4.17 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3881 | 2024-03-02 | HAVU              | W   | 0.184      | -            | -                | -                | -         |     0.47 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3903 | 2024-02-29 | Rebels            | L   | 0.173      | -            | -                | -                | -         |    -3.78 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3925 | 2024-02-28 | Alliance          | L   | 0.165      | -            | -                | -                | -         |    -4.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3932 | 2024-02-27 | 9INE              | W   | 0.160      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3980 | 2024-02-25 | Sashi             | W   | 0.147      | -            | -                | -                | -         |     2.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     4161 | 2024-02-18 | 500               | W   | 0.098      | -            | -                | -                | -         |     0.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     4352 | 2024-02-10 | brazylijski luz   | W   | 0.045      | -            | -                | -                | -         |     0.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4375 | 2024-02-08 | AURA              | L   | 0.032      | -            | -                | -                | -         |    -0.99 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4397 | 2024-02-06 | ex-Preasy         | L   | 0.018      | -            | -                | -                | -         |    -0.51 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4431 | 2024-02-04 | ALTERNATE aTTaX   | W   | 0.004      | -            | -                | -                | -         |     0.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,251.35)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.846 | $16,500.00     | $13,959.69      |
| 2024-05-22 |      0.726 | $50,000.00     | $36,291.67      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
