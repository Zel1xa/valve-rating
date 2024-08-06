### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, nitr0, oSee<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  989.3<br />
<br />
Final Rank Value (989.3) = Starting Rank Value (849.4) + Head To Head Adjustments (139.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.157[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.4
- 400 + ( ( 0.218 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 849.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |       65 | 2024-08-03 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | autimatic, Brehze, HexT, nitr0, oSee |
|           74 |      173 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.319 (0.152)    | 0 (0.000) |     8.34 | autimatic, Brehze, HexT, nitr0, oSee |
|           73 |      177 | 2024-07-31 | BOSS             | W   | 1.000      | 0.477        | 0.014 (0.007)    | 0.319 (0.152)    | 0 (0.000) |     8.95 | autimatic, Brehze, HexT, nitr0, oSee |
|           72 |      221 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -15.51 | autimatic, Brehze, HexT, nitr0, oSee |
|           71 |      225 | 2024-07-30 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -16.94 | autimatic, Brehze, HexT, nitr0, oSee |
|           70 |      514 | 2024-07-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -20.02 | autimatic, Brehze, HexT, nitr0, oSee |
|           69 |      518 | 2024-07-21 | Nouns            | W   | 1.000      | 0.303        | 0.057 (0.017)    | 0.541 (0.164)    | 0 (0.000) |    14.38 | autimatic, Brehze, HexT, nitr0, oSee |
|           68 |      544 | 2024-07-20 | BOSS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.77 | autimatic, Brehze, HexT, nitr0, oSee |
|           67 |      612 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     8.44 | autimatic, Brehze, HexT, nitr0, oSee |
|           66 |      616 | 2024-07-18 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     9.05 | autimatic, Brehze, HexT, nitr0, oSee |
|           65 |      678 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | autimatic, Brehze, HexT, nitr0, oSee |
|           64 |      683 | 2024-07-17 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.01 | autimatic, Brehze, HexT, nitr0, oSee |
|           63 |      740 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.304 (0.145)    | 0 (0.000) |     5.78 | autimatic, Brehze, HexT, nitr0, oSee |
|           62 |      745 | 2024-07-16 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.304 (0.145)    | -         |     6.10 | autimatic, Brehze, HexT, nitr0, oSee |
|           61 |      792 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     7.56 | autimatic, Brehze, HexT, nitr0, oSee |
|           60 |      795 | 2024-07-15 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     8.07 | autimatic, Brehze, HexT, nitr0, oSee |
|           59 |     1253 | 2024-06-09 | M80              | W   | 0.815      | 0.143        | 0.188 (0.022)    | -                | -         |    22.14 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     1325 | 2024-06-08 | Party Astronauts | W   | 0.808      | -            | -                | -                | -         |    15.48 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     1371 | 2024-06-07 | Party Astronauts | L   | 0.802      | -            | -                | -                | -         |    -9.90 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     1415 | 2024-06-06 | Party Astronauts | L   | 0.797      | -            | -                | -                | -         |   -11.02 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     1424 | 2024-06-06 | Wildcard         | W   | 0.796      | 0.143        | 0.048 (0.005)    | -                | -         |    13.97 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     1428 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.796      | -            | -                | -                | -         |     6.53 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     1449 | 2024-06-06 | Wildcard         | L   | 0.795      | -            | -                | -                | -         |   -10.77 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     1482 | 2024-06-05 | LAG              | W   | 0.790      | 0.477        | -                | 0.376 (0.142)    | -         |    10.03 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     1496 | 2024-06-05 | FLUFFY AIMERS    | W   | 0.788      | -            | -                | -                | -         |     6.85 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     1533 | 2024-06-04 | Nouns            | L   | 0.784      | -            | -                | -                | -         |    -9.51 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     1828 | 2024-05-23 | Nouns            | L   | 0.704      | -            | -                | -                | -         |    -9.12 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     1844 | 2024-05-22 | Elevate          | L   | 0.697      | -            | -                | -                | -         |    -8.67 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     1850 | 2024-05-22 | Elevate          | L   | 0.697      | -            | -                | -                | -         |    -9.20 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     1873 | 2024-05-22 | Legacy           | W   | 0.695      | 0.384        | 0.122 (0.032)    | 0.620 (0.166)    | -         |    13.63 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     1896 | 2024-05-21 | Phoenix          | L   | 0.690      | -            | -                | -                | -         |   -16.02 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     1898 | 2024-05-21 | Phoenix          | W   | 0.690      | -            | -                | -                | -         |     5.65 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     1929 | 2024-05-20 | M80              | L   | 0.684      | -            | -                | -                | -         |    -3.05 | autimatic, Brehze, HexT, oSee, Walco |
|           42 |     1933 | 2024-05-20 | M80              | L   | 0.684      | -            | -                | -                | -         |    -3.14 | autimatic, Brehze, HexT, oSee, Walco |
|           41 |     1992 | 2024-05-18 | Nouns            | L   | 0.670      | -            | -                | -                | -         |   -10.62 | autimatic, Brehze, HexT, oSee, Walco |
|           40 |     1997 | 2024-05-18 | Party Astronauts | W   | 0.669      | 0.303        | 0.041 (0.008)    | -                | -         |    10.55 | autimatic, Brehze, HexT, oSee, Walco |
|           39 |     2031 | 2024-05-17 | BOSS             | W   | 0.663      | -            | -                | -                | -         |     6.64 | autimatic, Brehze, HexT, oSee, Walco |
|           38 |     2100 | 2024-05-15 | LAG              | W   | 0.650      | -            | -                | -                | -         |     7.29 | autimatic, Brehze, HexT, oSee, Walco |
|           37 |     2107 | 2024-05-15 | LAG              | W   | 0.650      | -            | -                | -                | -         |     7.69 | autimatic, Brehze, HexT, oSee, Walco |
|           36 |     2152 | 2024-05-14 | Take Flyte       | W   | 0.644      | -            | -                | -                | -         |     4.95 | autimatic, Brehze, HexT, oSee, Walco |
|           35 |     2157 | 2024-05-14 | Take Flyte       | W   | 0.644      | -            | -                | -                | -         |     5.17 | autimatic, Brehze, HexT, oSee, Walco |
|           34 |     2222 | 2024-05-12 | Phoenix          | W   | 0.630      | -            | -                | -                | -         |     6.21 | autimatic, Brehze, HexT, oSee, Walco |
|           33 |     2224 | 2024-05-12 | Elevate          | W   | 0.629      | -            | -                | -                | -         |    12.58 | autimatic, Brehze, HexT, oSee, Walco |
|           32 |     2252 | 2024-05-11 | Phoenix          | W   | 0.622      | -            | -                | -                | -         |     6.19 | autimatic, Brehze, HexT, oSee, Walco |
|           31 |     2254 | 2024-05-11 | BOSS             | W   | 0.622      | -            | -                | -                | -         |     8.05 | autimatic, Brehze, HexT, oSee, Walco |
|           30 |     2358 | 2024-05-06 | Party Astronauts | W   | 0.590      | 0.477        | 0.041 (0.012)    | 0.510 (0.144)    | -         |    11.45 | autimatic, Brehze, HexT, oSee, Walco |
|           29 |     2359 | 2024-05-06 | Party Astronauts | L   | 0.590      | -            | -                | -                | -         |    -7.23 | autimatic, Brehze, HexT, oSee, Walco |
|           28 |     2595 | 2024-04-25 | Wildcard         | L   | 0.517      | -            | -                | -                | -         |    -7.87 | autimatic, Brehze, HexT, oSee, Walco |
|           27 |     2597 | 2024-04-25 | Wildcard         | W   | 0.517      | 0.477        | 0.048 (0.012)    | -                | -         |     8.62 | autimatic, Brehze, HexT, oSee, Walco |
|           26 |     2833 | 2024-04-17 | Akimbo           | L   | 0.463      | -            | -                | -                | -         |    -9.45 | autimatic, Brehze, HexT, oSee, Walco |
|           25 |     2892 | 2024-04-15 | Mythic           | W   | 0.450      | -            | -                | -                | -         |     5.12 | autimatic, Brehze, HexT, oSee, Walco |
|           24 |     2893 | 2024-04-15 | Mythic           | W   | 0.450      | -            | -                | -                | -         |     5.31 | autimatic, Brehze, HexT, oSee, Walco |
|           23 |     2980 | 2024-04-10 | BOSS             | W   | 0.417      | -            | -                | -                | -         |     5.99 | autimatic, Brehze, HexT, oSee, Walco |
|           22 |     2984 | 2024-04-10 | BOSS             | L   | 0.417      | -            | -                | -                | -         |    -7.32 | autimatic, Brehze, HexT, oSee, Walco |
|           21 |     3038 | 2024-04-09 | Carpe Diem       | W   | 0.410      | -            | -                | -                | -         |     3.27 | autimatic, Brehze, HexT, oSee, Walco |
|           20 |     3041 | 2024-04-09 | Carpe Diem       | W   | 0.410      | -            | -                | -                | -         |     3.36 | autimatic, Brehze, HexT, oSee, Walco |
|           19 |     3341 | 2024-03-27 | Nouns            | W   | 0.324      | 0.477        | 0.057 (0.009)    | -                | -         |     6.14 | autimatic, Brehze, HexT, oSee, Walco |
|           18 |     3345 | 2024-03-27 | Nouns            | L   | 0.324      | -            | -                | -                | -         |    -4.13 | autimatic, Brehze, HexT, oSee, Walco |
|           17 |     3393 | 2024-03-26 | MIGHT            | W   | 0.317      | -            | -                | -                | -         |     1.51 | autimatic, Brehze, HexT, oSee, Walco |
|           16 |     3398 | 2024-03-26 | MIGHT            | W   | 0.317      | -            | -                | -                | -         |     1.53 | autimatic, Brehze, HexT, oSee, Walco |
|           15 |     3564 | 2024-03-15 | FLUFFY AIMERS    | W   | 0.244      | -            | -                | -                | -         |     2.97 | autimatic, Brehze, HexT, oSee, Walco |
|           14 |     3566 | 2024-03-15 | FLUFFY AIMERS    | L   | 0.244      | -            | -                | -                | -         |    -4.79 | autimatic, Brehze, HexT, oSee, Walco |
|           13 |     3584 | 2024-03-14 | Limitless        | W   | 0.237      | -            | -                | -                | -         |     1.85 | autimatic, Brehze, HexT, oSee, Walco |
|           12 |     3588 | 2024-03-14 | Limitless        | W   | 0.237      | -            | -                | -                | -         |     1.88 | autimatic, Brehze, HexT, oSee, Walco |
|           11 |     3663 | 2024-03-12 | Carpe Diem       | L   | 0.224      | -            | -                | -                | -         |    -5.08 | autimatic, Brehze, HexT, oSee, Walco |
|           10 |     3918 | 2024-03-02 | MIBR             | L   | 0.155      | -            | -                | -                | -         |    -0.20 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     3937 | 2024-03-01 | Imperial         | L   | 0.149      | -            | -                | -                | -         |    -0.45 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     4043 | 2024-02-24 | Wildcard         | L   | 0.110      | -            | -                | -                | -         |    -1.63 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     4045 | 2024-02-24 | Limitless        | W   | 0.110      | -            | -                | -                | -         |     0.87 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     4051 | 2024-02-24 | Mythic           | W   | 0.110      | -            | -                | -                | -         |     1.45 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     4087 | 2024-02-22 | Party Astronauts | L   | 0.097      | -            | -                | -                | -         |    -1.22 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     4092 | 2024-02-22 | Wildcard         | W   | 0.096      | -            | -                | -                | -         |     1.62 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     4140 | 2024-02-20 | Party Astronauts | L   | 0.084      | -            | -                | -                | -         |    -1.06 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     4165 | 2024-02-19 | Party Astronauts | W   | 0.077      | -            | -                | -                | -         |     1.46 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     4167 | 2024-02-19 | Mythic           | W   | 0.076      | -            | -                | -                | -         |     1.01 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,400.12)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.817 | $4,250.00      | $3,470.44       |
| 2024-05-18 |      0.670 | $1,000.00      | $670.09         |
| 2024-05-12 |      0.630 | $2,000.00      | $1,259.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
