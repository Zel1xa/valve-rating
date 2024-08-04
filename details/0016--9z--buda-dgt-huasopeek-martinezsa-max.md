### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1447.3<br />
<br />
Final Rank Value (1447.3) = Starting Rank Value (1553.6) + Head To Head Adjustments (-106.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.719[<sup>1</sup>](#table2)
- Bounty Collected: 0.552[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.712[<sup>2</sup>](#table1)

The average of these factors is 0.565<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1553.6
- 400 + ( ( 0.565 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1553.6


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
|           60 |      267 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      326 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.502 (0.218)    | 0 (0.000) |     1.27 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |      951 | 2024-06-16 | fnatic            | W   | 0.880      | 0.548        | 0.371 (0.179)    | 0.709 (0.342)    | 1 (0.880) |    13.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |      962 | 2024-06-16 | KOI               | W   | 0.878      | -            | -                | -                | 1 (0.878) |     3.33 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |      983 | 2024-06-15 | paiN              | W   | 0.873      | 0.548        | 0.328 (0.157)    | 0.865 (0.414)    | 1 (0.873) |    10.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1002 | 2024-06-15 | BESTIA            | W   | 0.871      | 0.548        | 0.095 (0.045)    | 0.799 (0.382)    | 1 (0.871) |     2.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1021 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.866      | -            | -                | -                | -         |    -8.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1231 | 2024-06-08 | Imperial          | L   | 0.826      | -            | -                | -                | -         |   -19.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1288 | 2024-06-07 | Sharks            | W   | 0.820      | 0.450        | -                | 0.564 (0.208)    | 0 (0.000) |     2.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1346 | 2024-06-06 | MIBR              | W   | 0.813      | 0.450        | 0.210 (0.077)    | 0.659 (0.241)    | -         |    12.33 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1415 | 2024-06-05 | RED Canids        | L   | 0.806      | -            | -                | -                | -         |   -21.77 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1465 | 2024-06-04 | Fluxo             | W   | 0.800      | 0.450        | 0.124 (0.045)    | 0.722 (0.260)    | -         |     2.49 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1546 | 2024-06-01 | G2                | L   | 0.780      | -            | -                | -                | -         |    -1.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1636 | 2024-05-29 | Vitality          | W   | 0.759      | 0.624        | 0.649 (0.308)    | -                | 1 (0.759) |    21.60 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1676 | 2024-05-27 | Liquid            | W   | 0.747      | 0.624        | 0.316 (0.147)    | 0.461 (0.215)    | 1 (0.747) |    14.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1686 | 2024-05-27 | MOUZ              | W   | 0.746      | 0.624        | 1.000 (0.465)    | -                | 1 (0.746) |    21.88 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1781 | 2024-05-22 | Imperial          | L   | 0.713      | -            | -                | -                | -         |   -15.78 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1785 | 2024-05-22 | Imperial          | L   | 0.713      | -            | -                | -                | -         |   -16.60 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1864 | 2024-05-20 | W7M               | W   | 0.700      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1867 | 2024-05-20 | W7M               | W   | 0.700      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1868 | 2024-05-20 | BESTIA            | L   | 0.699      | -            | -                | -                | -         |   -20.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1871 | 2024-05-20 | BESTIA            | W   | 0.699      | 0.450        | -                | 0.799 (0.251)    | -         |     1.27 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1898 | 2024-05-19 | RED Canids        | L   | 0.692      | -            | -                | -                | -         |   -18.99 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1923 | 2024-05-18 | Fluxo             | W   | 0.685      | -            | -                | -                | -         |     2.29 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     1988 | 2024-05-16 | ODDIK             | W   | 0.673      | -            | -                | -                | -         |     0.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     1996 | 2024-05-16 | Imperial          | L   | 0.672      | -            | -                | -                | -         |   -16.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2033 | 2024-05-15 | RED Canids        | W   | 0.667      | 0.450        | -                | 0.743 (0.223)    | -         |     2.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2035 | 2024-05-15 | RED Canids        | L   | 0.667      | -            | -                | -                | -         |   -19.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2042 | 2024-05-15 | Sharks            | W   | 0.666      | -            | -                | -                | -         |     1.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2094 | 2024-05-14 | Smoke             | W   | 0.660      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2098 | 2024-05-14 | Smoke             | W   | 0.660      | -            | -                | -                | -         |     0.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2108 | 2024-05-14 | Galorys           | W   | 0.659      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2127 | 2024-05-13 | Galorys           | W   | 0.653      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2146 | 2024-05-12 | inSanitY          | W   | 0.647      | -            | -                | -                | -         |     0.77 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2151 | 2024-05-12 | paiN              | L   | 0.646      | -            | -                | -                | -         |   -13.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2178 | 2024-05-11 | KRÜ               | W   | 0.639      | -            | -                | -                | -         |     0.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2205 | 2024-05-10 | inSanitY          | W   | 0.634      | -            | -                | -                | -         |     0.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2247 | 2024-05-08 | Sharks            | W   | 0.620      | -            | -                | -                | -         |     0.91 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2289 | 2024-05-06 | Vikings KR        | W   | 0.605      | -            | -                | -                | -         |     0.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2381 | 2024-05-01 | Case              | W   | 0.573      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2382 | 2024-05-01 | Case              | W   | 0.572      | -            | -                | -                | -         |     0.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2652 | 2024-04-19 | OG                | L   | 0.494      | -            | -                | -                | -         |   -14.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2702 | 2024-04-18 | Imperial          | L   | 0.487      | -            | -                | -                | -         |   -12.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2708 | 2024-04-18 | FURIA             | W   | 0.486      | 0.589        | 0.284 (0.081)    | -                | 1 (0.486) |    10.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3031 | 2024-04-08 | HEROIC            | L   | 0.416      | -            | -                | -                | -         |    -6.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3041 | 2024-04-07 | G2                | L   | 0.415      | -            | -                | -                | -         |    -1.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     3999 | 2024-02-23 | FURIA             | W   | 0.120      | -            | -                | -                | -         |     2.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4002 | 2024-02-23 | BESTIA            | W   | 0.119      | -            | -                | -                | -         |     0.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4013 | 2024-02-22 | FURIA             | L   | 0.113      | -            | -                | -                | -         |    -0.99 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4019 | 2024-02-22 | BESTIA            | W   | 0.112      | -            | -                | -                | -         |     0.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4064 | 2024-02-20 | Solid             | W   | 0.100      | -            | -                | -                | -         |     0.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4067 | 2024-02-20 | Case              | W   | 0.100      | -            | -                | -                | -         |     0.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4071 | 2024-02-20 | Salao do Corte    | W   | 0.099      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4123 | 2024-02-18 | LA RUGONETA       | L   | 0.084      | -            | -                | -                | -         |    -2.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4164 | 2024-02-16 | Fluxo             | L   | 0.072      | -            | -                | -                | -         |    -2.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4189 | 2024-02-15 | Imperial          | L   | 0.067      | -            | -                | -                | -         |    -1.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4190 | 2024-02-15 | Case              | W   | 0.066      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4194 | 2024-02-15 | KRÜ               | W   | 0.066      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4219 | 2024-02-14 | 2GAME             | W   | 0.060      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4284 | 2024-02-12 | LA RUGONETA       | W   | 0.046      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($132,107.18)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.41) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.880 | $100,000.00    | $88,018.52      |
| 2024-06-09 |      0.833 | $7,500.00      | $6,245.14       |
| 2024-06-02 |      0.785 | $20,000.00     | $15,705.56      |
| 2024-05-19 |      0.692 | $4,000.00      | $2,767.78       |
| 2024-05-16 |      0.672 | $5,000.00      | $3,359.72       |
| 2024-05-12 |      0.646 | $15,000.00     | $9,687.50       |
| 2024-04-20 |      0.499 | $5,000.00      | $2,496.76       |
| 2024-04-14 |      0.457 | $4,000.00      | $1,826.20       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
