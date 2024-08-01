### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1114.2<br />
<br />
Final Rank Value (1114.2) = Starting Rank Value (1020.1) + Head To Head Adjustments (94.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.520[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.135[<sup>2</sup>](#table1)

The average of these factors is 0.301<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1020.1
- 400 + ( ( 0.301 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1020.1


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
|           39 |       22 | 2024-07-31 | Case             | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.721 (0.267)    | 0 (0.000) |     7.36 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |      112 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.843 (0.120)    | 0 (0.000) |     9.75 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |      156 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.77 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |      702 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.69 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      709 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.075 (0.028)    | 0.753 (0.279)    | 0 (0.000) |    15.16 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      722 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.511 (0.189)    | 0 (0.000) |    11.00 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      735 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.56 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      758 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.721 (0.267)    | -         |     6.41 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      785 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.459 (0.170)    | -         |     6.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      883 | 2024-06-16 | Nouns            | W   | 0.897      | 0.371        | 0.058 (0.019)    | 0.557 (0.185)    | -         |    10.69 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      886 | 2024-06-16 | Elevate          | W   | 0.896      | 0.371        | 0.027 (0.009)    | 0.505 (0.168)    | -         |    10.38 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |      912 | 2024-06-15 | Akimbo           | W   | 0.889      | -            | -                | -                | -         |     5.42 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |      942 | 2024-06-14 | Akimbo           | W   | 0.883      | -            | -                | -                | -         |     2.80 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |     1053 | 2024-06-10 | Akimbo           | W   | 0.857      | -            | -                | -                | -         |     5.05 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     1088 | 2024-06-09 | Party Astronauts | W   | 0.850      | 0.384        | 0.042 (0.014)    | 0.532 (0.174)    | -         |    11.32 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1152 | 2024-06-08 | Nouns            | W   | 0.843      | 0.384        | 0.058 (0.019)    | 0.557 (0.180)    | -         |    11.79 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1161 | 2024-06-08 | M80              | L   | 0.842      | -            | -                | -                | -         |    -5.51 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1216 | 2024-06-07 | Elevate          | W   | 0.836      | -            | -                | -                | -         |    11.13 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1222 | 2024-06-07 | Party Astronauts | L   | 0.836      | -            | -                | -                | -         |   -14.20 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1230 | 2024-06-07 | Elevate          | W   | 0.835      | -            | -                | -                | -         |    11.44 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1276 | 2024-06-06 | Mythic           | W   | 0.830      | -            | -                | -                | -         |     6.28 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1279 | 2024-06-06 | Akimbo           | W   | 0.829      | -            | -                | -                | -         |     5.34 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1347 | 2024-06-05 | Vibe             | W   | 0.823      | -            | -                | -                | -         |     0.87 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1398 | 2024-06-04 | E-Xolos LAZER    | W   | 0.817      | -            | -                | -                | -         |     5.51 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1739 | 2024-05-22 | NRG              | L   | 0.728      | -            | -                | -                | -         |   -14.19 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1779 | 2024-05-21 | Limitless        | W   | 0.723      | -            | -                | -                | -         |     4.84 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     1922 | 2024-05-17 | Party Astronauts | L   | 0.696      | -            | -                | -                | -         |   -13.62 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2646 | 2024-04-19 | M80              | L   | 0.509      | -            | -                | -                | -         |    -3.98 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2689 | 2024-04-18 | Elevate          | W   | 0.504      | -            | -                | -                | -         |     7.13 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2693 | 2024-04-18 | Liquid           | L   | 0.503      | -            | -                | -                | -         |    -1.33 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3419 | 2024-03-20 | The MongolZ      | L   | 0.307      | -            | -                | -                | -         |    -0.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3434 | 2024-03-19 | Apeks            | W   | 0.301      | -            | -                | -                | 1 (0.301) |     3.43 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3445 | 2024-03-18 | GamerLegion      | L   | 0.294      | -            | -                | -                | -         |    -7.22 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3458 | 2024-03-17 | Cloud9           | L   | 0.289      | -            | -                | -                | -         |    -4.25 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3468 | 2024-03-17 | FURIA            | W   | 0.288      | 0.143        | 0.286 (0.012)    | -                | 1 (0.288) |     8.89 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3815 | 2024-03-04 | M80              | W   | 0.202      | -            | -                | -                | 1 (0.202) |     4.89 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3827 | 2024-03-03 | MIBR             | W   | 0.196      | 0.143        | 0.201 (0.006)    | -                | 1 (0.196) |     5.55 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3856 | 2024-03-02 | Nouns            | W   | 0.189      | -            | -                | -                | 1 (0.189) |     2.16 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3880 | 2024-03-01 | paiN             | L   | 0.183      | -            | -                | -                | -         |    -0.74 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,057.92)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.897 | $10,000.00     | $8,970.83       |
| 2024-06-10 |      0.857 | $7,000.00      | $5,999.58       |
| 2024-06-09 |      0.850 | $20,000.00     | $17,005.56      |
| 2024-03-20 |      0.308 | $10,000.00     | $3,081.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
