### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1419.5<br />
<br />
Final Rank Value (1419.5) = Starting Rank Value (1443.6) + Head To Head Adjustments (-24.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.629[<sup>1</sup>](#table2)
- Bounty Collected: 0.546[<sup>2</sup>](#table1)
- Opponent Network: 0.264[<sup>2</sup>](#table1)
- LAN Wins: 0.587[<sup>2</sup>](#table1)

The average of these factors is 0.507<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1443.6
- 400 + ( ( 0.507 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1443.6


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
|           64 |     1253 | 2024-06-07 | Astralis          | L   | 0.834      | -            | -                | -                | -         |    -4.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1310 | 2024-06-06 | Eternal Fire      | W   | 0.828      | 0.715        | 0.757 (0.448)    | 0.461 (0.273)    | 1 (0.828) |    20.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1321 | 2024-06-06 | Complexity        | W   | 0.827      | 0.715        | 0.318 (0.188)    | 0.366 (0.217)    | 1 (0.827) |    20.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1357 | 2024-06-05 | BIG               | W   | 0.822      | 0.715        | 0.132 (0.078)    | 0.299 (0.176)    | 1 (0.822) |     9.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1373 | 2024-06-05 | FURIA             | L   | 0.821      | -            | -                | -                | -         |    -6.90 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1382 | 2024-06-05 | fnatic            | W   | 0.820      | 0.715        | 0.292 (0.171)    | 0.529 (0.311)    | 1 (0.820) |    10.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1668 | 2024-05-25 | B8                | L   | 0.747      | -            | -                | -                | -         |   -18.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1693 | 2024-05-24 | DMS               | W   | 0.739      | -            | -                | -                | 0 (0.000) |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1798 | 2024-05-21 | Eternal Fire      | L   | 0.721      | -            | -                | -                | -         |    -3.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1828 | 2024-05-20 | MIBR              | W   | 0.715      | 0.769        | 0.201 (0.111)    | 0.637 (0.350)    | -         |    12.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1834 | 2024-05-20 | Astralis          | L   | 0.714      | -            | -                | -                | -         |    -3.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1851 | 2024-05-20 | MIBR              | W   | 0.713      | 0.769        | 0.201 (0.110)    | 0.637 (0.349)    | -         |    13.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2019 | 2024-05-15 | Falcons           | L   | 0.681      | -            | -                | -                | -         |    -9.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2090 | 2024-05-14 | MOUZ              | L   | 0.673      | -            | -                | -                | -         |    -1.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2135 | 2024-05-12 | B8                | L   | 0.661      | -            | -                | -                | -         |   -17.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2139 | 2024-05-12 | 9 Pandas          | W   | 0.660      | -            | -                | -                | -         |     2.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2172 | 2024-05-11 | Metizport         | W   | 0.653      | -            | -                | -                | -         |     1.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2189 | 2024-05-10 | Enterprise        | W   | 0.647      | 0.435        | -                | 0.622 (0.175)    | -         |     1.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2251 | 2024-05-07 | FlyQuest          | L   | 0.627      | -            | -                | -                | -         |   -14.55 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2302 | 2024-05-04 | AMKAL             | L   | 0.608      | -            | -                | -                | -         |   -15.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2307 | 2024-05-04 | 9 Pandas          | W   | 0.607      | -            | -                | -                | -         |     1.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2330 | 2024-05-03 | Insilio           | W   | 0.599      | -            | -                | -                | -         |     1.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2373 | 2024-05-01 | EYEBALLERS        | W   | 0.587      | -            | -                | -                | -         |     0.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2404 | 2024-04-30 | 3DMAX             | L   | 0.580      | -            | -                | -                | -         |    -4.46 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2479 | 2024-04-26 | M80               | W   | 0.555      | 0.889        | 0.190 (0.094)    | 0.641 (0.317)    | 1 (0.555) |     5.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2492 | 2024-04-26 | Falcons           | W   | 0.553      | 0.889        | 0.206 (0.101)    | -                | 1 (0.553) |     9.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2515 | 2024-04-25 | Vitality          | L   | 0.547      | -            | -                | -                | -         |    -1.42 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2548 | 2024-04-23 | M80               | W   | 0.535      | 0.889        | 0.190 (0.090)    | 0.641 (0.305)    | 1 (0.535) |     4.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2663 | 2024-04-19 | Cloud9            | L   | 0.508      | -            | -                | -                | -         |   -13.76 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2674 | 2024-04-19 | Eternal Fire      | L   | 0.507      | -            | -                | -                | -         |    -2.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2699 | 2024-04-18 | Apeks             | W   | 0.502      | -            | -                | -                | -         |     1.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2703 | 2024-04-18 | brazylijski luz   | W   | 0.501      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2710 | 2024-04-18 | Serbia            | W   | 0.501      | -            | -                | -                | -         |     0.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2831 | 2024-04-14 | 3DMAX             | W   | 0.474      | 0.358        | 0.505 (0.086)    | 1.000 (0.170)    | -         |    11.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2837 | 2024-04-13 | OG                | L   | 0.468      | -            | -                | -                | -         |   -13.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2841 | 2024-04-13 | Aurora            | L   | 0.468      | -            | -                | -                | -         |    -3.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2849 | 2024-04-13 | Sampi             | W   | 0.466      | -            | -                | -                | -         |     0.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2877 | 2024-04-11 | Aurora            | L   | 0.455      | -            | -                | -                | -         |    -3.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2885 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.454      | -            | -                | -                | -         |     8.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2891 | 2024-04-11 | AMKAL             | L   | 0.453      | -            | -                | -                | -         |   -11.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2930 | 2024-04-10 | Aurora            | W   | 0.448      | -            | -                | -                | -         |    11.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     2989 | 2024-04-09 | BIG               | W   | 0.440      | -            | -                | -                | -         |     3.69 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3061 | 2024-04-06 | Alliance          | W   | 0.420      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3075 | 2024-04-05 | BLEED             | W   | 0.415      | -            | -                | -                | -         |     1.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3111 | 2024-04-04 | Alliance          | W   | 0.408      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3125 | 2024-04-04 | BLEED             | W   | 0.407      | -            | -                | -                | -         |     1.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3303 | 2024-03-27 | FAVBET            | L   | 0.355      | -            | -                | -                | -         |   -10.92 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3345 | 2024-03-24 | FORZE             | L   | 0.333      | -            | -                | -                | -         |    -9.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3359 | 2024-03-23 | fnatic            | W   | 0.326      | -            | -                | -                | -         |     4.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3401 | 2024-03-21 | B8                | W   | 0.313      | -            | -                | -                | -         |     1.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3806 | 2024-03-05 | BLEED             | L   | 0.207      | -            | -                | -                | -         |    -6.05 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3824 | 2024-03-04 | Gaimin Gladiators | W   | 0.199      | -            | -                | -                | -         |     0.51 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3836 | 2024-03-03 | ex-Preasy         | L   | 0.195      | -            | -                | -                | -         |    -5.98 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3841 | 2024-03-03 | ex-Sprout         | W   | 0.195      | -            | -                | -                | -         |     0.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3884 | 2024-03-01 | ex-Preasy         | W   | 0.182      | -            | -                | -                | -         |     0.15 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3917 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.167      | -            | -                | -                | -         |     0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4029 | 2024-02-23 | ex-Guild Eagles   | L   | 0.134      | -            | -                | -                | -         |    -4.08 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4172 | 2024-02-17 | Eternal Fire      | L   | 0.094      | -            | -                | -                | -         |    -0.53 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4201 | 2024-02-16 | Natus Vincere     | L   | 0.088      | -            | -                | -                | -         |    -0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4234 | 2024-02-15 | Enterprise        | W   | 0.080      | -            | -                | -                | 1 (0.080) |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4268 | 2024-02-14 | Into the Breach   | W   | 0.075      | -            | -                | -                | 1 (0.075) |     0.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4272 | 2024-02-14 | fnatic            | L   | 0.074      | -            | -                | -                | -         |    -1.38 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4365 | 2024-02-08 | FORZE             | L   | 0.035      | -            | -                | -                | -         |    -1.06 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4372 | 2024-02-08 | Nemiga            | L   | 0.034      | -            | -                | -                | -         |    -0.89 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($84,310.28)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $20,000.00     | $16,950.00      |
| 2024-05-26 |      0.754 | $2,000.00      | $1,508.89       |
| 2024-05-23 |      0.734 | $12,500.00     | $9,171.88       |
| 2024-05-12 |      0.661 | $10,000.00     | $6,613.19       |
| 2024-05-12 |      0.661 | $17,500.00     | $11,564.58      |
| 2024-05-04 |      0.608 | $10,000.00     | $6,077.78       |
| 2024-05-02 |      0.594 | $1,000.00      | $594.44         |
| 2024-04-14 |      0.474 | $52,500.00     | $24,886.46      |
| 2024-04-14 |      0.474 | $9,000.00      | $4,262.50       |
| 2024-03-06 |      0.214 | $12,500.00     | $2,680.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
