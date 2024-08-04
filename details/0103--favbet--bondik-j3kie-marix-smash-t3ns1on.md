### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  845.7<br />
<br />
Final Rank Value (845.7) = Starting Rank Value (753.6) + Head To Head Adjustments (92.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.071[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.6
- 400 + ( ( 0.173 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 753.6


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
|           26 |      404 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -9.90 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      703 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.063 (0.009)    | 0.559 (0.080)    | 0 (0.000) |    25.40 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |      959 | 2024-06-16 | Zero Tenacity     | L   | 0.878      | -            | -                | -                | -         |    -5.63 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |      989 | 2024-06-15 | 9INE              | W   | 0.872      | -            | -                | -                | 0 (0.000) |     4.75 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1027 | 2024-06-14 | ARCRED            | L   | 0.865      | -            | -                | -                | -         |   -10.17 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1096 | 2024-06-12 | Nemiga            | W   | 0.852      | 0.143        | 0.318 (0.039)    | 0.695 (0.085)    | 0 (0.000) |    23.11 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1118 | 2024-06-11 | Nexus             | W   | 0.845      | 0.143        | 0.014 (0.002)    | 0.465 (0.056)    | 0 (0.000) |    10.80 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1356 | 2024-06-06 | Zero Tenacity     | L   | 0.812      | -            | -                | -                | -         |    -3.82 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1385 | 2024-06-06 | 1WIN              | W   | 0.811      | 0.372        | 0.027 (0.008)    | 0.629 (0.190)    | 0 (0.000) |    18.62 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1487 | 2024-06-04 | RUSTEC            | W   | 0.797      | -            | -                | -                | 0 (0.000) |     2.70 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1536 | 2024-06-02 | JANO              | W   | 0.784      | 0.372        | 0.001 (0.000)    | 0.045 (0.013)    | 0 (0.000) |     8.71 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1596 | 2024-05-31 | Sangal            | L   | 0.771      | -            | -                | -                | -         |    -3.14 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1604 | 2024-05-31 | SAW               | L   | 0.770      | -            | -                | -                | -         |    -2.08 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1617 | 2024-05-30 | ARCRED            | L   | 0.765      | -            | -                | -                | -         |    -9.26 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1647 | 2024-05-29 | Aurora Young Blud | W   | 0.758      | 0.372        | 0.003 (0.001)    | 0.419 (0.118)    | 0 (0.000) |    12.42 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2216 | 2024-05-10 | Johnny Speeds     | L   | 0.629      | -            | -                | -                | -         |    -1.18 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3167 | 2024-04-03 | Metizport         | L   | 0.384      | -            | -                | -                | -         |    -3.83 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3197 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.379      | -            | -                | -                | -         |    -0.08 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3204 | 2024-04-02 | GamerLegion       | W   | 0.377      | 0.143        | 0.174 (0.009)    | 0.271 (0.015)    | 0 (0.000) |    10.47 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3230 | 2024-03-31 | Passion UA        | W   | 0.364      | 0.276        | 0.172 (0.017)    | 1.000 (0.100)    | 0 (0.000) |     9.41 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3235 | 2024-03-30 | L&G               | W   | 0.357      | -            | -                | -                | -         |     2.18 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3292 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.339      | 0.143        | 0.032 (0.002)    | 0.561 (0.027)    | -         |     8.26 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3301 | 2024-03-27 | BetBoom           | W   | 0.339      | 0.143        | 0.252 (0.012)    | 0.543 (0.026)    | -         |    10.40 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3637 | 2024-03-10 | AURA              | L   | 0.225      | -            | -                | -                | -         |    -5.75 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3681 | 2024-03-08 | Nexus             | L   | 0.212      | -            | -                | -                | -         |    -2.65 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3738 | 2024-03-06 | CYBERSHOKE        | W   | 0.198      | -            | -                | -                | -         |     2.34 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,107.76)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.839 | $750.00        | $629.06         |
| 2024-03-31 |      0.364 | $1,315.00      | $478.70         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
