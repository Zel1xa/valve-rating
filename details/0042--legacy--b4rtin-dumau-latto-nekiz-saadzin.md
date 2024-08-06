### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1111.9<br />
<br />
Final Rank Value (1111.9) = Starting Rank Value (1006.9) + Head To Head Adjustments (105.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.195[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1006.9
- 400 + ( ( 0.295 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1006.9


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
|           42 |       71 | 2024-08-03 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.85 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           41 |       87 | 2024-08-03 | Solid            | W   | 1.000      | 0.143        | -                | 0.807 (0.115)    | 0 (0.000) |     9.49 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           40 |      104 | 2024-08-02 | Fluxo            | W   | 1.000      | 0.143        | 0.123 (0.018)    | -                | 0 (0.000) |    17.48 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           39 |      109 | 2024-08-02 | paiN             | L   | 1.000      | -            | -                | -                | -         |    -4.82 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |      142 | 2024-08-01 | Intense          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |      190 | 2024-07-31 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.778 (0.288)    | 0 (0.000) |     8.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |      278 | 2024-07-29 | Solid            | W   | 1.000      | 0.143        | -                | 0.807 (0.115)    | 0 (0.000) |    10.46 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |      322 | 2024-07-28 | Smoke            | W   | 1.000      | -            | -                | -                | -         |     3.84 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |      852 | 2024-07-14 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -17.27 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      858 | 2024-07-13 | RED Canids       | W   | 1.000      | 0.371        | 0.076 (0.028)    | 0.732 (0.271)    | -         |    19.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      871 | 2024-07-12 | Bounty Hunters   | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.540 (0.200)    | -         |    12.15 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |      884 | 2024-07-11 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -18.29 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |      907 | 2024-07-10 | Case             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.778 (0.288)    | -         |     7.70 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |      934 | 2024-07-09 | Vikings KR       | W   | 1.000      | 0.371        | -                | 0.490 (0.182)    | -         |     6.82 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |     1031 | 2024-06-16 | Nouns            | W   | 0.863      | 0.371        | 0.057 (0.018)    | 0.541 (0.173)    | -         |    11.26 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |     1035 | 2024-06-16 | Elevate          | W   | 0.862      | 0.371        | 0.027 (0.009)    | 0.501 (0.160)    | -         |    11.24 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |     1064 | 2024-06-15 | Akimbo           | W   | 0.855      | -            | -                | -                | -         |     5.87 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     1098 | 2024-06-14 | Akimbo           | W   | 0.849      | -            | -                | -                | -         |     2.99 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     1212 | 2024-06-10 | Akimbo           | W   | 0.823      | -            | -                | -                | -         |     5.50 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     1246 | 2024-06-09 | Party Astronauts | W   | 0.816      | 0.384        | 0.041 (0.013)    | 0.510 (0.160)    | -         |    11.59 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     1317 | 2024-06-08 | M80              | L   | 0.808      | -            | -                | -                | -         |    -5.21 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     1372 | 2024-06-07 | Party Astronauts | L   | 0.802      | -            | -                | -                | -         |   -13.70 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     1379 | 2024-06-07 | Elevate          | W   | 0.801      | -            | -                | -                | -         |    11.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     1424 | 2024-06-06 | Mythic           | W   | 0.796      | -            | -                | -                | -         |     6.12 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     1427 | 2024-06-06 | Akimbo           | W   | 0.795      | -            | -                | -                | -         |     5.27 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     1493 | 2024-06-05 | Vibe             | W   | 0.789      | -            | -                | -                | -         |     0.90 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     1542 | 2024-06-04 | E-Xolos LAZER    | W   | 0.783      | -            | -                | -                | -         |     5.54 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     1880 | 2024-05-22 | NRG              | L   | 0.694      | -            | -                | -                | -         |   -13.62 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     1908 | 2024-05-21 | Limitless        | W   | 0.689      | -            | -                | -                | -         |     4.70 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     2037 | 2024-05-17 | Party Astronauts | L   | 0.662      | -            | -                | -                | -         |   -12.92 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2741 | 2024-04-19 | M80              | L   | 0.475      | -            | -                | -                | -         |    -3.77 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           11 |     2783 | 2024-04-18 | Elevate          | W   | 0.470      | -            | -                | -                | -         |     6.77 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           10 |     2787 | 2024-04-18 | Liquid           | L   | 0.468      | -            | -                | -                | -         |    -0.57 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            9 |     3496 | 2024-03-20 | The MongolZ      | L   | 0.273      | -            | -                | -                | -         |    -0.05 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     3511 | 2024-03-19 | Apeks            | W   | 0.266      | -            | -                | -                | 1 (0.266) |     2.98 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     3522 | 2024-03-18 | GamerLegion      | L   | 0.259      | -            | -                | -                | -         |    -6.47 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     3535 | 2024-03-17 | Cloud9           | L   | 0.255      | -            | -                | -                | -         |    -3.90 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     3545 | 2024-03-17 | FURIA            | W   | 0.254      | 0.143        | 0.284 (0.010)    | -                | 1 (0.254) |     7.84 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     3881 | 2024-03-04 | M80              | W   | 0.167      | -            | -                | -                | 1 (0.167) |     4.03 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     3893 | 2024-03-03 | MIBR             | W   | 0.162      | 0.143        | 0.208 (0.005)    | -                | 1 (0.162) |     4.61 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     3922 | 2024-03-02 | Nouns            | W   | 0.155      | -            | -                | -                | 1 (0.155) |     1.79 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     3945 | 2024-03-01 | paiN             | L   | 0.148      | -            | -                | -                | -         |    -0.46 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($38,952.08)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-06-16 |      0.863 | $10,000.00     | $8,629.17       |
| 2024-06-10 |      0.823 | $7,000.00      | $5,760.42       |
| 2024-06-09 |      0.816 | $20,000.00     | $16,322.22      |
| 2024-03-20 |      0.274 | $10,000.00     | $2,740.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
