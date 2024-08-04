### Roster Details<br />
Team Name: inSanitY<br />
Roster: cass1n, f4stzin, iDk, pesadelo, shz<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
<br />
Final Rank Value:  969.9<br />
<br />
Final Rank Value (969.9) = Starting Rank Value (919.2) + Head To Head Adjustments (50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.235[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.2
- 400 + ( ( 0.254 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 919.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       29 | 2024-08-02 | Case              | L   | 1.000      | -            | -                | -                | -         |   -19.30 | cass1n, f4stzin, iDk, pesadelo, shz |
|           35 |       62 | 2024-08-01 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.38 | cass1n, f4stzin, iDk, pesadelo, shz |
|           34 |      157 | 2024-07-30 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -13.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|           33 |      310 | 2024-07-25 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -21.21 | cass1n, f4stzin, iDk, pesadelo, shz |
|           32 |      386 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -20.81 | cass1n, f4stzin, iDk, pesadelo, shz |
|           31 |      472 | 2024-07-20 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.48 | cass1n, f4stzin, iDk, pesadelo, shz |
|           30 |      577 | 2024-07-18 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -22.05 | cass1n, f4stzin, iDk, pesadelo, shz |
|           29 |      641 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.70 | cass1n, f4stzin, iDk, pesadelo, shz |
|           28 |      677 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.01 | cass1n, f4stzin, iDk, pesadelo, shz |
|           27 |      682 | 2024-07-16 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.35 | cass1n, f4stzin, iDk, pesadelo, shz |
|           26 |      726 | 2024-07-15 | Galorys           | W   | 1.000      | 0.450        | 0.030 (0.013)    | 0.552 (0.248)    | 0 (0.000) |     7.98 | cass1n, f4stzin, iDk, pesadelo, shz |
|           25 |      732 | 2024-07-15 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -24.07 | cass1n, f4stzin, iDk, pesadelo, shz |
|           24 |      749 | 2024-07-15 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.29 | cass1n, f4stzin, iDk, pesadelo, shz |
|           23 |      892 | 2024-07-03 | Bounty Hunters    | W   | 0.992      | 0.333        | -                | 0.556 (0.184)    | 0 (0.000) |    11.58 | cass1n, f4stzin, iDk, pesadelo, shz |
|           22 |      895 | 2024-07-01 | Bounty Hunters    | W   | 0.979      | 0.333        | -                | 0.556 (0.181)    | 0 (0.000) |    11.94 | cass1n, f4stzin, iDk, pesadelo, shz |
|           21 |      905 | 2024-06-29 | Galorys           | W   | 0.966      | 0.333        | 0.030 (0.010)    | -                | 0 (0.000) |     8.62 | cass1n, f4stzin, iDk, pesadelo, shz |
|           20 |      919 | 2024-06-27 | Sharks            | W   | 0.952      | 0.333        | 0.031 (0.010)    | -                | -         |    15.90 | cass1n, f4stzin, iDk, pesadelo, shz |
|           19 |      940 | 2024-06-19 | Case              | W   | 0.899      | 0.337        | 0.029 (0.009)    | 0.804 (0.243)    | -         |     9.04 | cass1n, f4stzin, iDk, pesadelo, shz |
|           18 |      941 | 2024-06-18 | Galorys           | W   | 0.893      | 0.337        | 0.030 (0.009)    | -                | -         |     9.19 | cass1n, f4stzin, iDk, pesadelo, shz |
|           17 |      944 | 2024-06-17 | Dusty Roots       | W   | 0.887      | -            | -                | -                | -         |     8.90 | cass1n, f4stzin, iDk, pesadelo, shz |
|           16 |      984 | 2024-06-15 | Fluxo             | L   | 0.873      | -            | -                | -                | -         |    -9.03 | cass1n, f4stzin, iDk, pesadelo, shz |
|           15 |     1028 | 2024-06-14 | Patins da Ferrari | W   | 0.865      | -            | -                | -                | -         |     8.35 | cass1n, f4stzin, iDk, pesadelo, shz |
|           14 |     1170 | 2024-06-09 | Bounty Hunters    | L   | 0.833      | -            | -                | -                | -         |   -15.39 | cass1n, f4stzin, iDk, pesadelo, shz |
|           13 |     1176 | 2024-06-09 | Bounty Hunters    | W   | 0.832      | 0.450        | 0.022 (0.008)    | 0.556 (0.208)    | -         |    10.82 | cass1n, f4stzin, iDk, pesadelo, shz |
|           12 |     1252 | 2024-06-08 | Solid             | W   | 0.825      | 0.450        | 0.025 (0.009)    | 0.835 (0.310)    | -         |    10.20 | cass1n, f4stzin, iDk, pesadelo, shz |
|           11 |     1287 | 2024-06-07 | Hype              | L   | 0.820      | -            | -                | -                | -         |   -15.58 | cass1n, f4stzin, iDk, pesadelo, shz |
|           10 |     1316 | 2024-06-07 | KRÜ               | W   | 0.818      | -            | -                | -                | -         |     9.40 | cass1n, f4stzin, iDk, pesadelo, shz |
|            9 |     1354 | 2024-06-06 | BESTIA            | W   | 0.813      | 0.450        | 0.095 (0.035)    | 0.799 (0.292)    | -         |    15.76 | cass1n, f4stzin, iDk, pesadelo, shz |
|            8 |     1545 | 2024-06-01 | Solid             | W   | 0.780      | 0.371        | -                | 0.835 (0.241)    | -         |    10.40 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     1622 | 2024-05-30 | Intense           | W   | 0.764      | -            | -                | -                | -         |     5.76 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     1683 | 2024-05-27 | Bounty Hunters    | W   | 0.746      | -            | -                | -                | -         |    10.21 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     2146 | 2024-05-12 | 9z                | L   | 0.647      | -            | -                | -                | -         |    -0.77 | cass1n, f4stzin, pesadelo, shz, vsm |
|            4 |     2205 | 2024-05-10 | 9z                | L   | 0.634      | -            | -                | -                | -         |    -0.70 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     2231 | 2024-05-09 | ODDIK             | W   | 0.625      | 0.435        | 0.098 (0.027)    | 0.829 (0.225)    | -         |    11.15 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     2270 | 2024-05-07 | Case              | W   | 0.612      | 0.435        | 0.029 (0.008)    | 0.804 (0.214)    | -         |     9.33 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     2303 | 2024-05-05 | Imperial          | L   | 0.598      | -            | -                | -                | -         |    -2.11 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,786.84)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-03 |      0.992 | $6,000.00      | $5,953.33       |
| 2024-06-19 |      0.899 | $5,350.00      | $4,810.54       |
| 2024-06-16 |      0.879 | $5,000.00      | $4,393.06       |
| 2024-06-10 |      0.840 | $750.00        | $629.91         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
