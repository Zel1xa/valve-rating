### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1418.8<br />
<br />
Final Rank Value (1418.8) = Starting Rank Value (1441.4) + Head To Head Adjustments (-22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.629[<sup>1</sup>](#table2)
- Bounty Collected: 0.546[<sup>2</sup>](#table1)
- Opponent Network: 0.264[<sup>2</sup>](#table1)
- LAN Wins: 0.586[<sup>2</sup>](#table1)

The average of these factors is 0.506<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1441.4
- 400 + ( ( 0.506 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1441.4


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
|           64 |     1257 | 2024-06-07 | Astralis          | L   | 0.832      | -            | -                | -                | -         |    -4.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1314 | 2024-06-06 | Eternal Fire      | W   | 0.826      | 0.715        | 0.757 (0.447)    | 0.461 (0.272)    | 1 (0.826) |    20.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1325 | 2024-06-06 | Complexity        | W   | 0.825      | 0.715        | 0.318 (0.188)    | 0.366 (0.216)    | 1 (0.825) |    20.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1361 | 2024-06-05 | BIG               | W   | 0.820      | 0.715        | 0.132 (0.078)    | 0.299 (0.175)    | 1 (0.820) |     9.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1377 | 2024-06-05 | FURIA             | L   | 0.820      | -            | -                | -                | -         |    -6.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1386 | 2024-06-05 | fnatic            | W   | 0.819      | 0.715        | 0.292 (0.171)    | 0.529 (0.310)    | 1 (0.819) |    10.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1672 | 2024-05-25 | B8                | L   | 0.746      | -            | -                | -                | -         |   -18.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1697 | 2024-05-24 | DMS               | W   | 0.738      | -            | -                | -                | 0 (0.000) |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1802 | 2024-05-21 | Eternal Fire      | L   | 0.720      | -            | -                | -                | -         |    -3.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1832 | 2024-05-20 | MIBR              | W   | 0.714      | 0.769        | 0.201 (0.110)    | 0.637 (0.350)    | -         |    12.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1838 | 2024-05-20 | Astralis          | L   | 0.713      | -            | -                | -                | -         |    -2.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1855 | 2024-05-20 | MIBR              | W   | 0.711      | 0.769        | 0.201 (0.110)    | 0.637 (0.348)    | -         |    13.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2023 | 2024-05-15 | Falcons           | L   | 0.680      | -            | -                | -                | -         |    -9.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2094 | 2024-05-14 | MOUZ              | L   | 0.672      | -            | -                | -                | -         |    -1.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2139 | 2024-05-12 | B8                | L   | 0.660      | -            | -                | -                | -         |   -17.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2143 | 2024-05-12 | 9 Pandas          | W   | 0.659      | -            | -                | -                | -         |     2.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2176 | 2024-05-11 | Metizport         | W   | 0.652      | -            | -                | -                | -         |     1.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2193 | 2024-05-10 | Enterprise        | W   | 0.645      | 0.435        | -                | 0.622 (0.175)    | -         |     1.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2255 | 2024-05-07 | FlyQuest          | L   | 0.626      | -            | -                | -                | -         |   -14.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2306 | 2024-05-04 | AMKAL             | L   | 0.606      | -            | -                | -                | -         |   -15.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2311 | 2024-05-04 | 9 Pandas          | W   | 0.606      | -            | -                | -                | -         |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2334 | 2024-05-03 | Insilio           | W   | 0.598      | -            | -                | -                | -         |     1.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2377 | 2024-05-01 | EYEBALLERS        | W   | 0.586      | -            | -                | -                | -         |     0.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2408 | 2024-04-30 | 3DMAX             | L   | 0.578      | -            | -                | -                | -         |    -4.46 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2483 | 2024-04-26 | M80               | W   | 0.554      | 0.889        | 0.190 (0.094)    | 0.641 (0.316)    | 1 (0.554) |     5.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2496 | 2024-04-26 | Falcons           | W   | 0.552      | 0.889        | 0.205 (0.101)    | -                | 1 (0.552) |     9.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2519 | 2024-04-25 | Vitality          | L   | 0.546      | -            | -                | -                | -         |    -1.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2552 | 2024-04-23 | M80               | W   | 0.533      | 0.889        | 0.190 (0.090)    | 0.641 (0.304)    | 1 (0.533) |     5.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2667 | 2024-04-19 | Cloud9            | L   | 0.507      | -            | -                | -                | -         |   -13.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2678 | 2024-04-19 | Eternal Fire      | L   | 0.506      | -            | -                | -                | -         |    -2.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2703 | 2024-04-18 | Apeks             | W   | 0.500      | -            | -                | -                | -         |     1.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2707 | 2024-04-18 | brazylijski luz   | W   | 0.500      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2714 | 2024-04-18 | Serbia            | W   | 0.500      | -            | -                | -                | -         |     0.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2835 | 2024-04-14 | 3DMAX             | W   | 0.472      | 0.358        | 0.505 (0.085)    | 1.000 (0.169)    | -         |    11.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2841 | 2024-04-13 | OG                | L   | 0.467      | -            | -                | -                | -         |   -13.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2845 | 2024-04-13 | Aurora            | L   | 0.466      | -            | -                | -                | -         |    -3.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2853 | 2024-04-13 | Sampi             | W   | 0.465      | -            | -                | -                | -         |     0.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2881 | 2024-04-11 | Aurora            | L   | 0.454      | -            | -                | -                | -         |    -3.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2889 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.453      | -            | -                | -                | -         |     9.44 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2895 | 2024-04-11 | AMKAL             | L   | 0.452      | -            | -                | -                | -         |   -11.92 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2934 | 2024-04-10 | Aurora            | W   | 0.446      | -            | -                | -                | -         |    11.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     2993 | 2024-04-09 | BIG               | W   | 0.439      | -            | -                | -                | -         |     3.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3065 | 2024-04-06 | Alliance          | W   | 0.419      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3079 | 2024-04-05 | BLEED             | W   | 0.413      | -            | -                | -                | -         |     1.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3115 | 2024-04-04 | Alliance          | W   | 0.407      | -            | -                | -                | -         |     0.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3129 | 2024-04-04 | BLEED             | W   | 0.406      | -            | -                | -                | -         |     1.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3307 | 2024-03-27 | FAVBET            | L   | 0.354      | -            | -                | -                | -         |   -10.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3349 | 2024-03-24 | FORZE             | L   | 0.332      | -            | -                | -                | -         |    -9.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3363 | 2024-03-23 | fnatic            | W   | 0.325      | -            | -                | -                | -         |     4.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3405 | 2024-03-21 | B8                | W   | 0.312      | -            | -                | -                | -         |     1.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3810 | 2024-03-05 | BLEED             | L   | 0.206      | -            | -                | -                | -         |    -6.00 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3828 | 2024-03-04 | Gaimin Gladiators | W   | 0.198      | -            | -                | -                | -         |     0.50 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3840 | 2024-03-03 | ex-Preasy         | L   | 0.194      | -            | -                | -                | -         |    -5.94 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3845 | 2024-03-03 | ex-Sprout         | W   | 0.193      | -            | -                | -                | -         |     0.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3888 | 2024-03-01 | ex-Preasy         | W   | 0.181      | -            | -                | -                | -         |     0.15 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3921 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.166      | -            | -                | -                | -         |     0.40 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4033 | 2024-02-23 | ex-Guild Eagles   | L   | 0.132      | -            | -                | -                | -         |    -4.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4176 | 2024-02-17 | Eternal Fire      | L   | 0.093      | -            | -                | -                | -         |    -0.52 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4205 | 2024-02-16 | Natus Vincere     | L   | 0.086      | -            | -                | -                | -         |    -0.12 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4238 | 2024-02-15 | Enterprise        | W   | 0.079      | -            | -                | -                | 1 (0.079) |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4272 | 2024-02-14 | Into the Breach   | W   | 0.073      | -            | -                | -                | 1 (0.073) |     0.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4276 | 2024-02-14 | fnatic            | L   | 0.073      | -            | -                | -                | -         |    -1.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4369 | 2024-02-08 | FORZE             | L   | 0.034      | -            | -                | -                | -         |    -1.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4376 | 2024-02-08 | Nemiga            | L   | 0.033      | -            | -                | -                | -         |    -0.85 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($84,106.11)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $20,000.00     | $16,922.22      |
| 2024-05-26 |      0.753 | $2,000.00      | $1,506.11       |
| 2024-05-23 |      0.732 | $12,500.00     | $9,154.51       |
| 2024-05-12 |      0.660 | $10,000.00     | $6,599.31       |
| 2024-05-12 |      0.659 | $17,500.00     | $11,540.28      |
| 2024-05-04 |      0.606 | $10,000.00     | $6,063.89       |
| 2024-05-02 |      0.593 | $1,000.00      | $593.06         |
| 2024-04-14 |      0.473 | $52,500.00     | $24,813.54      |
| 2024-04-14 |      0.472 | $9,000.00      | $4,250.00       |
| 2024-03-06 |      0.213 | $12,500.00     | $2,663.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
