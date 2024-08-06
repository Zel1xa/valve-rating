### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1417.5<br />
<br />
Final Rank Value (1417.5) = Starting Rank Value (1417.1) + Head To Head Adjustments (0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.546[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.554[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1417.1
- 400 + ( ( 0.494 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1417.1


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
|           64 |     1392 | 2024-06-07 | Astralis          | L   | 0.801      | -            | -                | -                | -         |    -3.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1447 | 2024-06-06 | Eternal Fire      | W   | 0.795      | 0.715        | 0.739 (0.420)    | 0.438 (0.249)    | 1 (0.795) |    19.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1458 | 2024-06-06 | Complexity        | W   | 0.794      | 0.715        | 0.341 (0.194)    | 0.364 (0.207)    | 1 (0.794) |    20.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1492 | 2024-06-05 | BIG               | W   | 0.789      | 0.715        | 0.154 (0.087)    | -                | 1 (0.789) |    10.79 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1507 | 2024-06-05 | FURIA             | L   | 0.788      | -            | -                | -                | -         |    -6.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1516 | 2024-06-05 | fnatic            | W   | 0.787      | 0.715        | 0.371 (0.209)    | 0.680 (0.383)    | 1 (0.787) |    14.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1799 | 2024-05-25 | B8                | L   | 0.714      | -            | -                | -                | -         |   -17.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1824 | 2024-05-24 | DMS               | W   | 0.706      | -            | -                | -                | 0 (0.000) |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1914 | 2024-05-21 | Eternal Fire      | L   | 0.688      | -            | -                | -                | -         |    -3.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1942 | 2024-05-20 | MIBR              | W   | 0.682      | 0.769        | 0.208 (0.109)    | 0.633 (0.332)    | -         |    12.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1948 | 2024-05-20 | Astralis          | L   | 0.681      | -            | -                | -                | -         |    -2.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1962 | 2024-05-20 | MIBR              | W   | 0.679      | 0.769        | 0.208 (0.108)    | 0.633 (0.331)    | -         |    13.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2124 | 2024-05-15 | Falcons           | L   | 0.648      | -            | -                | -                | -         |    -9.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2189 | 2024-05-14 | MOUZ              | L   | 0.640      | -            | -                | -                | -         |    -1.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2231 | 2024-05-12 | B8                | L   | 0.628      | -            | -                | -                | -         |   -16.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2235 | 2024-05-12 | 9 Pandas          | W   | 0.627      | 0.435        | -                | 0.700 (0.191)    | -         |     2.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2268 | 2024-05-11 | Metizport         | W   | 0.620      | -            | -                | -                | -         |     1.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2285 | 2024-05-10 | Enterprise        | W   | 0.614      | 0.435        | -                | 0.641 (0.171)    | -         |     1.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2345 | 2024-05-07 | FlyQuest          | L   | 0.594      | -            | -                | -                | -         |   -14.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2396 | 2024-05-04 | AMKAL             | L   | 0.575      | -            | -                | -                | -         |   -14.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2401 | 2024-05-04 | 9 Pandas          | W   | 0.574      | 0.435        | -                | 0.700 (0.175)    | -         |     1.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2424 | 2024-05-03 | Insilio           | W   | 0.566      | -            | -                | -                | -         |     1.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2465 | 2024-05-01 | EYEBALLERS        | W   | 0.554      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2495 | 2024-04-30 | 3DMAX             | L   | 0.547      | -            | -                | -                | -         |    -3.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2569 | 2024-04-26 | M80               | W   | 0.522      | 0.889        | 0.188 (0.087)    | 0.563 (0.261)    | 1 (0.522) |     4.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2583 | 2024-04-26 | Falcons           | W   | 0.520      | 0.889        | 0.220 (0.102)    | -                | 1 (0.520) |     8.44 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2606 | 2024-04-25 | Vitality          | L   | 0.514      | -            | -                | -                | -         |    -1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2638 | 2024-04-23 | M80               | W   | 0.502      | 0.889        | 0.188 (0.084)    | 0.563 (0.251)    | 1 (0.502) |     4.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2747 | 2024-04-19 | Cloud9            | L   | 0.475      | -            | -                | -                | -         |   -13.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2758 | 2024-04-19 | Eternal Fire      | L   | 0.474      | -            | -                | -                | -         |    -2.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2782 | 2024-04-18 | Apeks             | W   | 0.469      | -            | -                | -                | -         |     1.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2786 | 2024-04-18 | brazylijski luz   | W   | 0.468      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2793 | 2024-04-18 | Serbia            | W   | 0.468      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2912 | 2024-04-14 | 3DMAX             | W   | 0.441      | 0.358        | 0.510 (0.080)    | -                | -         |    10.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2918 | 2024-04-13 | OG                | L   | 0.435      | -            | -                | -                | -         |   -12.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2922 | 2024-04-13 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -2.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2930 | 2024-04-13 | Sampi             | W   | 0.433      | -            | -                | -                | -         |     0.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2957 | 2024-04-11 | Aurora            | L   | 0.422      | -            | -                | -                | -         |    -2.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2965 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.421      | -            | -                | -                | -         |    10.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2971 | 2024-04-11 | AMKAL             | L   | 0.420      | -            | -                | -                | -         |   -10.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     3010 | 2024-04-10 | Aurora            | W   | 0.414      | -            | -                | -                | -         |    10.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3069 | 2024-04-09 | BIG               | W   | 0.407      | -            | -                | -                | -         |     4.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3141 | 2024-04-06 | Alliance          | W   | 0.387      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3155 | 2024-04-05 | BLEED             | W   | 0.382      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3191 | 2024-04-04 | Alliance          | W   | 0.375      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3204 | 2024-04-04 | BLEED             | W   | 0.374      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3374 | 2024-03-27 | FAVBET            | L   | 0.322      | -            | -                | -                | -         |    -9.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3412 | 2024-03-24 | FORZE             | L   | 0.300      | -            | -                | -                | -         |    -8.90 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3426 | 2024-03-23 | fnatic            | W   | 0.293      | -            | -                | -                | -         |     6.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3468 | 2024-03-21 | B8                | W   | 0.280      | -            | -                | -                | -         |     1.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3862 | 2024-03-05 | BLEED             | L   | 0.174      | -            | -                | -                | -         |    -5.06 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3880 | 2024-03-04 | Gaimin Gladiators | W   | 0.166      | -            | -                | -                | -         |     0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3892 | 2024-03-03 | ex-Preasy         | L   | 0.162      | -            | -                | -                | -         |    -4.96 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3897 | 2024-03-03 | ex-Sprout         | W   | 0.162      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3939 | 2024-03-01 | ex-Preasy         | W   | 0.149      | -            | -                | -                | -         |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3971 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.134      | -            | -                | -                | -         |     0.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4078 | 2024-02-23 | ex-Guild Eagles   | L   | 0.101      | -            | -                | -                | -         |    -3.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4219 | 2024-02-17 | Eternal Fire      | L   | 0.061      | -            | -                | -                | -         |    -0.34 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4247 | 2024-02-16 | Natus Vincere     | L   | 0.055      | -            | -                | -                | -         |    -0.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4280 | 2024-02-15 | Enterprise        | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4314 | 2024-02-14 | Into the Breach   | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.00 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4318 | 2024-02-14 | fnatic            | L   | 0.041      | -            | -                | -                | -         |    -0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4401 | 2024-02-08 | FORZE             | L   | 0.002      | -            | -                | -                | -         |    -0.06 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4408 | 2024-02-08 | Nemiga            | L   | 0.001      | -            | -                | -                | -         |    -0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($79,451.11)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $20,000.00     | $16,288.89      |
| 2024-05-26 |      0.721 | $2,000.00      | $1,442.78       |
| 2024-05-23 |      0.701 | $12,500.00     | $8,758.68       |
| 2024-05-12 |      0.628 | $10,000.00     | $6,282.64       |
| 2024-05-12 |      0.628 | $17,500.00     | $10,986.11      |
| 2024-05-04 |      0.575 | $10,000.00     | $5,747.22       |
| 2024-05-02 |      0.561 | $1,000.00      | $561.39         |
| 2024-04-14 |      0.441 | $52,500.00     | $23,151.04      |
| 2024-04-14 |      0.441 | $9,000.00      | $3,965.00       |
| 2024-03-06 |      0.181 | $12,500.00     | $2,267.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
