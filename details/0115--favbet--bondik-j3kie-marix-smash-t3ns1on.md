### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  828.0<br />
<br />
Final Rank Value (828.0) = Starting Rank Value (755.9) + Head To Head Adjustments (72.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 755.9
- 400 + ( ( 0.174 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 755.9


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
|           27 |      139 | 2024-08-01 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -19.00 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           26 |      456 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -9.95 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      757 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.557 (0.080)    | 0 (0.000) |    25.45 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |     1012 | 2024-06-16 | Zero Tenacity     | L   | 0.868      | -            | -                | -                | -         |    -5.55 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |     1042 | 2024-06-15 | 9INE              | W   | 0.861      | -            | -                | -                | 0 (0.000) |     4.66 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1080 | 2024-06-14 | ARCRED            | L   | 0.854      | -            | -                | -                | -         |   -10.12 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1149 | 2024-06-12 | Nemiga            | W   | 0.841      | 0.143        | 0.316 (0.038)    | 0.731 (0.088)    | 0 (0.000) |    23.03 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1171 | 2024-06-11 | Nexus             | W   | 0.834      | 0.143        | 0.014 (0.002)    | 0.464 (0.055)    | 0 (0.000) |    10.66 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1409 | 2024-06-06 | Zero Tenacity     | L   | 0.802      | -            | -                | -                | -         |    -3.79 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1438 | 2024-06-06 | 1WIN              | W   | 0.800      | 0.372        | 0.033 (0.010)    | 0.705 (0.210)    | 0 (0.000) |    19.00 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1540 | 2024-06-04 | RUSTEC            | W   | 0.787      | -            | -                | -                | 0 (0.000) |     2.65 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1589 | 2024-06-02 | JANO              | W   | 0.773      | 0.372        | 0.001 (0.000)    | 0.044 (0.013)    | 0 (0.000) |     8.56 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1649 | 2024-05-31 | Sangal            | L   | 0.761      | -            | -                | -                | -         |    -3.02 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1657 | 2024-05-31 | SAW               | L   | 0.760      | -            | -                | -                | -         |    -2.09 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1670 | 2024-05-30 | ARCRED            | L   | 0.755      | -            | -                | -                | -         |    -9.18 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1700 | 2024-05-29 | Aurora Young Blud | W   | 0.748      | 0.372        | 0.003 (0.001)    | 0.499 (0.139)    | 0 (0.000) |    13.04 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2269 | 2024-05-10 | Johnny Speeds     | L   | 0.619      | -            | -                | -                | -         |    -1.10 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3221 | 2024-04-03 | Metizport         | L   | 0.373      | -            | -                | -                | -         |    -4.67 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3251 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.368      | -            | -                | -                | -         |    -0.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3258 | 2024-04-02 | GamerLegion       | W   | 0.367      | 0.143        | 0.173 (0.009)    | 0.269 (0.014)    | 0 (0.000) |    10.15 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3284 | 2024-03-31 | Passion UA        | W   | 0.353      | 0.276        | 0.173 (0.017)    | 1.000 (0.097)    | 0 (0.000) |     9.17 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3289 | 2024-03-30 | L&G               | W   | 0.347      | -            | -                | -                | -         |     2.10 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3346 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.328      | 0.143        | 0.031 (0.001)    | 0.557 (0.026)    | -         |     7.97 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3355 | 2024-03-27 | BetBoom           | W   | 0.328      | 0.143        | 0.249 (0.012)    | 0.536 (0.025)    | -         |    10.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3692 | 2024-03-10 | AURA              | L   | 0.214      | -            | -                | -                | -         |    -5.52 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3736 | 2024-03-08 | Nexus             | L   | 0.201      | -            | -                | -                | -         |    -2.53 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3793 | 2024-03-06 | CYBERSHOKE        | W   | 0.188      | -            | -                | -                | -         |     2.20 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,085.96)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.828 | $750.00        | $621.15         |
| 2024-03-31 |      0.353 | $1,315.00      | $464.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
