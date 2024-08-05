### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1085.3<br />
<br />
Final Rank Value (1085.3) = Starting Rank Value (1003.5) + Head To Head Adjustments (81.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.519[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.138[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1003.5
- 400 + ( ( 0.293 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1003.5


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
|           36 |       83 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.817 (0.117)    | 0 (0.000) |    10.31 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      127 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.79 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      657 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.41 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      663 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.079 (0.029)    | 0.738 (0.274)    | 0 (0.000) |    19.77 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      676 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.471 (0.175)    | 0 (0.000) |    12.16 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      689 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.42 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      712 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.720 (0.267)    | 0 (0.000) |     7.58 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      739 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.458 (0.170)    | -         |     6.73 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |      836 | 2024-06-16 | Nouns            | W   | 0.901      | 0.371        | 0.058 (0.019)    | 0.546 (0.182)    | -         |    11.91 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |      840 | 2024-06-16 | Elevate          | W   | 0.901      | 0.371        | 0.027 (0.009)    | 0.505 (0.169)    | -         |    11.85 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |      869 | 2024-06-15 | Akimbo           | W   | 0.893      | 0.371        | 0.015 (0.005)    | 0.276 (0.091)    | -         |     6.19 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |      903 | 2024-06-14 | Akimbo           | W   | 0.888      | -            | -                | -                | -         |     3.14 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1017 | 2024-06-10 | Akimbo           | W   | 0.861      | -            | -                | -                | -         |     5.82 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1051 | 2024-06-09 | Party Astronauts | W   | 0.855      | 0.384        | 0.041 (0.014)    | 0.533 (0.175)    | -         |    12.49 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1122 | 2024-06-08 | M80              | L   | 0.847      | -            | -                | -                | -         |    -5.05 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1177 | 2024-06-07 | Party Astronauts | L   | 0.840      | -            | -                | -                | -         |   -13.94 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1184 | 2024-06-07 | Elevate          | W   | 0.839      | -            | -                | -                | -         |    11.85 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1229 | 2024-06-06 | Mythic           | W   | 0.834      | -            | -                | -                | -         |     6.59 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1232 | 2024-06-06 | Akimbo           | W   | 0.834      | -            | -                | -                | -         |     5.66 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1298 | 2024-06-05 | Vibe             | W   | 0.828      | -            | -                | -                | -         |     0.94 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1347 | 2024-06-04 | E-Xolos LAZER    | W   | 0.821      | 0.368        | -                | 0.347 (0.105)    | -         |     5.34 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1685 | 2024-05-22 | NRG              | L   | 0.732      | -            | -                | -                | -         |   -14.16 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1713 | 2024-05-21 | Limitless        | W   | 0.727      | -            | -                | -                | -         |     5.15 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     1842 | 2024-05-17 | Party Astronauts | L   | 0.700      | -            | -                | -                | -         |   -13.36 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2546 | 2024-04-19 | M80              | L   | 0.514      | -            | -                | -                | -         |    -3.76 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2588 | 2024-04-18 | Elevate          | W   | 0.508      | -            | -                | -                | -         |     7.48 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2592 | 2024-04-18 | Liquid           | L   | 0.507      | -            | -                | -                | -         |    -1.09 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3301 | 2024-03-20 | The MongolZ      | L   | 0.311      | -            | -                | -                | -         |    -0.05 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3316 | 2024-03-19 | Apeks            | W   | 0.305      | -            | -                | -                | 1 (0.305) |     3.76 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3327 | 2024-03-18 | GamerLegion      | L   | 0.298      | -            | -                | -                | -         |    -7.13 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3340 | 2024-03-17 | Cloud9           | L   | 0.293      | -            | -                | -                | -         |    -4.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3350 | 2024-03-17 | FURIA            | W   | 0.292      | 0.143        | 0.284 (0.012)    | -                | 1 (0.292) |     9.05 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3686 | 2024-03-04 | M80              | W   | 0.206      | 0.143        | 0.189 (0.006)    | -                | 1 (0.206) |     5.11 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3698 | 2024-03-03 | MIBR             | W   | 0.200      | 0.143        | 0.200 (0.006)    | -                | 1 (0.200) |     5.76 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3727 | 2024-03-02 | Nouns            | W   | 0.193      | -            | -                | -                | 1 (0.193) |     2.34 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3750 | 2024-03-01 | paiN             | L   | 0.187      | -            | -                | -                | -         |    -0.50 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,261.80)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.901 | $10,000.00     | $9,014.21       |
| 2024-06-10 |      0.861 | $7,000.00      | $6,029.95       |
| 2024-06-09 |      0.855 | $20,000.00     | $17,092.31      |
| 2024-03-20 |      0.313 | $10,000.00     | $3,125.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
