### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1115.7<br />
<br />
Final Rank Value (1115.7) = Starting Rank Value (1011.5) + Head To Head Adjustments (104.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.125[<sup>2</sup>](#table1)

The average of these factors is 0.299<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1011.5
- 400 + ( ( 0.299 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1011.5


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
|           42 |        0 | 2024-08-03 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.82 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           41 |        9 | 2024-08-03 | Solid            | W   | 1.000      | 0.143        | -                | 0.835 (0.119)    | 0 (0.000) |     9.45 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           40 |       25 | 2024-08-02 | Fluxo            | W   | 1.000      | 0.143        | 0.124 (0.018)    | -                | 0 (0.000) |    17.48 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           39 |       32 | 2024-08-02 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.79 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |       63 | 2024-08-01 | Intense          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.32 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |      109 | 2024-07-31 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.804 (0.298)    | 0 (0.000) |     8.03 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |      197 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.835 (0.119)    | 0 (0.000) |    10.40 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      241 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | -         |     3.76 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      771 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.75 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      777 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.077 (0.029)    | 0.743 (0.275)    | -         |    19.43 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      789 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.556 (0.206)    | -         |    12.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      802 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      825 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.804 (0.298)    | -         |     7.58 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      852 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.504 (0.187)    | -         |     6.73 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |      949 | 2024-06-16 | Nouns            | W   | 0.881      | 0.371        | 0.057 (0.019)    | 0.547 (0.179)    | -         |    11.34 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |      953 | 2024-06-16 | Elevate          | W   | 0.880      | 0.371        | 0.027 (0.009)    | 0.505 (0.165)    | -         |    11.32 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |      982 | 2024-06-15 | Akimbo           | W   | 0.873      | -            | -                | -                | -         |     5.88 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     1016 | 2024-06-14 | Akimbo           | W   | 0.867      | -            | -                | -                | -         |     2.98 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1130 | 2024-06-10 | Akimbo           | W   | 0.841      | -            | -                | -                | -         |     5.51 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1164 | 2024-06-09 | Party Astronauts | W   | 0.834      | 0.384        | 0.041 (0.013)    | 0.532 (0.170)    | -         |    11.89 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1235 | 2024-06-08 | M80              | L   | 0.826      | -            | -                | -                | -         |    -5.31 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1290 | 2024-06-07 | Party Astronauts | L   | 0.820      | -            | -                | -                | -         |   -13.96 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1297 | 2024-06-07 | Elevate          | W   | 0.819      | -            | -                | -                | -         |    11.21 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1342 | 2024-06-06 | Mythic           | W   | 0.814      | -            | -                | -                | -         |     6.20 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1345 | 2024-06-06 | Akimbo           | W   | 0.813      | -            | -                | -                | -         |     5.29 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1411 | 2024-06-05 | Vibe             | W   | 0.807      | -            | -                | -                | -         |     0.89 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1460 | 2024-06-04 | E-Xolos LAZER    | W   | 0.801      | -            | -                | -                | -         |     5.46 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1798 | 2024-05-22 | NRG              | L   | 0.712      | -            | -                | -                | -         |   -13.99 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1826 | 2024-05-21 | Limitless        | W   | 0.707      | -            | -                | -                | -         |     4.78 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     1955 | 2024-05-17 | Party Astronauts | L   | 0.680      | -            | -                | -                | -         |   -13.28 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2658 | 2024-04-19 | M80              | L   | 0.493      | -            | -                | -                | -         |    -3.93 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2700 | 2024-04-18 | Elevate          | W   | 0.487      | -            | -                | -                | -         |     6.87 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2704 | 2024-04-18 | Liquid           | L   | 0.486      | -            | -                | -                | -         |    -0.97 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3413 | 2024-03-20 | The MongolZ      | L   | 0.290      | -            | -                | -                | -         |    -0.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3428 | 2024-03-19 | Apeks            | W   | 0.284      | -            | -                | -                | 1 (0.284) |     3.20 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3439 | 2024-03-18 | GamerLegion      | L   | 0.277      | -            | -                | -                | -         |    -6.86 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3452 | 2024-03-17 | Cloud9           | L   | 0.273      | -            | -                | -                | -         |    -4.17 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3462 | 2024-03-17 | FURIA            | W   | 0.271      | 0.143        | 0.284 (0.011)    | -                | 1 (0.271) |     8.38 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3797 | 2024-03-04 | M80              | W   | 0.185      | -            | -                | -                | 1 (0.185) |     4.45 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3809 | 2024-03-03 | MIBR             | W   | 0.180      | 0.143        | 0.210 (0.005)    | -                | 1 (0.180) |     5.12 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3838 | 2024-03-02 | Nouns            | W   | 0.173      | -            | -                | -                | 1 (0.173) |     1.99 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3861 | 2024-03-01 | paiN             | L   | 0.166      | -            | -                | -                | -         |    -0.50 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,787.64)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.881 | $10,000.00     | $8,806.94       |
| 2024-06-10 |      0.841 | $7,000.00      | $5,884.86       |
| 2024-06-09 |      0.834 | $20,000.00     | $16,677.78      |
| 2024-03-20 |      0.292 | $10,000.00     | $2,918.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
