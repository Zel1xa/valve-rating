### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1115.5<br />
<br />
Final Rank Value (1115.5) = Starting Rank Value (1010.8) + Head To Head Adjustments (104.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.123[<sup>2</sup>](#table1)

The average of these factors is 0.299<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1010.8
- 400 + ( ( 0.299 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1010.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |        2 | 2024-08-03 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.83 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           41 |       12 | 2024-08-03 | Solid            | W   | 1.000      | 0.143        | -                | 0.835 (0.119)    | 0 (0.000) |     9.45 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           40 |       28 | 2024-08-02 | Fluxo            | W   | 1.000      | 0.143        | 0.124 (0.018)    | -                | 0 (0.000) |    17.48 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           39 |       34 | 2024-08-02 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.80 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |       66 | 2024-08-01 | Intense          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.33 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |      112 | 2024-07-31 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.805 (0.298)    | 0 (0.000) |     8.03 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |      200 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.835 (0.119)    | 0 (0.000) |    10.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      244 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | -         |     3.77 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      774 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.34 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      780 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.077 (0.029)    | 0.743 (0.275)    | -         |    19.43 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      793 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.557 (0.206)    | -         |    12.13 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      806 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.36 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      829 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.805 (0.298)    | -         |     7.62 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      856 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.505 (0.187)    | -         |     6.76 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |      953 | 2024-06-16 | Nouns            | W   | 0.878      | 0.371        | 0.057 (0.019)    | 0.548 (0.178)    | -         |    11.32 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |      957 | 2024-06-16 | Elevate          | W   | 0.877      | 0.371        | 0.027 (0.009)    | 0.505 (0.164)    | -         |    11.30 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |      986 | 2024-06-15 | Akimbo           | W   | 0.870      | -            | -                | -                | -         |     5.87 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     1020 | 2024-06-14 | Akimbo           | W   | 0.864      | -            | -                | -                | -         |     2.98 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1134 | 2024-06-10 | Akimbo           | W   | 0.838      | -            | -                | -                | -         |     5.50 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1168 | 2024-06-09 | Party Astronauts | W   | 0.831      | 0.384        | 0.041 (0.013)    | 0.531 (0.170)    | -         |    11.85 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1239 | 2024-06-08 | M80              | L   | 0.823      | -            | -                | -                | -         |    -5.29 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1294 | 2024-06-07 | Party Astronauts | L   | 0.817      | -            | -                | -                | -         |   -13.90 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1301 | 2024-06-07 | Elevate          | W   | 0.816      | -            | -                | -                | -         |    11.19 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1346 | 2024-06-06 | Mythic           | W   | 0.811      | -            | -                | -                | -         |     6.18 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1349 | 2024-06-06 | Akimbo           | W   | 0.810      | -            | -                | -                | -         |     5.28 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1415 | 2024-06-05 | Vibe             | W   | 0.804      | -            | -                | -                | -         |     0.89 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1464 | 2024-06-04 | E-Xolos LAZER    | W   | 0.798      | -            | -                | -                | -         |     5.46 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1802 | 2024-05-22 | NRG              | L   | 0.709      | -            | -                | -                | -         |   -13.92 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1830 | 2024-05-21 | Limitless        | W   | 0.704      | -            | -                | -                | -         |     4.77 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     1959 | 2024-05-17 | Party Astronauts | L   | 0.677      | -            | -                | -                | -         |   -13.21 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2663 | 2024-04-19 | M80              | L   | 0.490      | -            | -                | -                | -         |    -3.90 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2705 | 2024-04-18 | Elevate          | W   | 0.484      | -            | -                | -                | -         |     6.84 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2709 | 2024-04-18 | Liquid           | L   | 0.483      | -            | -                | -                | -         |    -0.96 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3418 | 2024-03-20 | The MongolZ      | L   | 0.287      | -            | -                | -                | -         |    -0.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3433 | 2024-03-19 | Apeks            | W   | 0.281      | -            | -                | -                | 1 (0.281) |     3.15 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3444 | 2024-03-18 | GamerLegion      | L   | 0.274      | -            | -                | -                | -         |    -6.79 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3457 | 2024-03-17 | Cloud9           | L   | 0.270      | -            | -                | -                | -         |    -4.14 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3467 | 2024-03-17 | FURIA            | W   | 0.268      | 0.143        | 0.284 (0.011)    | -                | 1 (0.268) |     8.29 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3803 | 2024-03-04 | M80              | W   | 0.182      | -            | -                | -                | 1 (0.182) |     4.38 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3815 | 2024-03-03 | MIBR             | W   | 0.176      | 0.143        | 0.209 (0.005)    | -                | 1 (0.176) |     5.04 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3844 | 2024-03-02 | Nouns            | W   | 0.170      | -            | -                | -                | 1 (0.170) |     1.95 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3867 | 2024-03-01 | paiN             | L   | 0.163      | -            | -                | -                | -         |    -0.49 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,644.03)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.878 | $10,000.00     | $8,776.39       |
| 2024-06-10 |      0.838 | $7,000.00      | $5,863.47       |
| 2024-06-09 |      0.831 | $20,000.00     | $16,616.67      |
| 2024-03-20 |      0.289 | $10,000.00     | $2,887.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
