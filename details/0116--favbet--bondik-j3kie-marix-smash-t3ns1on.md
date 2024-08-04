### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  828.0<br />
<br />
Final Rank Value (828.0) = Starting Rank Value (755.3) + Head To Head Adjustments (72.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 755.3
- 400 + ( ( 0.174 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 755.3


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
|           27 |      122 | 2024-08-01 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -19.01 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           26 |      439 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -9.95 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      740 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.558 (0.080)    | 0 (0.000) |    25.44 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |      995 | 2024-06-16 | Zero Tenacity     | L   | 0.873      | -            | -                | -                | -         |    -5.60 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |     1025 | 2024-06-15 | 9INE              | W   | 0.867      | -            | -                | -                | 0 (0.000) |     4.69 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1063 | 2024-06-14 | ARCRED            | L   | 0.860      | -            | -                | -                | -         |   -10.17 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1132 | 2024-06-12 | Nemiga            | W   | 0.847      | 0.143        | 0.317 (0.038)    | 0.734 (0.089)    | 0 (0.000) |    23.19 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1154 | 2024-06-11 | Nexus             | W   | 0.840      | 0.143        | 0.014 (0.002)    | 0.465 (0.056)    | 0 (0.000) |    10.71 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1392 | 2024-06-06 | Zero Tenacity     | L   | 0.807      | -            | -                | -                | -         |    -3.82 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1421 | 2024-06-06 | 1WIN              | W   | 0.806      | 0.372        | 0.027 (0.008)    | 0.707 (0.212)    | 0 (0.000) |    19.03 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1523 | 2024-06-04 | RUSTEC            | W   | 0.792      | -            | -                | -                | 0 (0.000) |     2.67 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1572 | 2024-06-02 | JANO              | W   | 0.779      | 0.372        | 0.001 (0.000)    | 0.044 (0.013)    | 0 (0.000) |     8.63 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1632 | 2024-05-31 | Sangal            | L   | 0.766      | -            | -                | -                | -         |    -3.08 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1640 | 2024-05-31 | SAW               | L   | 0.765      | -            | -                | -                | -         |    -2.08 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1653 | 2024-05-30 | ARCRED            | L   | 0.760      | -            | -                | -                | -         |    -9.24 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1683 | 2024-05-29 | Aurora Young Blud | W   | 0.753      | 0.372        | 0.003 (0.001)    | 0.460 (0.129)    | 0 (0.000) |    13.09 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2252 | 2024-05-10 | Johnny Speeds     | L   | 0.624      | -            | -                | -                | -         |    -1.12 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3204 | 2024-04-03 | Metizport         | L   | 0.379      | -            | -                | -                | -         |    -4.71 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3234 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.374      | -            | -                | -                | -         |    -0.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3241 | 2024-04-02 | GamerLegion       | W   | 0.373      | 0.143        | 0.173 (0.009)    | 0.271 (0.014)    | 0 (0.000) |    10.31 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3267 | 2024-03-31 | Passion UA        | W   | 0.359      | 0.276        | 0.172 (0.017)    | 1.000 (0.099)    | 0 (0.000) |     9.31 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3272 | 2024-03-30 | L&G               | W   | 0.353      | -            | -                | -                | -         |     2.14 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3329 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.334      | 0.143        | 0.031 (0.002)    | 0.560 (0.027)    | -         |     8.12 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3338 | 2024-03-27 | BetBoom           | W   | 0.334      | 0.143        | 0.251 (0.012)    | 0.541 (0.026)    | -         |    10.25 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3675 | 2024-03-10 | AURA              | L   | 0.220      | -            | -                | -                | -         |    -5.65 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3719 | 2024-03-08 | Nexus             | L   | 0.207      | -            | -                | -                | -         |    -2.60 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3776 | 2024-03-06 | CYBERSHOKE        | W   | 0.193      | -            | -                | -                | -         |     2.27 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,097.77)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.834 | $750.00        | $625.43         |
| 2024-03-31 |      0.359 | $1,315.00      | $472.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
