### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1052.4<br />
<br />
Final Rank Value (1052.4) = Starting Rank Value (903.5) + Head To Head Adjustments (148.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.491[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.008[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 903.5
- 400 + ( ( 0.260 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 903.5


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
|           54 |      102 | 2024-09-04 | timbermen        | W   | 1.000      | 0.477        | 0.023 (0.011)    | 0.576 (0.275)    | 0 (0.000) |     9.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           53 |      104 | 2024-09-04 | timbermen        | L   | 1.000      | -            | -                | -                | -         |   -22.91 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           52 |      168 | 2024-09-02 | BOSS             | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.401 (0.191)    | 0 (0.000) |     5.54 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           51 |      169 | 2024-09-02 | BOSS             | W   | 1.000      | 0.477        | -                | 0.401 (0.191)    | 0 (0.000) |     5.83 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           50 |      190 | 2024-09-01 | Liquid           | L   | 1.000      | -            | -                | -                | -         |    -1.24 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           49 |      208 | 2024-08-31 | Liquid           | W   | 1.000      | 0.143        | 0.370 (0.053)    | -                | 0 (0.000) |    30.45 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           48 |      210 | 2024-08-31 | LAG              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.70 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           47 |      300 | 2024-08-28 | FLUFFY AIMERS    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.85 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           46 |      305 | 2024-08-28 | NRG              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.02 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           45 |      364 | 2024-08-27 | Take Flyte       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.80 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           44 |      420 | 2024-08-26 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -25.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           43 |      441 | 2024-08-26 | LAG              | W   | 1.000      | -            | -                | -                | -         |     4.16 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           42 |      571 | 2024-08-22 | Mythic           | W   | 1.000      | 0.477        | -                | 0.276 (0.132)    | -         |     5.27 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           41 |      572 | 2024-08-22 | Mythic           | W   | 1.000      | 0.477        | -                | 0.276 (0.132)    | -         |     5.54 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           40 |      603 | 2024-08-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.50 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           39 |      605 | 2024-08-21 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -12.50 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           38 |     1189 | 2024-08-03 | paiN             | L   | 0.963      | -            | -                | -                | -         |    -1.71 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           37 |     1205 | 2024-08-03 | Solid            | W   | 0.960      | -            | -                | -                | -         |    10.61 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           36 |     1222 | 2024-08-02 | Fluxo            | W   | 0.956      | 0.143        | 0.122 (0.017)    | -                | -         |    18.39 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           35 |     1227 | 2024-08-02 | paiN             | L   | 0.955      | -            | -                | -                | -         |    -1.55 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           34 |     1260 | 2024-08-01 | Intense          | W   | 0.950      | -            | -                | -                | -         |     6.11 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |     1307 | 2024-07-31 | Case             | W   | 0.943      | 0.371        | 0.039 (0.014)    | 0.727 (0.254)    | -         |    10.13 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |     1396 | 2024-07-29 | Solid            | W   | 0.929      | -            | -                | -                | -         |    11.59 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |     1440 | 2024-07-28 | Players          | W   | 0.920      | -            | -                | -                | -         |     4.94 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |     1973 | 2024-07-14 | ODDIK            | L   | 0.827      | -            | -                | -                | -         |    -9.59 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |     1979 | 2024-07-13 | RED Canids       | W   | 0.822      | 0.371        | 0.049 (0.015)    | 0.612 (0.186)    | -         |    15.92 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |     1992 | 2024-07-12 | Bounty Hunters   | W   | 0.815      | 0.371        | 0.026 (0.008)    | 0.440 (0.133)    | -         |    11.03 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           27 |     2005 | 2024-07-11 | ODDIK            | L   | 0.809      | -            | -                | -                | -         |    -9.52 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           26 |     2028 | 2024-07-10 | Case             | W   | 0.801      | 0.371        | 0.039 (0.012)    | 0.727 (0.216)    | -         |     9.68 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           25 |     2055 | 2024-07-09 | Vikings KR       | W   | 0.794      | -            | -                | -                | -         |     6.83 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           24 |     2152 | 2024-06-16 | Nouns            | W   | 0.643      | 0.371        | 0.056 (0.013)    | -                | -         |     9.98 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           23 |     2156 | 2024-06-16 | timbermen        | W   | 0.643      | 0.371        | -                | 0.576 (0.137)    | -         |    10.06 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           22 |     2185 | 2024-06-15 | Akimbo           | W   | 0.635      | -            | -                | -                | -         |     5.06 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           21 |     2219 | 2024-06-14 | Akimbo           | W   | 0.630      | -            | -                | -                | -         |     2.84 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           20 |     2333 | 2024-06-10 | Akimbo           | W   | 0.603      | -            | -                | -                | -         |     4.71 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           19 |     2367 | 2024-06-09 | Party Astronauts | W   | 0.597      | 0.384        | 0.033 (0.008)    | -                | -         |     9.57 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           18 |     2438 | 2024-06-08 | M80              | L   | 0.589      | -            | -                | -                | -         |    -4.08 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           17 |     2493 | 2024-06-07 | Party Astronauts | L   | 0.582      | -            | -                | -                | -         |    -9.08 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           16 |     2500 | 2024-06-07 | timbermen        | W   | 0.582      | -            | -                | -                | -         |     9.60 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           15 |     2545 | 2024-06-06 | Mythic           | W   | 0.577      | -            | -                | -                | -         |     6.10 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           14 |     2548 | 2024-06-06 | Akimbo           | W   | 0.576      | -            | -                | -                | -         |     4.52 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           13 |     2614 | 2024-06-05 | Vibe             | W   | 0.570      | -            | -                | -                | -         |     1.04 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           12 |     2663 | 2024-06-04 | E-Xolos LAZER    | W   | 0.564      | -            | -                | -                | -         |     5.84 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           11 |     3001 | 2024-05-22 | NRG              | L   | 0.474      | -            | -                | -                | -         |    -8.23 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           10 |     3029 | 2024-05-21 | Carpe Diem       | W   | 0.469      | -            | -                | -                | -         |     4.03 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|            9 |     3158 | 2024-05-17 | Party Astronauts | L   | 0.443      | -            | -                | -                | -         |    -7.57 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|            8 |     3862 | 2024-04-19 | M80              | L   | 0.256      | -            | -                | -                | -         |    -2.15 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            7 |     3904 | 2024-04-18 | timbermen        | W   | 0.250      | -            | -                | -                | -         |     4.22 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            6 |     3908 | 2024-04-18 | Liquid           | L   | 0.249      | -            | -                | -                | -         |    -0.18 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|            5 |     4617 | 2024-03-20 | The MongolZ      | L   | 0.053      | -            | -                | -                | -         |    -0.01 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     4632 | 2024-03-19 | Apeks            | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.46 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     4643 | 2024-03-18 | GamerLegion      | L   | 0.040      | -            | -                | -                | -         |    -1.03 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     4656 | 2024-03-17 | Cloud9           | L   | 0.035      | -            | -                | -                | -         |    -0.73 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     4666 | 2024-03-17 | FURIA            | W   | 0.034      | -            | -                | -                | 1 (0.034) |     1.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,881.25)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      0.956 | $1,500.00      | $1,433.89       |
| 2024-07-14 |      0.827 | $4,000.00      | $3,309.17       |
| 2024-06-16 |      0.643 | $10,000.00     | $6,434.72       |
| 2024-06-10 |      0.603 | $7,000.00      | $4,224.31       |
| 2024-06-09 |      0.597 | $20,000.00     | $11,933.33      |
| 2024-03-20 |      0.055 | $10,000.00     | $545.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
