### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1460.8<br />
<br />
Final Rank Value (1460.8) = Starting Rank Value (1575.6) + Head To Head Adjustments (-114.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.720[<sup>1</sup>](#table2)
- Bounty Collected: 0.559[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.736[<sup>2</sup>](#table1)

The average of these factors is 0.570<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1575.6
- 400 + ( ( 0.570 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1575.6


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
|           64 |      153 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.36 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           63 |      212 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.096 (0.042)    | 0.506 (0.220)    | 0 (0.000) |     1.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           62 |      838 | 2024-06-16 | fnatic            | W   | 0.901      | 0.548        | 0.371 (0.183)    | 0.633 (0.313)    | 1 (0.901) |    14.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           61 |      849 | 2024-06-16 | KOI               | W   | 0.899      | -            | -                | -                | 1 (0.899) |     3.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           60 |      870 | 2024-06-15 | paiN              | W   | 0.893      | 0.548        | 0.333 (0.163)    | 0.797 (0.390)    | 1 (0.893) |    10.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      889 | 2024-06-15 | BESTIA            | W   | 0.891      | 0.548        | 0.095 (0.046)    | 0.731 (0.357)    | 1 (0.891) |     2.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |      908 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.886      | -            | -                | -                | -         |    -9.36 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1118 | 2024-06-08 | Imperial          | L   | 0.847      | -            | -                | -                | -         |   -19.44 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1175 | 2024-06-07 | Sharks            | W   | 0.840      | 0.450        | -                | 0.558 (0.211)    | 0 (0.000) |     2.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1233 | 2024-06-06 | MIBR              | W   | 0.834      | 0.450        | 0.200 (0.075)    | 0.637 (0.239)    | -         |    12.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1302 | 2024-06-05 | RED Canids        | L   | 0.827      | -            | -                | -                | -         |   -22.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1352 | 2024-06-04 | Fluxo             | W   | 0.821      | 0.450        | 0.126 (0.047)    | 0.685 (0.253)    | -         |     2.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1433 | 2024-06-01 | G2                | L   | 0.800      | -            | -                | -                | -         |    -1.86 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1523 | 2024-05-29 | Vitality          | W   | 0.780      | 0.624        | 0.654 (0.319)    | -                | 1 (0.780) |    22.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1563 | 2024-05-27 | Liquid            | W   | 0.768      | 0.624        | 0.387 (0.186)    | 0.430 (0.206)    | 1 (0.768) |    14.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1573 | 2024-05-27 | MOUZ              | W   | 0.766      | 0.624        | 1.000 (0.478)    | -                | 1 (0.766) |    22.61 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1668 | 2024-05-22 | Imperial          | L   | 0.734      | -            | -                | -                | -         |   -16.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1672 | 2024-05-22 | Imperial          | L   | 0.734      | -            | -                | -                | -         |   -17.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1751 | 2024-05-20 | W7M               | W   | 0.721      | -            | -                | -                | -         |     0.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1754 | 2024-05-20 | W7M               | W   | 0.720      | -            | -                | -                | -         |     0.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1755 | 2024-05-20 | BESTIA            | L   | 0.720      | -            | -                | -                | -         |   -21.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1758 | 2024-05-20 | BESTIA            | W   | 0.720      | 0.450        | -                | 0.731 (0.237)    | -         |     1.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1785 | 2024-05-19 | RED Canids        | L   | 0.713      | -            | -                | -                | -         |   -19.67 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           41 |     1810 | 2024-05-18 | Fluxo             | W   | 0.706      | -            | -                | -                | -         |     2.20 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           40 |     1875 | 2024-05-16 | ODDIK             | W   | 0.694      | -            | -                | -                | -         |     0.91 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1883 | 2024-05-16 | Imperial          | L   | 0.693      | -            | -                | -                | -         |   -16.46 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1920 | 2024-05-15 | RED Canids        | W   | 0.688      | 0.450        | -                | 0.738 (0.229)    | -         |     2.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           37 |     1922 | 2024-05-15 | RED Canids        | L   | 0.687      | -            | -                | -                | -         |   -19.72 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           36 |     1929 | 2024-05-15 | Sharks            | W   | 0.687      | -            | -                | -                | -         |     0.99 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     1981 | 2024-05-14 | Smoke             | W   | 0.681      | -            | -                | -                | -         |     0.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     1985 | 2024-05-14 | Smoke             | W   | 0.680      | -            | -                | -                | -         |     0.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     1995 | 2024-05-14 | Galorys           | W   | 0.679      | -            | -                | -                | -         |     0.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2014 | 2024-05-13 | Galorys           | W   | 0.674      | -            | -                | -                | -         |     0.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2033 | 2024-05-12 | inSanitY          | W   | 0.668      | -            | -                | -                | -         |     0.72 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2038 | 2024-05-12 | paiN              | L   | 0.667      | -            | -                | -                | -         |   -14.37 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2065 | 2024-05-11 | KRÜ               | W   | 0.660      | -            | -                | -                | -         |     0.61 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2092 | 2024-05-10 | inSanitY          | W   | 0.654      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2134 | 2024-05-08 | Sharks            | W   | 0.641      | -            | -                | -                | -         |     0.85 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2176 | 2024-05-06 | Vikings KR        | W   | 0.626      | -            | -                | -                | -         |     0.37 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2268 | 2024-05-01 | Case              | W   | 0.593      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2269 | 2024-05-01 | Case              | W   | 0.593      | -            | -                | -                | -         |     0.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2540 | 2024-04-19 | OG                | L   | 0.515      | -            | -                | -                | -         |   -15.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2590 | 2024-04-18 | Imperial          | L   | 0.508      | -            | -                | -                | -         |   -12.82 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2596 | 2024-04-18 | FURIA             | W   | 0.506      | 0.589        | 0.284 (0.085)    | -                | 1 (0.506) |    10.85 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2919 | 2024-04-08 | HEROIC            | L   | 0.437      | -            | -                | -                | -         |    -6.61 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2929 | 2024-04-07 | G2                | L   | 0.436      | -            | -                | -                | -         |    -1.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     3888 | 2024-02-23 | FURIA             | W   | 0.141      | -            | -                | -                | -         |     3.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     3891 | 2024-02-23 | BESTIA            | W   | 0.140      | -            | -                | -                | -         |     0.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3902 | 2024-02-22 | FURIA             | L   | 0.134      | -            | -                | -                | -         |    -1.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3908 | 2024-02-22 | BESTIA            | W   | 0.133      | -            | -                | -                | -         |     0.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     3953 | 2024-02-20 | Solid             | W   | 0.121      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     3956 | 2024-02-20 | Case              | W   | 0.120      | -            | -                | -                | -         |     0.12 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     3960 | 2024-02-20 | Salao do Corte    | W   | 0.120      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4012 | 2024-02-18 | LA RUGONETA       | L   | 0.105      | -            | -                | -                | -         |    -3.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4054 | 2024-02-16 | Fluxo             | L   | 0.093      | -            | -                | -                | -         |    -2.79 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4079 | 2024-02-15 | Imperial          | L   | 0.088      | -            | -                | -                | -         |    -2.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4080 | 2024-02-15 | Case              | W   | 0.087      | -            | -                | -                | -         |     0.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4084 | 2024-02-15 | KRÜ               | W   | 0.087      | -            | -                | -                | -         |     0.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4109 | 2024-02-14 | 2GAME             | W   | 0.081      | -            | -                | -                | -         |     0.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4174 | 2024-02-12 | LA RUGONETA       | W   | 0.067      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4256 | 2024-02-04 | Imperial          | L   | 0.014      | -            | -                | -                | -         |    -0.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4277 | 2024-02-03 | W7M               | W   | 0.008      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4310 | 2024-02-02 | Imperial          | W   | 0.001      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4314 | 2024-02-02 | ODDIK             | W   | 0.000      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($135,433.84)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.41) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.901 | $100,000.00    | $90,091.20      |
| 2024-06-09 |      0.853 | $7,500.00      | $6,400.59       |
| 2024-06-02 |      0.806 | $20,000.00     | $16,120.09      |
| 2024-05-19 |      0.713 | $4,000.00      | $2,850.69       |
| 2024-05-16 |      0.693 | $5,000.00      | $3,463.36       |
| 2024-05-12 |      0.667 | $15,000.00     | $9,998.40       |
| 2024-04-20 |      0.520 | $5,000.00      | $2,600.39       |
| 2024-04-14 |      0.477 | $4,000.00      | $1,909.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
