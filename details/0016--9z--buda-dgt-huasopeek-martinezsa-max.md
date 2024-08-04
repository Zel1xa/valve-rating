### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1449.7<br />
<br />
Final Rank Value (1449.7) = Starting Rank Value (1553.8) + Head To Head Adjustments (-104.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.718[<sup>1</sup>](#table2)
- Bounty Collected: 0.554[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.710[<sup>2</sup>](#table1)

The average of these factors is 0.564<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1553.8
- 400 + ( ( 0.564 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1553.8


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
|           60 |      301 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      360 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.501 (0.218)    | 0 (0.000) |     1.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |      986 | 2024-06-16 | fnatic            | W   | 0.876      | 0.548        | 0.371 (0.178)    | 0.708 (0.340)    | 1 (0.876) |    13.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |      997 | 2024-06-16 | KOI               | W   | 0.874      | -            | -                | -                | 1 (0.874) |     3.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1018 | 2024-06-15 | paiN              | W   | 0.868      | 0.548        | 0.327 (0.156)    | 0.867 (0.412)    | 1 (0.868) |    10.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1037 | 2024-06-15 | BESTIA            | W   | 0.866      | 0.548        | 0.095 (0.045)    | 0.801 (0.380)    | 1 (0.866) |     2.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1056 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.861      | -            | -                | -                | -         |    -8.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1266 | 2024-06-08 | Imperial          | L   | 0.822      | -            | -                | -                | -         |   -19.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1323 | 2024-06-07 | Sharks            | W   | 0.815      | 0.450        | -                | 0.565 (0.207)    | 0 (0.000) |     2.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1381 | 2024-06-06 | MIBR              | W   | 0.809      | 0.450        | 0.209 (0.076)    | 0.659 (0.240)    | -         |    12.12 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1450 | 2024-06-05 | RED Canids        | L   | 0.802      | -            | -                | -                | -         |   -21.71 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1500 | 2024-06-04 | Fluxo             | W   | 0.795      | 0.450        | 0.124 (0.044)    | 0.724 (0.259)    | -         |     2.44 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1581 | 2024-06-01 | G2                | L   | 0.775      | -            | -                | -                | -         |    -1.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1671 | 2024-05-29 | Vitality          | W   | 0.755      | 0.624        | 0.649 (0.306)    | -                | 1 (0.755) |    21.49 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1711 | 2024-05-27 | Liquid            | W   | 0.743      | 0.624        | 0.384 (0.178)    | 0.460 (0.213)    | 1 (0.743) |    16.60 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1721 | 2024-05-27 | MOUZ              | W   | 0.741      | 0.624        | 1.000 (0.463)    | -                | 1 (0.741) |    21.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1816 | 2024-05-22 | Imperial          | L   | 0.709      | -            | -                | -                | -         |   -15.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1820 | 2024-05-22 | Imperial          | L   | 0.709      | -            | -                | -                | -         |   -16.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1899 | 2024-05-20 | W7M               | W   | 0.695      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1902 | 2024-05-20 | W7M               | W   | 0.695      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1903 | 2024-05-20 | BESTIA            | L   | 0.695      | -            | -                | -                | -         |   -20.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1906 | 2024-05-20 | BESTIA            | W   | 0.694      | 0.450        | -                | 0.801 (0.250)    | -         |     1.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1933 | 2024-05-19 | RED Canids        | L   | 0.687      | -            | -                | -                | -         |   -18.89 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1958 | 2024-05-18 | Fluxo             | W   | 0.681      | -            | -                | -                | -         |     2.26 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2023 | 2024-05-16 | ODDIK             | W   | 0.669      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2031 | 2024-05-16 | Imperial          | L   | 0.667      | -            | -                | -                | -         |   -15.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2068 | 2024-05-15 | RED Canids        | W   | 0.663      | 0.450        | -                | 0.758 (0.226)    | -         |     2.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2070 | 2024-05-15 | RED Canids        | L   | 0.662      | -            | -                | -                | -         |   -18.91 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2077 | 2024-05-15 | Sharks            | W   | 0.661      | -            | -                | -                | -         |     1.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2129 | 2024-05-14 | Smoke             | W   | 0.655      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2133 | 2024-05-14 | Smoke             | W   | 0.655      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2143 | 2024-05-14 | Galorys           | W   | 0.654      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2162 | 2024-05-13 | Galorys           | W   | 0.649      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2181 | 2024-05-12 | inSanitY          | W   | 0.642      | -            | -                | -                | -         |     0.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2186 | 2024-05-12 | paiN              | L   | 0.641      | -            | -                | -                | -         |   -13.78 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2213 | 2024-05-11 | KRÜ               | W   | 0.635      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2240 | 2024-05-10 | inSanitY          | W   | 0.629      | -            | -                | -                | -         |     0.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2282 | 2024-05-08 | Sharks            | W   | 0.615      | -            | -                | -                | -         |     0.90 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2324 | 2024-05-06 | Vikings KR        | W   | 0.600      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2416 | 2024-05-01 | Case              | W   | 0.568      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2417 | 2024-05-01 | Case              | W   | 0.568      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2688 | 2024-04-19 | OG                | L   | 0.489      | -            | -                | -                | -         |   -14.42 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2738 | 2024-04-18 | Imperial          | L   | 0.482      | -            | -                | -                | -         |   -12.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2744 | 2024-04-18 | FURIA             | W   | 0.481      | 0.589        | 0.284 (0.080)    | -                | 1 (0.481) |    10.27 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3067 | 2024-04-08 | HEROIC            | L   | 0.412      | -            | -                | -                | -         |    -6.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3077 | 2024-04-07 | G2                | L   | 0.410      | -            | -                | -                | -         |    -1.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4036 | 2024-02-23 | FURIA             | W   | 0.116      | -            | -                | -                | -         |     2.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4039 | 2024-02-23 | BESTIA            | W   | 0.114      | -            | -                | -                | -         |     0.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4050 | 2024-02-22 | FURIA             | L   | 0.109      | -            | -                | -                | -         |    -0.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4056 | 2024-02-22 | BESTIA            | W   | 0.108      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4101 | 2024-02-20 | Solid             | W   | 0.095      | -            | -                | -                | -         |     0.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4104 | 2024-02-20 | Case              | W   | 0.095      | -            | -                | -                | -         |     0.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4108 | 2024-02-20 | Salao do Corte    | W   | 0.095      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4160 | 2024-02-18 | LA RUGONETA       | L   | 0.080      | -            | -                | -                | -         |    -2.50 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4202 | 2024-02-16 | Fluxo             | L   | 0.068      | -            | -                | -                | -         |    -2.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4227 | 2024-02-15 | Imperial          | L   | 0.062      | -            | -                | -                | -         |    -1.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4228 | 2024-02-15 | Case              | W   | 0.062      | -            | -                | -                | -         |     0.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4232 | 2024-02-15 | KRÜ               | W   | 0.062      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4257 | 2024-02-14 | 2GAME             | W   | 0.056      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4322 | 2024-02-12 | LA RUGONETA       | W   | 0.041      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($131,378.98)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.41) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.876 | $100,000.00    | $87,564.81      |
| 2024-06-09 |      0.828 | $7,500.00      | $6,211.11       |
| 2024-06-02 |      0.781 | $20,000.00     | $15,614.81      |
| 2024-05-19 |      0.687 | $4,000.00      | $2,749.63       |
| 2024-05-16 |      0.667 | $5,000.00      | $3,337.04       |
| 2024-05-12 |      0.641 | $15,000.00     | $9,619.44       |
| 2024-04-20 |      0.495 | $5,000.00      | $2,474.07       |
| 2024-04-14 |      0.452 | $4,000.00      | $1,808.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
