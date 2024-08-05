### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1448.9<br />
<br />
Final Rank Value (1448.9) = Starting Rank Value (1551.9) + Head To Head Adjustments (-103.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.718[<sup>1</sup>](#table2)
- Bounty Collected: 0.553[<sup>2</sup>](#table1)
- Opponent Network: 0.272[<sup>2</sup>](#table1)
- LAN Wins: 0.707[<sup>2</sup>](#table1)

The average of these factors is 0.563<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1551.9
- 400 + ( ( 0.563 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1551.9


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
|           60 |      319 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      378 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.499 (0.217)    | 0 (0.000) |     1.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1004 | 2024-06-16 | fnatic            | W   | 0.870      | 0.548        | 0.371 (0.177)    | 0.706 (0.336)    | 1 (0.870) |    13.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1015 | 2024-06-16 | KOI               | W   | 0.868      | -            | -                | -                | 1 (0.868) |     3.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1036 | 2024-06-15 | paiN              | W   | 0.862      | 0.548        | 0.325 (0.154)    | 0.867 (0.410)    | 1 (0.862) |    10.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1055 | 2024-06-15 | BESTIA            | W   | 0.860      | 0.548        | 0.096 (0.045)    | 0.801 (0.378)    | 1 (0.860) |     2.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1074 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.855      | -            | -                | -                | -         |    -7.90 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1284 | 2024-06-08 | Imperial          | L   | 0.816      | -            | -                | -                | -         |   -18.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1341 | 2024-06-07 | Sharks            | W   | 0.809      | 0.450        | -                | 0.565 (0.206)    | 0 (0.000) |     2.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1399 | 2024-06-06 | MIBR              | W   | 0.802      | 0.450        | 0.208 (0.075)    | 0.657 (0.237)    | -         |    11.99 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1468 | 2024-06-05 | RED Canids        | L   | 0.796      | -            | -                | -                | -         |   -21.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1518 | 2024-06-04 | Fluxo             | W   | 0.789      | 0.450        | 0.123 (0.044)    | 0.724 (0.257)    | -         |     2.42 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1599 | 2024-06-01 | G2                | L   | 0.769      | -            | -                | -                | -         |    -1.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1689 | 2024-05-29 | Vitality          | W   | 0.749      | 0.624        | 0.648 (0.303)    | -                | 1 (0.749) |    21.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1729 | 2024-05-27 | Liquid            | W   | 0.737      | 0.624        | 0.384 (0.176)    | 0.456 (0.210)    | 1 (0.737) |    16.48 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1739 | 2024-05-27 | MOUZ              | W   | 0.735      | 0.624        | 1.000 (0.459)    | -                | 1 (0.735) |    21.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1834 | 2024-05-22 | Imperial          | L   | 0.703      | -            | -                | -                | -         |   -15.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1838 | 2024-05-22 | Imperial          | L   | 0.703      | -            | -                | -                | -         |   -16.48 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1917 | 2024-05-20 | W7M               | W   | 0.689      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1920 | 2024-05-20 | W7M               | W   | 0.689      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1921 | 2024-05-20 | BESTIA            | L   | 0.689      | -            | -                | -                | -         |   -20.36 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1924 | 2024-05-20 | BESTIA            | W   | 0.688      | 0.450        | -                | 0.801 (0.248)    | -         |     1.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1951 | 2024-05-19 | RED Canids        | L   | 0.681      | -            | -                | -                | -         |   -18.73 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1976 | 2024-05-18 | Fluxo             | W   | 0.675      | -            | -                | -                | -         |     2.23 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2041 | 2024-05-16 | ODDIK             | W   | 0.662      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2049 | 2024-05-16 | Imperial          | L   | 0.661      | -            | -                | -                | -         |   -15.87 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2086 | 2024-05-15 | RED Canids        | W   | 0.657      | 0.450        | -                | 0.757 (0.224)    | -         |     2.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2088 | 2024-05-15 | RED Canids        | L   | 0.656      | -            | -                | -                | -         |   -18.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2095 | 2024-05-15 | Sharks            | W   | 0.655      | -            | -                | -                | -         |     1.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2147 | 2024-05-14 | Smoke             | W   | 0.649      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2151 | 2024-05-14 | Smoke             | W   | 0.649      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2161 | 2024-05-14 | Galorys           | W   | 0.648      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2180 | 2024-05-13 | Galorys           | W   | 0.643      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2199 | 2024-05-12 | inSanitY          | W   | 0.636      | -            | -                | -                | -         |     0.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2204 | 2024-05-12 | paiN              | L   | 0.635      | -            | -                | -                | -         |   -13.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2231 | 2024-05-11 | KRÜ               | W   | 0.629      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2258 | 2024-05-10 | inSanitY          | W   | 0.623      | -            | -                | -                | -         |     0.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2300 | 2024-05-08 | Sharks            | W   | 0.609      | -            | -                | -                | -         |     0.89 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2342 | 2024-05-06 | Vikings KR        | W   | 0.594      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2434 | 2024-05-01 | Case              | W   | 0.562      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2435 | 2024-05-01 | Case              | W   | 0.562      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2706 | 2024-04-19 | OG                | L   | 0.483      | -            | -                | -                | -         |   -14.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2756 | 2024-04-18 | Imperial          | L   | 0.476      | -            | -                | -                | -         |   -12.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2762 | 2024-04-18 | FURIA             | W   | 0.475      | 0.589        | 0.284 (0.079)    | -                | 1 (0.475) |    10.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3085 | 2024-04-08 | HEROIC            | L   | 0.406      | -            | -                | -                | -         |    -6.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3095 | 2024-04-07 | G2                | L   | 0.404      | -            | -                | -                | -         |    -1.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4054 | 2024-02-23 | FURIA             | W   | 0.110      | -            | -                | -                | -         |     2.52 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4057 | 2024-02-23 | BESTIA            | W   | 0.108      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4068 | 2024-02-22 | FURIA             | L   | 0.103      | -            | -                | -                | -         |    -0.88 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4074 | 2024-02-22 | BESTIA            | W   | 0.102      | -            | -                | -                | -         |     0.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4119 | 2024-02-20 | Solid             | W   | 0.089      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4122 | 2024-02-20 | Case              | W   | 0.089      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4126 | 2024-02-20 | Salao do Corte    | W   | 0.089      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4178 | 2024-02-18 | LA RUGONETA       | L   | 0.074      | -            | -                | -                | -         |    -2.31 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4220 | 2024-02-16 | Fluxo             | L   | 0.062      | -            | -                | -                | -         |    -1.84 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4245 | 2024-02-15 | Imperial          | L   | 0.056      | -            | -                | -                | -         |    -1.48 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4246 | 2024-02-15 | Case              | W   | 0.056      | -            | -                | -                | -         |     0.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4250 | 2024-02-15 | KRÜ               | W   | 0.056      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4275 | 2024-02-14 | 2GAME             | W   | 0.050      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4340 | 2024-02-12 | LA RUGONETA       | W   | 0.035      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($130,413.01)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.870 | $100,000.00    | $86,962.96      |
| 2024-06-09 |      0.822 | $7,500.00      | $6,165.97       |
| 2024-06-02 |      0.775 | $20,000.00     | $15,494.44      |
| 2024-05-19 |      0.681 | $4,000.00      | $2,725.56       |
| 2024-05-16 |      0.661 | $5,000.00      | $3,306.94       |
| 2024-05-12 |      0.635 | $15,000.00     | $9,529.17       |
| 2024-04-20 |      0.489 | $5,000.00      | $2,443.98       |
| 2024-04-14 |      0.446 | $4,000.00      | $1,783.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
