### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1113.4<br />
<br />
Final Rank Value (1113.4) = Starting Rank Value (1019.0) + Head To Head Adjustments (94.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.520[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.135[<sup>2</sup>](#table1)

The average of these factors is 0.301<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1019.0
- 400 + ( ( 0.301 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1019.0


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
|           39 |       26 | 2024-07-31 | Case             | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.722 (0.267)    | 0 (0.000) |     7.36 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |      116 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.844 (0.121)    | 0 (0.000) |     9.75 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |      160 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.78 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |      706 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.69 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      713 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.075 (0.028)    | 0.754 (0.279)    | 0 (0.000) |    15.16 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      726 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.511 (0.190)    | 0 (0.000) |    11.00 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      739 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.56 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      762 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.722 (0.267)    | -         |     6.42 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      789 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.459 (0.170)    | -         |     6.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      887 | 2024-06-16 | Nouns            | W   | 0.896      | 0.371        | 0.058 (0.019)    | 0.557 (0.185)    | -         |    10.68 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      890 | 2024-06-16 | Elevate          | W   | 0.895      | 0.371        | 0.027 (0.009)    | 0.505 (0.168)    | -         |    10.36 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |      916 | 2024-06-15 | Akimbo           | W   | 0.888      | -            | -                | -                | -         |     5.42 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |      946 | 2024-06-14 | Akimbo           | W   | 0.882      | -            | -                | -                | -         |     2.80 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |     1057 | 2024-06-10 | Akimbo           | W   | 0.856      | -            | -                | -                | -         |     5.05 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     1092 | 2024-06-09 | Party Astronauts | W   | 0.849      | 0.384        | 0.042 (0.014)    | 0.532 (0.174)    | -         |    11.31 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1156 | 2024-06-08 | Nouns            | W   | 0.842      | 0.384        | 0.058 (0.019)    | 0.557 (0.180)    | -         |    11.77 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1165 | 2024-06-08 | M80              | L   | 0.841      | -            | -                | -                | -         |    -5.48 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1220 | 2024-06-07 | Elevate          | W   | 0.835      | -            | -                | -                | -         |    11.12 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1226 | 2024-06-07 | Party Astronauts | L   | 0.835      | -            | -                | -                | -         |   -14.17 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1234 | 2024-06-07 | Elevate          | W   | 0.834      | -            | -                | -                | -         |    11.42 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1280 | 2024-06-06 | Mythic           | W   | 0.829      | -            | -                | -                | -         |     6.27 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1283 | 2024-06-06 | Akimbo           | W   | 0.828      | -            | -                | -                | -         |     5.34 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1351 | 2024-06-05 | Vibe             | W   | 0.822      | -            | -                | -                | -         |     0.87 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1402 | 2024-06-04 | E-Xolos LAZER    | W   | 0.816      | -            | -                | -                | -         |     5.51 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1743 | 2024-05-22 | NRG              | L   | 0.727      | -            | -                | -                | -         |   -14.16 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1783 | 2024-05-21 | Limitless        | W   | 0.722      | -            | -                | -                | -         |     4.83 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     1926 | 2024-05-17 | Party Astronauts | L   | 0.695      | -            | -                | -                | -         |   -13.59 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2650 | 2024-04-19 | M80              | L   | 0.508      | -            | -                | -                | -         |    -3.96 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2693 | 2024-04-18 | Elevate          | W   | 0.502      | -            | -                | -                | -         |     7.11 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2697 | 2024-04-18 | Liquid           | L   | 0.501      | -            | -                | -                | -         |    -0.92 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3423 | 2024-03-20 | The MongolZ      | L   | 0.305      | -            | -                | -                | -         |    -0.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3438 | 2024-03-19 | Apeks            | W   | 0.299      | -            | -                | -                | 1 (0.299) |     3.42 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3449 | 2024-03-18 | GamerLegion      | L   | 0.292      | -            | -                | -                | -         |    -7.19 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3462 | 2024-03-17 | Cloud9           | L   | 0.288      | -            | -                | -                | -         |    -4.24 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3472 | 2024-03-17 | FURIA            | W   | 0.286      | 0.143        | 0.286 (0.012)    | -                | 1 (0.286) |     8.85 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3819 | 2024-03-04 | M80              | W   | 0.200      | -            | -                | -                | 1 (0.200) |     4.86 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3831 | 2024-03-03 | MIBR             | W   | 0.195      | 0.143        | 0.201 (0.006)    | -                | 1 (0.195) |     5.51 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3860 | 2024-03-02 | Nouns            | W   | 0.188      | -            | -                | -                | 1 (0.188) |     2.15 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3884 | 2024-03-01 | paiN             | L   | 0.181      | -            | -                | -                | -         |    -0.74 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($38,992.64)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.896 | $10,000.00     | $8,956.94       |
| 2024-06-10 |      0.856 | $7,000.00      | $5,989.86       |
| 2024-06-09 |      0.849 | $20,000.00     | $16,977.78      |
| 2024-03-20 |      0.307 | $10,000.00     | $3,068.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
