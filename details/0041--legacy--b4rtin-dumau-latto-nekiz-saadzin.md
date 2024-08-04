### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1115.5<br />
<br />
Final Rank Value (1115.5) = Starting Rank Value (1010.7) + Head To Head Adjustments (104.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.123[<sup>2</sup>](#table1)

The average of these factors is 0.299<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1010.7
- 400 + ( ( 0.299 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1010.7


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
|           42 |        8 | 2024-08-03 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.82 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           41 |       19 | 2024-08-03 | Solid            | W   | 1.000      | 0.143        | -                | 0.835 (0.119)    | 0 (0.000) |     9.45 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           40 |       36 | 2024-08-02 | Fluxo            | W   | 1.000      | 0.143        | 0.124 (0.018)    | -                | 0 (0.000) |    17.48 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           39 |       42 | 2024-08-02 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.79 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |       74 | 2024-08-01 | Intense          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.33 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |      120 | 2024-07-31 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.805 (0.298)    | 0 (0.000) |     8.03 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |      208 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.835 (0.119)    | 0 (0.000) |    10.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      252 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | -         |     3.77 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      782 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.34 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      788 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.077 (0.029)    | 0.743 (0.275)    | -         |    19.43 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      801 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.557 (0.206)    | -         |    12.12 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      814 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.37 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      837 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.805 (0.298)    | -         |     7.61 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      864 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.505 (0.187)    | -         |     6.75 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |      961 | 2024-06-16 | Nouns            | W   | 0.877      | 0.371        | 0.057 (0.019)    | 0.548 (0.178)    | -         |    11.30 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |      965 | 2024-06-16 | Elevate          | W   | 0.876      | 0.371        | 0.027 (0.009)    | 0.505 (0.164)    | -         |    11.29 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |      994 | 2024-06-15 | Akimbo           | W   | 0.869      | -            | -                | -                | -         |     5.87 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     1028 | 2024-06-14 | Akimbo           | W   | 0.863      | -            | -                | -                | -         |     2.97 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1142 | 2024-06-10 | Akimbo           | W   | 0.837      | -            | -                | -                | -         |     5.50 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1176 | 2024-06-09 | Party Astronauts | W   | 0.830      | 0.384        | 0.041 (0.013)    | 0.531 (0.170)    | -         |    11.84 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1247 | 2024-06-08 | M80              | L   | 0.822      | -            | -                | -                | -         |    -5.25 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1302 | 2024-06-07 | Party Astronauts | L   | 0.816      | -            | -                | -                | -         |   -13.90 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1309 | 2024-06-07 | Elevate          | W   | 0.815      | -            | -                | -                | -         |    11.17 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1354 | 2024-06-06 | Mythic           | W   | 0.810      | -            | -                | -                | -         |     6.17 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1357 | 2024-06-06 | Akimbo           | W   | 0.809      | -            | -                | -                | -         |     5.27 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1423 | 2024-06-05 | Vibe             | W   | 0.803      | -            | -                | -                | -         |     0.89 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1472 | 2024-06-04 | E-Xolos LAZER    | W   | 0.797      | -            | -                | -                | -         |     5.45 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1810 | 2024-05-22 | NRG              | L   | 0.708      | -            | -                | -                | -         |   -13.91 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1838 | 2024-05-21 | Limitless        | W   | 0.703      | -            | -                | -                | -         |     4.76 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     1967 | 2024-05-17 | Party Astronauts | L   | 0.676      | -            | -                | -                | -         |   -13.20 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2671 | 2024-04-19 | M80              | L   | 0.489      | -            | -                | -                | -         |    -3.88 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2713 | 2024-04-18 | Elevate          | W   | 0.484      | -            | -                | -                | -         |     6.83 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2717 | 2024-04-18 | Liquid           | L   | 0.482      | -            | -                | -                | -         |    -0.60 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3426 | 2024-03-20 | The MongolZ      | L   | 0.287      | -            | -                | -                | -         |    -0.05 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3441 | 2024-03-19 | Apeks            | W   | 0.280      | -            | -                | -                | 1 (0.280) |     3.14 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3452 | 2024-03-18 | GamerLegion      | L   | 0.273      | -            | -                | -                | -         |    -6.80 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3465 | 2024-03-17 | Cloud9           | L   | 0.269      | -            | -                | -                | -         |    -4.14 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3475 | 2024-03-17 | FURIA            | W   | 0.268      | 0.143        | 0.284 (0.011)    | -                | 1 (0.268) |     8.27 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3811 | 2024-03-04 | M80              | W   | 0.181      | -            | -                | -                | 1 (0.181) |     4.37 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3823 | 2024-03-03 | MIBR             | W   | 0.176      | 0.143        | 0.209 (0.005)    | -                | 1 (0.176) |     5.01 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3852 | 2024-03-02 | Nouns            | W   | 0.169      | -            | -                | -                | 1 (0.169) |     1.95 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3875 | 2024-03-01 | paiN             | L   | 0.162      | -            | -                | -                | -         |    -0.49 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,610.30)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.877 | $10,000.00     | $8,769.21       |
| 2024-06-10 |      0.837 | $7,000.00      | $5,858.45       |
| 2024-06-09 |      0.830 | $20,000.00     | $16,602.31      |
| 2024-03-20 |      0.288 | $10,000.00     | $2,880.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
