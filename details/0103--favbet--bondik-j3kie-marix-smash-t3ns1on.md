### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  845.2<br />
<br />
Final Rank Value (845.2) = Starting Rank Value (753.4) + Head To Head Adjustments (91.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.071[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.4
- 400 + ( ( 0.173 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 753.4


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
|           26 |      407 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -9.90 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      706 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.559 (0.080)    | 0 (0.000) |    25.41 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |      963 | 2024-06-16 | Zero Tenacity     | L   | 0.875      | -            | -                | -                | -         |    -5.60 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |      993 | 2024-06-15 | 9INE              | W   | 0.869      | -            | -                | -                | 0 (0.000) |     4.74 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1031 | 2024-06-14 | ARCRED            | L   | 0.862      | -            | -                | -                | -         |   -10.13 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1100 | 2024-06-12 | Nemiga            | W   | 0.849      | 0.143        | 0.317 (0.038)    | 0.695 (0.084)    | 0 (0.000) |    23.03 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1122 | 2024-06-11 | Nexus             | W   | 0.842      | 0.143        | 0.014 (0.002)    | 0.465 (0.056)    | 0 (0.000) |    10.79 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1360 | 2024-06-06 | Zero Tenacity     | L   | 0.809      | -            | -                | -                | -         |    -3.80 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1389 | 2024-06-06 | 1WIN              | W   | 0.807      | 0.372        | 0.027 (0.008)    | 0.628 (0.189)    | 0 (0.000) |    18.54 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1491 | 2024-06-04 | RUSTEC            | W   | 0.794      | -            | -                | -                | 0 (0.000) |     2.70 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1540 | 2024-06-02 | JANO              | W   | 0.781      | 0.372        | 0.001 (0.000)    | 0.045 (0.013)    | 0 (0.000) |     8.69 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1600 | 2024-05-31 | Sangal            | L   | 0.768      | -            | -                | -                | -         |    -3.12 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1608 | 2024-05-31 | SAW               | L   | 0.767      | -            | -                | -                | -         |    -2.08 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1621 | 2024-05-30 | ARCRED            | L   | 0.762      | -            | -                | -                | -         |    -9.22 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1651 | 2024-05-29 | Aurora Young Blud | W   | 0.755      | 0.372        | 0.003 (0.001)    | 0.420 (0.118)    | 0 (0.000) |    12.39 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2220 | 2024-05-10 | Johnny Speeds     | L   | 0.626      | -            | -                | -                | -         |    -1.17 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3172 | 2024-04-03 | Metizport         | L   | 0.381      | -            | -                | -                | -         |    -3.81 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3202 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.375      | -            | -                | -                | -         |    -0.08 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3209 | 2024-04-02 | GamerLegion       | W   | 0.374      | 0.143        | 0.174 (0.009)    | 0.271 (0.014)    | 0 (0.000) |    10.38 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3235 | 2024-03-31 | Passion UA        | W   | 0.361      | 0.276        | 0.172 (0.017)    | 1.000 (0.100)    | 0 (0.000) |     9.34 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3240 | 2024-03-30 | L&G               | W   | 0.354      | -            | -                | -                | -         |     2.17 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3297 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.336      | 0.143        | 0.031 (0.002)    | 0.560 (0.027)    | -         |     8.19 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3306 | 2024-03-27 | BetBoom           | W   | 0.336      | 0.143        | 0.251 (0.012)    | 0.542 (0.026)    | -         |    10.31 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3643 | 2024-03-10 | AURA              | L   | 0.222      | -            | -                | -                | -         |    -5.68 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3687 | 2024-03-08 | Nexus             | L   | 0.209      | -            | -                | -                | -         |    -2.61 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3744 | 2024-03-06 | CYBERSHOKE        | W   | 0.195      | -            | -                | -                | -         |     2.31 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,101.45)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.836 | $750.00        | $626.77         |
| 2024-03-31 |      0.361 | $1,315.00      | $474.68         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
