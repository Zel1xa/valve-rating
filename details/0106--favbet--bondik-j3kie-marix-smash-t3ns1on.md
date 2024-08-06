### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  847.2<br />
<br />
Final Rank Value (847.2) = Starting Rank Value (756.9) + Head To Head Adjustments (90.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 756.9
- 400 + ( ( 0.174 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 756.9


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
|           28 |        5 | 2024-08-06 | Lilmix            | W   | 1.000      | 0.143        | 0.023 (0.003)    | 0.095 (0.014)    | 0 (0.000) |    15.54 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           27 |      158 | 2024-08-01 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -19.06 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           26 |      475 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |   -10.11 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      776 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.061 (0.009)    | 0.537 (0.077)    | 0 (0.000) |    25.40 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |     1031 | 2024-06-16 | Zero Tenacity     | L   | 0.862      | -            | -                | -                | -         |    -5.53 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |     1061 | 2024-06-15 | 9INE              | W   | 0.855      | -            | -                | -                | 0 (0.000) |     4.56 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1099 | 2024-06-14 | ARCRED            | L   | 0.848      | -            | -                | -                | -         |    -8.97 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1168 | 2024-06-12 | Nemiga            | W   | 0.835      | 0.143        | 0.315 (0.038)    | 0.704 (0.084)    | 0 (0.000) |    22.81 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1190 | 2024-06-11 | Nexus             | W   | 0.828      | 0.143        | 0.014 (0.002)    | 0.447 (0.053)    | 0 (0.000) |    10.61 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1428 | 2024-06-06 | Zero Tenacity     | L   | 0.795      | -            | -                | -                | -         |    -3.76 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1457 | 2024-06-06 | 1WIN              | W   | 0.794      | 0.372        | 0.033 (0.010)    | 0.680 (0.201)    | 0 (0.000) |    18.82 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1559 | 2024-06-04 | RUSTEC            | W   | 0.781      | -            | -                | -                | 0 (0.000) |     2.59 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1608 | 2024-06-02 | JANO              | W   | 0.767      | -            | -                | -                | 0 (0.000) |     8.45 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1668 | 2024-05-31 | Sangal            | L   | 0.755      | -            | -                | -                | -         |    -3.01 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1676 | 2024-05-31 | SAW               | L   | 0.754      | -            | -                | -                | -         |    -2.15 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1689 | 2024-05-30 | ARCRED            | L   | 0.749      | -            | -                | -                | -         |    -7.89 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1719 | 2024-05-29 | Aurora Young Blud | W   | 0.741      | 0.372        | 0.003 (0.001)    | 0.521 (0.144)    | 0 (0.000) |    13.76 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2288 | 2024-05-10 | Johnny Speeds     | L   | 0.613      | -            | -                | -                | -         |    -1.09 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3240 | 2024-04-03 | Metizport         | L   | 0.367      | -            | -                | -                | -         |    -3.71 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3270 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.362      | -            | -                | -                | -         |    -0.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3277 | 2024-04-02 | GamerLegion       | W   | 0.361      | 0.143        | 0.173 (0.009)    | 0.259 (0.013)    | 0 (0.000) |     9.96 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3303 | 2024-03-31 | Passion UA        | W   | 0.347      | 0.276        | 0.173 (0.017)    | 1.000 (0.096)    | -         |     9.05 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3308 | 2024-03-30 | L&G               | W   | 0.341      | -            | -                | -                | -         |     2.06 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3365 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.322      | 0.143        | 0.031 (0.001)    | 0.537 (0.025)    | -         |     7.83 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3374 | 2024-03-27 | BetBoom           | W   | 0.322      | 0.143        | 0.248 (0.011)    | 0.514 (0.024)    | -         |     9.88 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3711 | 2024-03-10 | AURA              | L   | 0.208      | -            | -                | -                | -         |    -5.38 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3755 | 2024-03-08 | Nexus             | L   | 0.195      | -            | -                | -                | -         |    -2.44 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3812 | 2024-03-06 | CYBERSHOKE        | W   | 0.182      | -            | -                | -                | -         |     2.12 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,073.34)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.822 | $750.00        | $616.56         |
| 2024-03-31 |      0.347 | $1,315.00      | $456.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
