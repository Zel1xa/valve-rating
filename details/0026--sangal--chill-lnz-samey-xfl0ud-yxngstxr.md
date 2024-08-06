### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1284.3<br />
<br />
Final Rank Value (1284.3) = Starting Rank Value (1161.1) + Head To Head Adjustments (123.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.376[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1161.1
- 400 + ( ( 0.370 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1161.1


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
|           68 |       29 | 2024-08-05 | 1WIN              | W   | 1.000      | 0.435        | -                | 0.718 (0.312)    | 0 (0.000) |     5.76 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       85 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      254 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.790 (0.395)    | 0 (0.000) |     5.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      308 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | -                | 0 (0.000) |    23.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      324 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      346 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.170 (0.074)    | 0.912 (0.396)    | 0 (0.000) |    12.82 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      360 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.919 (0.399)    | 0 (0.000) |     4.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      475 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      575 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.03 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      704 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      718 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | 0 (0.000) |    13.44 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      812 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      829 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.86 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1257 | 2024-06-09 | KOI               | W   | 0.814      | -            | -                | -                | -         |     8.25 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1323 | 2024-06-08 | SINNERS           | W   | 0.808      | 0.500        | -                | 0.790 (0.319)    | -         |     7.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1376 | 2024-06-07 | Aurora            | W   | 0.801      | 0.500        | 0.420 (0.168)    | 0.759 (0.304)    | -         |    21.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1443 | 2024-06-06 | 3DMAX             | W   | 0.795      | 0.500        | 0.510 (0.202)    | 1.000 (0.397)    | -         |    22.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1503 | 2024-06-05 | SAW               | W   | 0.788      | 0.500        | 0.104 (0.041)    | -                | -         |    13.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1554 | 2024-06-04 | 9 Pandas          | W   | 0.781      | -            | -                | -                | -         |    10.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1667 | 2024-05-31 | SAW               | L   | 0.755      | -            | -                | -                | -         |    -9.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1670 | 2024-05-31 | FAVBET            | W   | 0.754      | -            | -                | -                | -         |     3.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1674 | 2024-05-31 | fnatic            | L   | 0.754      | -            | -                | -                | -         |    -3.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1702 | 2024-05-30 | MOUZ NXT          | L   | 0.746      | -            | -                | -                | -         |   -13.80 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1874 | 2024-05-22 | Zero Tenacity     | W   | 0.694      | 0.500        | 0.143 (0.050)    | 1.000 (0.347)    | -         |    10.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1921 | 2024-05-21 | Monte             | W   | 0.687      | -            | -                | -                | -         |     7.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1956 | 2024-05-20 | PARIVISION        | W   | 0.680      | -            | -                | -                | -         |     9.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1971 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.675      | 0.500        | 0.254 (0.086)    | -                | -         |    19.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1978 | 2024-05-19 | Endpoint          | W   | 0.674      | -            | -                | -                | -         |     6.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2013 | 2024-05-18 | Rare Atom         | W   | 0.667      | -            | -                | -                | -         |     4.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2055 | 2024-05-17 | Permitta          | W   | 0.659      | -            | -                | -                | -         |     5.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2068 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.655      | -            | -                | -                | -         |    -1.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2135 | 2024-05-15 | Verdant           | L   | 0.646      | -            | -                | -                | -         |   -14.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2198 | 2024-05-14 | DMS               | L   | 0.639      | -            | -                | -                | -         |   -15.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2444 | 2024-05-02 | Metizport         | L   | 0.560      | -            | -                | -                | -         |   -13.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2477 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.552      | -            | -                | -                | -         |   -12.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2487 | 2024-04-30 | Zero Tenacity     | W   | 0.547      | -            | -                | -                | -         |     6.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2519 | 2024-04-29 | SINNERS           | W   | 0.539      | -            | -                | -                | -         |     7.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2526 | 2024-04-28 | 1WIN              | W   | 0.535      | -            | -                | -                | -         |     4.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2550 | 2024-04-27 | PARIVISION        | L   | 0.527      | -            | -                | -                | -         |    -9.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2584 | 2024-04-26 | Nemiga            | W   | 0.520      | 0.435        | 0.314 (0.071)    | -                | -         |     9.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2656 | 2024-04-23 | Grannys Knockers  | W   | 0.499      | -            | -                | -                | -         |     1.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2661 | 2024-04-22 | BLEED             | L   | 0.494      | -            | -                | -                | -         |    -9.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2672 | 2024-04-22 | ex-Guild Eagles   | L   | 0.492      | -            | -                | -                | -         |   -13.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2687 | 2024-04-21 | Alliance          | W   | 0.486      | -            | -                | -                | -         |     2.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2706 | 2024-04-20 | brazylijski luz   | W   | 0.481      | -            | -                | -                | -         |     2.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2722 | 2024-04-20 | JANO              | W   | 0.479      | -            | -                | -                | -         |     1.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2741 | 2024-04-19 | TSM               | W   | 0.475      | -            | -                | -                | -         |     1.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2753 | 2024-04-19 | Nemiga            | L   | 0.474      | -            | -                | -                | -         |    -7.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2861 | 2024-04-17 | 9 Pandas          | W   | 0.459      | -            | -                | -                | -         |     4.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2873 | 2024-04-16 | Zero Tenacity     | W   | 0.455      | -            | -                | -                | -         |     5.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2894 | 2024-04-15 | B8                | W   | 0.448      | -            | -                | -                | -         |     5.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2898 | 2024-04-15 | Aurora Young Blud | W   | 0.447      | -            | -                | -                | -         |     3.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2939 | 2024-04-12 | Monte             | L   | 0.427      | -            | -                | -                | -         |    -9.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3192 | 2024-04-04 | EYEBALLERS        | W   | 0.375      | -            | -                | -                | -         |     2.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3275 | 2024-04-02 | 9 Pandas          | L   | 0.361      | -            | -                | -                | -         |    -7.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3632 | 2024-03-13 | KOI               | L   | 0.229      | -            | -                | -                | -         |    -4.28 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3741 | 2024-03-09 | Zero Tenacity     | L   | 0.200      | -            | -                | -                | -         |    -3.59 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3790 | 2024-03-07 | 500               | L   | 0.187      | -            | -                | -                | -         |    -5.44 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3810 | 2024-03-06 | TSM               | W   | 0.182      | -            | -                | -                | -         |     0.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3880 | 2024-03-04 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     0.94 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3906 | 2024-03-03 | Rebels            | L   | 0.161      | -            | -                | -                | -         |    -3.61 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3933 | 2024-03-02 | HAVU              | W   | 0.153      | -            | -                | -                | -         |     0.35 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3954 | 2024-02-29 | Rebels            | L   | 0.141      | -            | -                | -                | -         |    -3.19 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3975 | 2024-02-28 | Alliance          | L   | 0.133      | -            | -                | -                | -         |    -3.56 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3982 | 2024-02-27 | 9INE              | W   | 0.129      | -            | -                | -                | -         |     0.11 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4028 | 2024-02-25 | Sashi             | W   | 0.115      | -            | -                | -                | -         |     1.78 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4204 | 2024-02-18 | 500               | W   | 0.066      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4407 | 2024-02-08 | AURA              | L   | 0.001      | -            | -                | -                | -         |    -0.02 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,139.36)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.814 | $16,500.00     | $13,435.66      |
| 2024-05-22 |      0.694 | $50,000.00     | $34,703.70      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
