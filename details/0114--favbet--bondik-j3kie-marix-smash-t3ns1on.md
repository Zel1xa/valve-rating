### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  830.9<br />
<br />
Final Rank Value (830.9) = Starting Rank Value (756.4) + Head To Head Adjustments (74.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 756.4
- 400 + ( ( 0.174 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 756.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |      148 | 2024-08-01 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -19.09 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           26 |      465 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |   -10.07 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      766 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.550 (0.079)    | 0 (0.000) |    25.40 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |     1021 | 2024-06-16 | Zero Tenacity     | L   | 0.866      | -            | -                | -                | -         |    -5.60 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |     1051 | 2024-06-15 | 9INE              | W   | 0.860      | -            | -                | -                | 0 (0.000) |     4.59 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1089 | 2024-06-14 | ARCRED            | L   | 0.853      | -            | -                | -                | -         |    -8.99 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1158 | 2024-06-12 | Nemiga            | W   | 0.840      | 0.143        | 0.316 (0.038)    | 0.722 (0.087)    | 0 (0.000) |    22.96 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1180 | 2024-06-11 | Nexus             | W   | 0.833      | 0.143        | 0.014 (0.002)    | 0.458 (0.054)    | 0 (0.000) |    10.60 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1418 | 2024-06-06 | Zero Tenacity     | L   | 0.800      | -            | -                | -                | -         |    -3.82 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1447 | 2024-06-06 | 1WIN              | W   | 0.798      | 0.372        | 0.033 (0.010)    | 0.696 (0.207)    | 0 (0.000) |    18.96 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1549 | 2024-06-04 | RUSTEC            | W   | 0.785      | -            | -                | -                | 0 (0.000) |     2.62 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1598 | 2024-06-02 | JANO              | W   | 0.772      | 0.372        | 0.001 (0.000)    | 0.043 (0.012)    | 0 (0.000) |     8.51 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1658 | 2024-05-31 | Sangal            | L   | 0.759      | -            | -                | -                | -         |    -3.03 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1666 | 2024-05-31 | SAW               | L   | 0.758      | -            | -                | -                | -         |    -2.12 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1679 | 2024-05-30 | ARCRED            | L   | 0.753      | -            | -                | -                | -         |    -7.91 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1709 | 2024-05-29 | Aurora Young Blud | W   | 0.746      | 0.372        | 0.003 (0.001)    | 0.532 (0.148)    | 0 (0.000) |    13.87 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2278 | 2024-05-10 | Johnny Speeds     | L   | 0.617      | -            | -                | -                | -         |    -1.10 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3230 | 2024-04-03 | Metizport         | L   | 0.372      | -            | -                | -                | -         |    -4.65 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3260 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.366      | -            | -                | -                | -         |    -0.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3267 | 2024-04-02 | GamerLegion       | W   | 0.365      | 0.143        | 0.173 (0.009)    | 0.266 (0.014)    | 0 (0.000) |    10.11 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3293 | 2024-03-31 | Passion UA        | W   | 0.352      | 0.276        | 0.173 (0.017)    | 1.000 (0.097)    | 0 (0.000) |     9.16 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3298 | 2024-03-30 | L&G               | W   | 0.345      | -            | -                | -                | -         |     2.09 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3355 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.327      | 0.143        | 0.031 (0.001)    | 0.550 (0.026)    | -         |     7.93 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3364 | 2024-03-27 | BetBoom           | W   | 0.327      | 0.143        | 0.249 (0.012)    | 0.529 (0.025)    | -         |    10.03 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3701 | 2024-03-10 | AURA              | L   | 0.213      | -            | -                | -                | -         |    -5.49 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3745 | 2024-03-08 | Nexus             | L   | 0.200      | -            | -                | -                | -         |    -2.51 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3802 | 2024-03-06 | CYBERSHOKE        | W   | 0.186      | -            | -                | -                | -         |     2.18 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,082.81)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.827 | $750.00        | $620.00         |
| 2024-03-31 |      0.352 | $1,315.00      | $462.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
