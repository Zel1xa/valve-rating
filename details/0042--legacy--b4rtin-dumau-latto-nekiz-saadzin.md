### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1112.0<br />
<br />
Final Rank Value (1112.0) = Starting Rank Value (1007.0) + Head To Head Adjustments (105.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.195[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1007.0
- 400 + ( ( 0.295 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1007.0


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
|           42 |       61 | 2024-08-03 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.85 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           41 |       77 | 2024-08-03 | Solid            | W   | 1.000      | 0.143        | -                | 0.807 (0.115)    | 0 (0.000) |     9.49 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           40 |       92 | 2024-08-02 | Fluxo            | W   | 1.000      | 0.143        | 0.123 (0.018)    | -                | 0 (0.000) |    17.47 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           39 |       97 | 2024-08-02 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.82 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |      130 | 2024-08-01 | Intense          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |      178 | 2024-07-31 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.778 (0.288)    | 0 (0.000) |     8.09 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |      266 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.807 (0.115)    | 0 (0.000) |    10.45 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      310 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | -         |     3.83 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      840 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.27 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      846 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.076 (0.028)    | 0.732 (0.271)    | -         |    19.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      859 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.540 (0.200)    | -         |    12.15 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      872 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.30 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      895 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.778 (0.288)    | -         |     7.70 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      922 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.490 (0.182)    | -         |     6.82 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |     1019 | 2024-06-16 | Nouns            | W   | 0.863      | 0.371        | 0.057 (0.018)    | 0.541 (0.173)    | -         |    11.26 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |     1023 | 2024-06-16 | Elevate          | W   | 0.863      | 0.371        | 0.027 (0.009)    | 0.501 (0.160)    | -         |    11.24 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |     1052 | 2024-06-15 | Akimbo           | W   | 0.855      | -            | -                | -                | -         |     5.87 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     1086 | 2024-06-14 | Akimbo           | W   | 0.849      | -            | -                | -                | -         |     2.99 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1200 | 2024-06-10 | Akimbo           | W   | 0.823      | -            | -                | -                | -         |     5.50 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1234 | 2024-06-09 | Party Astronauts | W   | 0.817      | 0.384        | 0.041 (0.013)    | 0.510 (0.160)    | -         |    11.60 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1305 | 2024-06-08 | M80              | L   | 0.809      | -            | -                | -                | -         |    -5.21 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1360 | 2024-06-07 | Party Astronauts | L   | 0.802      | -            | -                | -                | -         |   -13.71 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1367 | 2024-06-07 | Elevate          | W   | 0.801      | -            | -                | -                | -         |    11.11 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1412 | 2024-06-06 | Mythic           | W   | 0.796      | -            | -                | -                | -         |     6.12 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1415 | 2024-06-06 | Akimbo           | W   | 0.796      | -            | -                | -                | -         |     5.28 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1481 | 2024-06-05 | Vibe             | W   | 0.790      | -            | -                | -                | -         |     0.90 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1530 | 2024-06-04 | E-Xolos LAZER    | W   | 0.783      | -            | -                | -                | -         |     5.54 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1868 | 2024-05-22 | NRG              | L   | 0.694      | -            | -                | -                | -         |   -13.63 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1896 | 2024-05-21 | Limitless        | W   | 0.689      | -            | -                | -                | -         |     4.70 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     2025 | 2024-05-17 | Party Astronauts | L   | 0.662      | -            | -                | -                | -         |   -12.93 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2729 | 2024-04-19 | M80              | L   | 0.476      | -            | -                | -                | -         |    -3.77 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2771 | 2024-04-18 | Elevate          | W   | 0.470      | -            | -                | -                | -         |     6.78 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2775 | 2024-04-18 | Liquid           | L   | 0.469      | -            | -                | -                | -         |    -0.57 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3484 | 2024-03-20 | The MongolZ      | L   | 0.273      | -            | -                | -                | -         |    -0.05 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3499 | 2024-03-19 | Apeks            | W   | 0.267      | -            | -                | -                | 1 (0.267) |     2.98 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3510 | 2024-03-18 | GamerLegion      | L   | 0.260      | -            | -                | -                | -         |    -6.48 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3523 | 2024-03-17 | Cloud9           | L   | 0.255      | -            | -                | -                | -         |    -3.90 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3533 | 2024-03-17 | FURIA            | W   | 0.254      | 0.143        | 0.284 (0.010)    | -                | 1 (0.254) |     7.85 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3869 | 2024-03-04 | M80              | W   | 0.168      | -            | -                | -                | 1 (0.168) |     4.04 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3881 | 2024-03-03 | MIBR             | W   | 0.162      | 0.143        | 0.208 (0.005)    | -                | 1 (0.162) |     4.62 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3910 | 2024-03-02 | Nouns            | W   | 0.155      | -            | -                | -                | 1 (0.155) |     1.79 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3933 | 2024-03-01 | paiN             | L   | 0.149      | -            | -                | -                | -         |    -0.47 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($38,973.84)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.863 | $10,000.00     | $8,633.80       |
| 2024-06-10 |      0.823 | $7,000.00      | $5,763.66       |
| 2024-06-09 |      0.817 | $20,000.00     | $16,331.48      |
| 2024-03-20 |      0.274 | $10,000.00     | $2,744.91       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
