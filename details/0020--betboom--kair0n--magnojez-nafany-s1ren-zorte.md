### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1417.2<br />
<br />
Final Rank Value (1417.2) = Starting Rank Value (1416.7) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.546[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.553[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1416.7
- 400 + ( ( 0.494 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1416.7


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
|           64 |     1390 | 2024-06-07 | Astralis          | L   | 0.800      | -            | -                | -                | -         |    -3.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1445 | 2024-06-06 | Eternal Fire      | W   | 0.794      | 0.715        | 0.739 (0.419)    | 0.438 (0.249)    | 1 (0.794) |    19.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1456 | 2024-06-06 | Complexity        | W   | 0.793      | 0.715        | 0.341 (0.194)    | 0.364 (0.206)    | 1 (0.793) |    20.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1490 | 2024-06-05 | BIG               | W   | 0.788      | 0.715        | 0.154 (0.087)    | -                | 1 (0.788) |    10.79 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1505 | 2024-06-05 | FURIA             | L   | 0.787      | -            | -                | -                | -         |    -6.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1514 | 2024-06-05 | fnatic            | W   | 0.786      | 0.715        | 0.371 (0.208)    | 0.680 (0.383)    | 1 (0.786) |    14.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1797 | 2024-05-25 | B8                | L   | 0.714      | -            | -                | -                | -         |   -17.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1822 | 2024-05-24 | DMS               | W   | 0.705      | -            | -                | -                | 0 (0.000) |     1.63 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1912 | 2024-05-21 | Eternal Fire      | L   | 0.687      | -            | -                | -                | -         |    -3.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1940 | 2024-05-20 | MIBR              | W   | 0.682      | 0.769        | 0.208 (0.109)    | 0.633 (0.332)    | -         |    12.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1946 | 2024-05-20 | Astralis          | L   | 0.681      | -            | -                | -                | -         |    -2.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1960 | 2024-05-20 | MIBR              | W   | 0.679      | 0.769        | 0.208 (0.108)    | 0.633 (0.330)    | -         |    12.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2122 | 2024-05-15 | Falcons           | L   | 0.648      | -            | -                | -                | -         |    -9.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2187 | 2024-05-14 | MOUZ              | L   | 0.640      | -            | -                | -                | -         |    -1.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2229 | 2024-05-12 | B8                | L   | 0.628      | -            | -                | -                | -         |   -16.55 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2233 | 2024-05-12 | 9 Pandas          | W   | 0.627      | 0.435        | -                | 0.700 (0.191)    | -         |     2.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2266 | 2024-05-11 | Metizport         | W   | 0.620      | -            | -                | -                | -         |     1.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2283 | 2024-05-10 | Enterprise        | W   | 0.613      | 0.435        | -                | 0.641 (0.171)    | -         |     1.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2343 | 2024-05-07 | FlyQuest          | L   | 0.594      | -            | -                | -                | -         |   -14.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2394 | 2024-05-04 | AMKAL             | L   | 0.574      | -            | -                | -                | -         |   -14.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2399 | 2024-05-04 | 9 Pandas          | W   | 0.573      | 0.435        | -                | 0.700 (0.174)    | -         |     1.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2422 | 2024-05-03 | Insilio           | W   | 0.565      | -            | -                | -                | -         |     1.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2463 | 2024-05-01 | EYEBALLERS        | W   | 0.554      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2493 | 2024-04-30 | 3DMAX             | L   | 0.546      | -            | -                | -                | -         |    -3.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2567 | 2024-04-26 | M80               | W   | 0.522      | 0.889        | 0.188 (0.087)    | 0.563 (0.261)    | 1 (0.522) |     4.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2581 | 2024-04-26 | Falcons           | W   | 0.519      | 0.889        | 0.219 (0.101)    | -                | 1 (0.519) |     8.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2604 | 2024-04-25 | Vitality          | L   | 0.514      | -            | -                | -                | -         |    -1.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2636 | 2024-04-23 | M80               | W   | 0.501      | 0.889        | 0.188 (0.084)    | 0.563 (0.251)    | 1 (0.501) |     4.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2745 | 2024-04-19 | Cloud9            | L   | 0.474      | -            | -                | -                | -         |   -13.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2756 | 2024-04-19 | Eternal Fire      | L   | 0.473      | -            | -                | -                | -         |    -2.32 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2780 | 2024-04-18 | Apeks             | W   | 0.468      | -            | -                | -                | -         |     1.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2784 | 2024-04-18 | brazylijski luz   | W   | 0.468      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2791 | 2024-04-18 | Serbia            | W   | 0.467      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2910 | 2024-04-14 | 3DMAX             | W   | 0.440      | 0.358        | 0.510 (0.080)    | -                | -         |    10.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2916 | 2024-04-13 | OG                | L   | 0.435      | -            | -                | -                | -         |   -12.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2920 | 2024-04-13 | Aurora            | L   | 0.434      | -            | -                | -                | -         |    -2.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2928 | 2024-04-13 | Sampi             | W   | 0.432      | -            | -                | -                | -         |     0.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2955 | 2024-04-11 | Aurora            | L   | 0.421      | -            | -                | -                | -         |    -2.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2963 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.421      | -            | -                | -                | -         |    10.75 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2969 | 2024-04-11 | AMKAL             | L   | 0.420      | -            | -                | -                | -         |   -10.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     3008 | 2024-04-10 | Aurora            | W   | 0.414      | -            | -                | -                | -         |    10.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3067 | 2024-04-09 | BIG               | W   | 0.407      | -            | -                | -                | -         |     4.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3139 | 2024-04-06 | Alliance          | W   | 0.387      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3153 | 2024-04-05 | BLEED             | W   | 0.381      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3189 | 2024-04-04 | Alliance          | W   | 0.375      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3202 | 2024-04-04 | BLEED             | W   | 0.373      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3372 | 2024-03-27 | FAVBET            | L   | 0.321      | -            | -                | -                | -         |    -9.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3410 | 2024-03-24 | FORZE             | L   | 0.299      | -            | -                | -                | -         |    -8.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3424 | 2024-03-23 | fnatic            | W   | 0.293      | -            | -                | -                | -         |     6.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3466 | 2024-03-21 | B8                | W   | 0.279      | -            | -                | -                | -         |     1.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3860 | 2024-03-05 | BLEED             | L   | 0.173      | -            | -                | -                | -         |    -5.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3878 | 2024-03-04 | Gaimin Gladiators | W   | 0.166      | -            | -                | -                | -         |     0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3890 | 2024-03-03 | ex-Preasy         | L   | 0.161      | -            | -                | -                | -         |    -4.94 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3895 | 2024-03-03 | ex-Sprout         | W   | 0.161      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3937 | 2024-03-01 | ex-Preasy         | W   | 0.148      | -            | -                | -                | -         |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3969 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.133      | -            | -                | -                | -         |     0.34 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4076 | 2024-02-23 | ex-Guild Eagles   | L   | 0.100      | -            | -                | -                | -         |    -3.05 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4217 | 2024-02-17 | Eternal Fire      | L   | 0.061      | -            | -                | -                | -         |    -0.33 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4245 | 2024-02-16 | Natus Vincere     | L   | 0.054      | -            | -                | -                | -         |    -0.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4278 | 2024-02-15 | Enterprise        | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4312 | 2024-02-14 | Into the Breach   | W   | 0.041      | -            | -                | -                | 1 (0.041) |     0.00 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4316 | 2024-02-14 | fnatic            | L   | 0.040      | -            | -                | -                | -         |    -0.40 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4399 | 2024-02-08 | FORZE             | L   | 0.001      | -            | -                | -                | -         |    -0.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4406 | 2024-02-08 | Nemiga            | L   | 0.000      | -            | -                | -                | -         |    -0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($79,355.83)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $20,000.00     | $16,275.93      |
| 2024-05-26 |      0.721 | $2,000.00      | $1,441.48       |
| 2024-05-23 |      0.700 | $12,500.00     | $8,750.58       |
| 2024-05-12 |      0.628 | $10,000.00     | $6,276.16       |
| 2024-05-12 |      0.627 | $17,500.00     | $10,974.77      |
| 2024-05-04 |      0.574 | $10,000.00     | $5,740.74       |
| 2024-05-02 |      0.561 | $1,000.00      | $560.74         |
| 2024-04-14 |      0.440 | $52,500.00     | $23,117.01      |
| 2024-04-14 |      0.440 | $9,000.00      | $3,959.17       |
| 2024-03-06 |      0.181 | $12,500.00     | $2,259.26       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
