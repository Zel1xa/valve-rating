### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1885.7<br />
<br />
Final Rank Value (1885.7) = Starting Rank Value (1869.2) + Head To Head Adjustments (16.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.661[<sup>2</sup>](#table1)
- Opponent Network: 0.333[<sup>2</sup>](#table1)
- LAN Wins: 0.863[<sup>2</sup>](#table1)

The average of these factors is 0.714<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1869.2
- 400 + ( ( 0.714 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1869.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      400 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.52 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           31 |      444 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.286 (0.286)    | 0.494 (0.494)    | 1 (1.000) |     5.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           30 |      586 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.187 (0.187)    | 0.970 (0.970)    | 1 (1.000) |     0.56 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |     1599 | 2024-05-28 | G2                 | L   | 0.769      | -            | -                | -                | -         |   -11.27 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |     1620 | 2024-05-27 | Complexity         | W   | 0.762      | 0.624        | -                | 0.366 (0.174)    | 1 (0.762) |     4.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1629 | 2024-05-27 | 9z                 | L   | 0.761      | -            | -                | -                | -         |   -23.59 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1875 | 2024-05-19 | Spirit             | W   | 0.706      | 0.769        | 1.000 (0.542)    | 0.424 (0.230)    | 1 (0.706) |    10.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1903 | 2024-05-18 | HEROIC             | W   | 0.699      | 0.769        | -                | 0.380 (0.204)    | 1 (0.699) |     2.68 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1983 | 2024-05-16 | Virtus.pro         | W   | 0.685      | 0.769        | 0.484 (0.255)    | -                | 1 (0.685) |     4.89 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     2094 | 2024-05-14 | BetBoom            | W   | 0.672      | 0.769        | -                | 0.551 (0.285)    | 1 (0.672) |     1.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2141 | 2024-05-12 | Vitality           | W   | 0.659      | 0.889        | 0.590 (0.346)    | 0.384 (0.225)    | 1 (0.659) |     9.25 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2162 | 2024-05-11 | Complexity         | W   | 0.654      | 0.889        | 0.318 (0.185)    | 0.366 (0.213)    | 1 (0.654) |     4.50 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2210 | 2024-05-09 | G2                 | W   | 0.640      | 0.889        | 1.000 (0.569)    | 0.500 (0.284)    | 1 (0.640) |    11.74 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2305 | 2024-05-04 | Liquid             | W   | 0.607      | 0.889        | 0.321 (0.173)    | 0.467 (0.252)    | -         |     2.40 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2375 | 2024-05-01 | GamerLegion        | W   | 0.586      | -            | -                | -                | -         |     0.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2407 | 2024-04-30 | Bad News Kangaroos | W   | 0.578      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2837 | 2024-04-14 | FaZe               | L   | 0.472      | -            | -                | -                | -         |   -10.35 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2854 | 2024-04-13 | G2                 | W   | 0.464      | 0.624        | 1.000 (0.290)    | -                | -         |     9.22 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2951 | 2024-04-10 | Liquid             | W   | 0.444      | -            | -                | -                | -         |     1.78 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     3025 | 2024-04-08 | FURIA              | W   | 0.432      | -            | -                | -                | -         |     3.84 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     3036 | 2024-04-07 | TYLOO              | W   | 0.430      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3245 | 2024-03-29 | G2                 | L   | 0.367      | -            | -                | -                | -         |    -4.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3373 | 2024-03-22 | Complexity         | W   | 0.319      | -            | -                | -                | -         |     2.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3393 | 2024-03-21 | Eternal Fire       | W   | 0.313      | 1.000        | 0.757 (0.237)    | -                | -         |     2.99 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3403 | 2024-03-21 | Gaimin Gladiators  | W   | 0.312      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     4105 | 2024-02-20 | Spirit             | W   | 0.113      | -            | -                | -                | -         |     2.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     4127 | 2024-02-19 | Gaimin Gladiators  | W   | 0.107      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4140 | 2024-02-19 | ex-Guild Eagles    | W   | 0.105      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4344 | 2024-02-10 | FaZe               | L   | 0.046      | -            | -                | -                | -         |    -1.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4388 | 2024-02-06 | ENCE               | W   | 0.020      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4400 | 2024-02-05 | GamerLegion        | W   | 0.013      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4424 | 2024-02-04 | Cloud9             | W   | 0.005      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($453,935.69)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.800 | $5,000.00      | $4,001.39       |
| 2024-05-19 |      0.706 | $300,000.00    | $211,666.67     |
| 2024-05-12 |      0.659 | $170,000.00    | $112,105.56     |
| 2024-04-14 |      0.472 | $42,000.00     | $19,805.14      |
| 2024-03-31 |      0.380 | $45,000.00     | $17,112.50      |
| 2024-02-11 |      0.053 | $80,000.00     | $4,244.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
