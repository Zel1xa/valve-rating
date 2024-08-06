### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  830.6<br />
<br />
Final Rank Value (830.6) = Starting Rank Value (756.2) + Head To Head Adjustments (74.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 756.2
- 400 + ( ( 0.174 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 756.2


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
|           27 |      150 | 2024-08-01 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -19.08 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           26 |      467 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |   -10.07 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      768 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.549 (0.078)    | 0 (0.000) |    25.41 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |     1023 | 2024-06-16 | Zero Tenacity     | L   | 0.864      | -            | -                | -                | -         |    -5.58 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |     1053 | 2024-06-15 | 9INE              | W   | 0.858      | -            | -                | -                | 0 (0.000) |     4.59 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1091 | 2024-06-14 | ARCRED            | L   | 0.851      | -            | -                | -                | -         |    -8.96 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1160 | 2024-06-12 | Nemiga            | W   | 0.838      | 0.143        | 0.315 (0.038)    | 0.721 (0.086)    | 0 (0.000) |    22.91 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1182 | 2024-06-11 | Nexus             | W   | 0.831      | 0.143        | 0.014 (0.002)    | 0.457 (0.054)    | 0 (0.000) |    10.59 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1420 | 2024-06-06 | Zero Tenacity     | L   | 0.798      | -            | -                | -                | -         |    -3.81 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1449 | 2024-06-06 | 1WIN              | W   | 0.797      | 0.372        | 0.033 (0.010)    | 0.696 (0.206)    | 0 (0.000) |    18.91 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1551 | 2024-06-04 | RUSTEC            | W   | 0.783      | -            | -                | -                | 0 (0.000) |     2.61 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1600 | 2024-06-02 | JANO              | W   | 0.770      | 0.372        | 0.001 (0.000)    | 0.043 (0.012)    | 0 (0.000) |     8.49 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1660 | 2024-05-31 | Sangal            | L   | 0.757      | -            | -                | -                | -         |    -3.02 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1668 | 2024-05-31 | SAW               | L   | 0.756      | -            | -                | -                | -         |    -2.12 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1681 | 2024-05-30 | ARCRED            | L   | 0.751      | -            | -                | -                | -         |    -7.89 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1711 | 2024-05-29 | Aurora Young Blud | W   | 0.744      | 0.372        | 0.003 (0.001)    | 0.532 (0.148)    | 0 (0.000) |    13.85 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2280 | 2024-05-10 | Johnny Speeds     | L   | 0.615      | -            | -                | -                | -         |    -1.09 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3232 | 2024-04-03 | Metizport         | L   | 0.370      | -            | -                | -                | -         |    -4.63 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3262 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.365      | -            | -                | -                | -         |    -0.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3269 | 2024-04-02 | GamerLegion       | W   | 0.363      | 0.143        | 0.173 (0.009)    | 0.266 (0.014)    | 0 (0.000) |    10.05 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3295 | 2024-03-31 | Passion UA        | W   | 0.350      | 0.276        | 0.173 (0.017)    | 1.000 (0.097)    | 0 (0.000) |     9.12 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3300 | 2024-03-30 | L&G               | W   | 0.344      | -            | -                | -                | -         |     2.08 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3357 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.325      | 0.143        | 0.031 (0.001)    | 0.550 (0.026)    | -         |     7.89 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3366 | 2024-03-27 | BetBoom           | W   | 0.325      | 0.143        | 0.249 (0.012)    | 0.527 (0.024)    | -         |     9.97 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3703 | 2024-03-10 | AURA              | L   | 0.211      | -            | -                | -                | -         |    -5.44 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3747 | 2024-03-08 | Nexus             | L   | 0.198      | -            | -                | -                | -         |    -2.48 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3804 | 2024-03-06 | CYBERSHOKE        | W   | 0.184      | -            | -                | -                | -         |     2.16 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,079.08)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.825 | $750.00        | $618.65         |
| 2024-03-31 |      0.350 | $1,315.00      | $460.43         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
