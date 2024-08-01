### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1242.8<br />
<br />
Final Rank Value (1242.8) = Starting Rank Value (1150.1) + Head To Head Adjustments (92.7)<br />

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
|           70 |      100 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.768 (0.384)    | 0 (0.000) |     5.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           69 |      154 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.292 (0.127)    | -                | 0 (0.000) |    20.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           68 |      170 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           67 |      192 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.168 (0.073)    | 0.878 (0.381)    | 0 (0.000) |    13.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      207 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.801 (0.348)    | 0 (0.000) |     4.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      321 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      424 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |   -10.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      559 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -16.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      573 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.878 (0.439)    | 0 (0.000) |    14.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      672 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      691 | 2024-07-15 | Rebels            | W   | 1.000      | 0.500        | -                | 0.635 (0.318)    | 0 (0.000) |     8.09 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           59 |     1111 | 2024-06-09 | KOI               | W   | 0.846      | -            | -                | -                | 0 (0.000) |     6.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |     1179 | 2024-06-08 | SINNERS           | W   | 0.840      | 0.500        | -                | 0.768 (0.323)    | -         |     7.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |     1239 | 2024-06-07 | Aurora            | W   | 0.833      | 0.500        | 0.431 (0.180)    | 0.798 (0.333)    | -         |    23.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |     1308 | 2024-06-06 | 3DMAX             | W   | 0.827      | 0.500        | 0.505 (0.209)    | 1.000 (0.413)    | -         |    23.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |     1371 | 2024-06-05 | SAW               | W   | 0.820      | 0.500        | 0.108 (0.044)    | -                | -         |    15.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1422 | 2024-06-04 | 9 Pandas          | W   | 0.813      | -            | -                | -                | -         |    11.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1536 | 2024-05-31 | SAW               | L   | 0.787      | -            | -                | -                | -         |    -8.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1539 | 2024-05-31 | FAVBET            | W   | 0.786      | -            | -                | -                | -         |     3.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1543 | 2024-05-31 | fnatic            | L   | 0.786      | -            | -                | -                | -         |    -5.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1571 | 2024-05-30 | MOUZ NXT          | L   | 0.778      | -            | -                | -                | -         |   -13.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1745 | 2024-05-22 | Zero Tenacity     | W   | 0.726      | 0.500        | 0.139 (0.050)    | 1.000 (0.363)    | -         |    10.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1807 | 2024-05-21 | Monte             | W   | 0.719      | -            | -                | -                | -         |     8.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1839 | 2024-05-20 | Passion UA        | L   | 0.713      | -            | -                | -                | -         |   -14.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1846 | 2024-05-20 | PARIVISION        | W   | 0.712      | -            | -                | -                | -         |    10.42 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1867 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.707      | 0.500        | 0.207 (0.073)    | -                | -         |    19.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1874 | 2024-05-19 | Endpoint          | W   | 0.706      | -            | -                | -                | -         |     7.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1910 | 2024-05-18 | Rare Atom         | W   | 0.699      | -            | -                | -                | -         |     1.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1952 | 2024-05-17 | Permitta          | W   | 0.691      | -            | -                | -                | -         |     5.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1965 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.687      | -            | -                | -                | -         |    -2.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2036 | 2024-05-15 | Verdant           | L   | 0.678      | -            | -                | -                | -         |   -15.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2102 | 2024-05-14 | DMS               | L   | 0.671      | -            | -                | -                | -         |   -15.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2353 | 2024-05-02 | Metizport         | L   | 0.593      | -            | -                | -                | -         |   -13.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2387 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.584      | -            | -                | -                | -         |   -13.34 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2398 | 2024-04-30 | Zero Tenacity     | W   | 0.579      | 0.500        | -                | 1.000 (0.290)    | -         |     7.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2430 | 2024-04-29 | SINNERS           | W   | 0.571      | -            | -                | -                | -         |     6.88 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2437 | 2024-04-28 | 1WIN              | W   | 0.567      | -            | -                | -                | -         |     4.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2461 | 2024-04-27 | PARIVISION        | L   | 0.559      | -            | -                | -                | -         |    -9.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2494 | 2024-04-26 | Nemiga            | W   | 0.552      | 0.435        | 0.324 (0.078)    | -                | -         |     9.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2569 | 2024-04-23 | Grannys Knockers  | W   | 0.531      | -            | -                | -                | -         |     2.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2575 | 2024-04-22 | BLEED             | L   | 0.526      | -            | -                | -                | -         |    -9.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2587 | 2024-04-22 | ex-Guild Eagles   | L   | 0.524      | -            | -                | -                | -         |   -13.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2602 | 2024-04-21 | Alliance          | W   | 0.518      | -            | -                | -                | -         |     3.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2623 | 2024-04-20 | brazylijski luz   | W   | 0.513      | -            | -                | -                | -         |     2.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2639 | 2024-04-20 | JANO              | W   | 0.511      | -            | -                | -                | -         |     1.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2659 | 2024-04-19 | TSM               | W   | 0.507      | -            | -                | -                | -         |     1.25 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2671 | 2024-04-19 | Nemiga            | L   | 0.506      | -            | -                | -                | -         |    -7.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2781 | 2024-04-17 | 9 Pandas          | W   | 0.491      | -            | -                | -                | -         |     4.94 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2793 | 2024-04-16 | Zero Tenacity     | W   | 0.487      | -            | -                | -                | -         |     6.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2815 | 2024-04-15 | B8                | W   | 0.480      | 0.500        | 0.168 (0.040)    | -                | -         |     6.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2819 | 2024-04-15 | Aurora Young Blud | W   | 0.479      | -            | -                | -                | -         |     2.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2860 | 2024-04-12 | Monte             | L   | 0.459      | -            | -                | -                | -         |    -9.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     3114 | 2024-04-04 | EYEBALLERS        | W   | 0.407      | -            | -                | -                | -         |     2.95 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     3205 | 2024-04-02 | 9 Pandas          | L   | 0.393      | -            | -                | -                | -         |    -8.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     3572 | 2024-03-13 | KOI               | L   | 0.261      | -            | -                | -                | -         |    -6.09 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           15 |     3682 | 2024-03-09 | Zero Tenacity     | L   | 0.233      | -            | -                | -                | -         |    -4.08 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           14 |     3731 | 2024-03-07 | 500               | L   | 0.219      | -            | -                | -                | -         |    -6.24 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     3751 | 2024-03-06 | TSM               | W   | 0.214      | -            | -                | -                | -         |     0.46 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3826 | 2024-03-04 | Sampi             | W   | 0.198      | -            | -                | -                | -         |     1.23 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3851 | 2024-03-03 | Rebels            | L   | 0.193      | -            | -                | -                | -         |    -4.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3879 | 2024-03-02 | HAVU              | W   | 0.185      | -            | -                | -                | -         |     0.47 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3901 | 2024-02-29 | Rebels            | L   | 0.173      | -            | -                | -                | -         |    -3.79 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3923 | 2024-02-28 | Alliance          | L   | 0.165      | -            | -                | -                | -         |    -4.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3930 | 2024-02-27 | 9INE              | W   | 0.161      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3978 | 2024-02-25 | Sashi             | W   | 0.147      | -            | -                | -                | -         |     2.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     4159 | 2024-02-18 | 500               | W   | 0.098      | -            | -                | -                | -         |     0.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     4350 | 2024-02-10 | brazylijski luz   | W   | 0.045      | -            | -                | -                | -         |     0.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4373 | 2024-02-08 | AURA              | L   | 0.033      | -            | -                | -                | -         |    -1.00 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4395 | 2024-02-06 | ex-Preasy         | L   | 0.018      | -            | -                | -                | -         |    -0.52 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4429 | 2024-02-04 | ALTERNATE aTTaX   | W   | 0.004      | -            | -                | -                | -         |     0.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,269.83)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.846 | $16,500.00     | $13,964.27      |
| 2024-05-22 |      0.726 | $50,000.00     | $36,305.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
