### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  830.3<br />
<br />
Final Rank Value (830.3) = Starting Rank Value (756.1) + Head To Head Adjustments (74.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 756.1
- 400 + ( ( 0.173 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 756.1


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
|           27 |      154 | 2024-08-01 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -19.05 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           26 |      471 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |   -10.06 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      772 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.061 (0.009)    | 0.549 (0.078)    | 0 (0.000) |    25.42 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |     1027 | 2024-06-16 | Zero Tenacity     | L   | 0.862      | -            | -                | -                | -         |    -5.55 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |     1057 | 2024-06-15 | 9INE              | W   | 0.855      | -            | -                | -                | 0 (0.000) |     4.58 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1095 | 2024-06-14 | ARCRED            | L   | 0.849      | -            | -                | -                | -         |    -8.92 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1164 | 2024-06-12 | Nemiga            | W   | 0.835      | 0.143        | 0.315 (0.038)    | 0.720 (0.086)    | 0 (0.000) |    22.84 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1186 | 2024-06-11 | Nexus             | W   | 0.829      | 0.143        | 0.014 (0.002)    | 0.457 (0.054)    | 0 (0.000) |    10.60 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1424 | 2024-06-06 | Zero Tenacity     | L   | 0.796      | -            | -                | -                | -         |    -3.79 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1453 | 2024-06-06 | 1WIN              | W   | 0.794      | 0.372        | 0.033 (0.010)    | 0.695 (0.206)    | 0 (0.000) |    18.88 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1555 | 2024-06-04 | RUSTEC            | W   | 0.781      | -            | -                | -                | 0 (0.000) |     2.61 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1604 | 2024-06-02 | JANO              | W   | 0.767      | 0.372        | 0.001 (0.000)    | 0.043 (0.012)    | 0 (0.000) |     8.48 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1664 | 2024-05-31 | Sangal            | L   | 0.755      | -            | -                | -                | -         |    -3.00 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1672 | 2024-05-31 | SAW               | L   | 0.754      | -            | -                | -                | -         |    -2.13 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1685 | 2024-05-30 | ARCRED            | L   | 0.749      | -            | -                | -                | -         |    -7.84 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1715 | 2024-05-29 | Aurora Young Blud | W   | 0.742      | 0.372        | 0.003 (0.001)    | 0.533 (0.147)    | 0 (0.000) |    13.82 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2284 | 2024-05-10 | Johnny Speeds     | L   | 0.613      | -            | -                | -                | -         |    -1.09 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3236 | 2024-04-03 | Metizport         | L   | 0.368      | -            | -                | -                | -         |    -4.61 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3266 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.362      | -            | -                | -                | -         |    -0.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3273 | 2024-04-02 | GamerLegion       | W   | 0.361      | 0.143        | 0.173 (0.009)    | 0.265 (0.014)    | 0 (0.000) |     9.98 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3299 | 2024-03-31 | Passion UA        | W   | 0.348      | 0.276        | 0.173 (0.017)    | 1.000 (0.096)    | 0 (0.000) |     9.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3304 | 2024-03-30 | L&G               | W   | 0.341      | -            | -                | -                | -         |     2.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3361 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.323      | 0.143        | 0.031 (0.001)    | 0.549 (0.025)    | -         |     7.83 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3370 | 2024-03-27 | BetBoom           | W   | 0.322      | 0.143        | 0.248 (0.011)    | 0.526 (0.024)    | -         |     9.89 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3707 | 2024-03-10 | AURA              | L   | 0.209      | -            | -                | -                | -         |    -5.39 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3751 | 2024-03-08 | Nexus             | L   | 0.195      | -            | -                | -                | -         |    -2.44 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3808 | 2024-03-06 | CYBERSHOKE        | W   | 0.182      | -            | -                | -                | -         |     2.13 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,073.92)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.822 | $750.00        | $616.77         |
| 2024-03-31 |      0.348 | $1,315.00      | $457.15         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
