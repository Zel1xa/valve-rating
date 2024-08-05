### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1418.4<br />
<br />
Final Rank Value (1418.4) = Starting Rank Value (1420.5) + Head To Head Adjustments (-2.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.624[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.263[<sup>2</sup>](#table1)
- LAN Wins: 0.557[<sup>2</sup>](#table1)

The average of these factors is 0.498<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1420.5
- 400 + ( ( 0.498 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1420.5


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
|           64 |     1381 | 2024-06-07 | Astralis          | L   | 0.806      | -            | -                | -                | -         |    -3.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1436 | 2024-06-06 | Eternal Fire      | W   | 0.800      | 0.715        | 0.740 (0.423)    | 0.449 (0.257)    | 1 (0.800) |    19.63 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1447 | 2024-06-06 | Complexity        | W   | 0.799      | 0.715        | 0.342 (0.195)    | 0.373 (0.213)    | 1 (0.799) |    20.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1481 | 2024-06-05 | BIG               | W   | 0.794      | 0.715        | 0.154 (0.088)    | 0.298 (0.169)    | 1 (0.794) |    10.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1496 | 2024-06-05 | FURIA             | L   | 0.793      | -            | -                | -                | -         |    -6.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1505 | 2024-06-05 | fnatic            | W   | 0.792      | 0.715        | 0.371 (0.210)    | 0.697 (0.395)    | 1 (0.792) |    15.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1788 | 2024-05-25 | B8                | L   | 0.719      | -            | -                | -                | -         |   -17.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1813 | 2024-05-24 | DMS               | W   | 0.711      | -            | -                | -                | 0 (0.000) |     1.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1903 | 2024-05-21 | Eternal Fire      | L   | 0.693      | -            | -                | -                | -         |    -3.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1931 | 2024-05-20 | MIBR              | W   | 0.687      | 0.769        | 0.208 (0.110)    | 0.649 (0.343)    | -         |    12.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1937 | 2024-05-20 | Astralis          | L   | 0.686      | -            | -                | -                | -         |    -2.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1951 | 2024-05-20 | MIBR              | W   | 0.684      | 0.769        | 0.208 (0.110)    | 0.649 (0.341)    | -         |    13.16 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2113 | 2024-05-15 | Falcons           | L   | 0.653      | -            | -                | -                | -         |    -9.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2178 | 2024-05-14 | MOUZ              | L   | 0.645      | -            | -                | -                | -         |    -1.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2220 | 2024-05-12 | B8                | L   | 0.633      | -            | -                | -                | -         |   -16.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2224 | 2024-05-12 | 9 Pandas          | W   | 0.632      | 0.435        | -                | 0.718 (0.197)    | -         |     2.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2257 | 2024-05-11 | Metizport         | W   | 0.625      | -            | -                | -                | -         |     0.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2274 | 2024-05-10 | Enterprise        | W   | 0.619      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2334 | 2024-05-07 | FlyQuest          | L   | 0.599      | -            | -                | -                | -         |   -14.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2385 | 2024-05-04 | AMKAL             | L   | 0.580      | -            | -                | -                | -         |   -14.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2390 | 2024-05-04 | 9 Pandas          | W   | 0.579      | 0.435        | -                | 0.718 (0.181)    | -         |     1.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2413 | 2024-05-03 | Insilio           | W   | 0.571      | -            | -                | -                | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2454 | 2024-05-01 | EYEBALLERS        | W   | 0.559      | -            | -                | -                | -         |     0.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2484 | 2024-04-30 | 3DMAX             | L   | 0.552      | -            | -                | -                | -         |    -3.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2558 | 2024-04-26 | M80               | W   | 0.527      | 0.889        | 0.188 (0.088)    | 0.577 (0.270)    | 1 (0.527) |     4.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2572 | 2024-04-26 | Falcons           | W   | 0.525      | 0.889        | 0.221 (0.103)    | -                | 1 (0.525) |     8.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2595 | 2024-04-25 | Vitality          | L   | 0.519      | -            | -                | -                | -         |    -1.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2627 | 2024-04-23 | M80               | W   | 0.507      | 0.889        | 0.188 (0.085)    | 0.577 (0.260)    | 1 (0.507) |     4.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2736 | 2024-04-19 | Cloud9            | L   | 0.480      | -            | -                | -                | -         |   -13.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2747 | 2024-04-19 | Eternal Fire      | L   | 0.479      | -            | -                | -                | -         |    -2.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2771 | 2024-04-18 | Apeks             | W   | 0.474      | -            | -                | -                | -         |     1.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2775 | 2024-04-18 | brazylijski luz   | W   | 0.473      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2782 | 2024-04-18 | Serbia            | W   | 0.473      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2901 | 2024-04-14 | 3DMAX             | W   | 0.446      | 0.358        | 0.508 (0.081)    | -                | -         |    11.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2907 | 2024-04-13 | OG                | L   | 0.440      | -            | -                | -                | -         |   -12.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2911 | 2024-04-13 | Aurora            | L   | 0.440      | -            | -                | -                | -         |    -2.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2919 | 2024-04-13 | Sampi             | W   | 0.438      | -            | -                | -                | -         |     0.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2946 | 2024-04-11 | Aurora            | L   | 0.427      | -            | -                | -                | -         |    -2.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2954 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.426      | -            | -                | -                | -         |    10.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2960 | 2024-04-11 | AMKAL             | L   | 0.425      | -            | -                | -                | -         |   -11.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2999 | 2024-04-10 | Aurora            | W   | 0.419      | -            | -                | -                | -         |    10.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3058 | 2024-04-09 | BIG               | W   | 0.412      | -            | -                | -                | -         |     4.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3130 | 2024-04-06 | Alliance          | W   | 0.392      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3144 | 2024-04-05 | BLEED             | W   | 0.387      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3180 | 2024-04-04 | Alliance          | W   | 0.380      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3193 | 2024-04-04 | BLEED             | W   | 0.379      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3363 | 2024-03-27 | FAVBET            | L   | 0.327      | -            | -                | -                | -         |   -10.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3401 | 2024-03-24 | FORZE             | L   | 0.305      | -            | -                | -                | -         |    -9.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3415 | 2024-03-23 | fnatic            | W   | 0.298      | -            | -                | -                | -         |     6.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3457 | 2024-03-21 | B8                | W   | 0.285      | -            | -                | -                | -         |     1.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3851 | 2024-03-05 | BLEED             | L   | 0.179      | -            | -                | -                | -         |    -5.21 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3869 | 2024-03-04 | Gaimin Gladiators | W   | 0.171      | -            | -                | -                | -         |     0.43 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3881 | 2024-03-03 | ex-Preasy         | L   | 0.167      | -            | -                | -                | -         |    -5.11 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3886 | 2024-03-03 | ex-Sprout         | W   | 0.167      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3928 | 2024-03-01 | ex-Preasy         | W   | 0.154      | -            | -                | -                | -         |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3960 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.139      | -            | -                | -                | -         |     0.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4067 | 2024-02-23 | ex-Guild Eagles   | L   | 0.106      | -            | -                | -                | -         |    -3.22 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4208 | 2024-02-17 | Eternal Fire      | L   | 0.066      | -            | -                | -                | -         |    -0.37 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4236 | 2024-02-16 | Natus Vincere     | L   | 0.060      | -            | -                | -                | -         |    -0.08 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4269 | 2024-02-15 | Enterprise        | W   | 0.052      | -            | -                | -                | 1 (0.052) |     0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4303 | 2024-02-14 | Into the Breach   | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4307 | 2024-02-14 | fnatic            | L   | 0.046      | -            | -                | -                | -         |    -0.46 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4390 | 2024-02-08 | FORZE             | L   | 0.007      | -            | -                | -                | -         |    -0.21 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4397 | 2024-02-08 | Nemiga            | L   | 0.006      | -            | -                | -                | -         |    -0.15 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($80,186.11)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.819 | $20,000.00     | $16,388.89      |
| 2024-05-26 |      0.726 | $2,000.00      | $1,452.78       |
| 2024-05-23 |      0.706 | $12,500.00     | $8,821.18       |
| 2024-05-12 |      0.633 | $10,000.00     | $6,332.64       |
| 2024-05-12 |      0.633 | $17,500.00     | $11,073.61      |
| 2024-05-04 |      0.580 | $10,000.00     | $5,797.22       |
| 2024-05-02 |      0.566 | $1,000.00      | $566.39         |
| 2024-04-14 |      0.446 | $52,500.00     | $23,413.54      |
| 2024-04-14 |      0.446 | $9,000.00      | $4,010.00       |
| 2024-03-06 |      0.186 | $12,500.00     | $2,329.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
