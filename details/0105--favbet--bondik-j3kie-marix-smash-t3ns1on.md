### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.9<br />
<br />
Final Rank Value (848.9) = Starting Rank Value (758.5) + Head To Head Adjustments (90.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.5
- 400 + ( ( 0.174 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 758.5


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
|           28 |        7 | 2024-08-06 | Lilmix            | W   | 1.000      | 0.143        | 0.023 (0.003)    | 0.095 (0.014)    | 0 (0.000) |    15.46 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           27 |      160 | 2024-08-01 | Meteor            | L   | 1.000      | -            | -                | -                | -         |   -19.14 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           26 |      477 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |   -10.18 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      778 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.061 (0.009)    | 0.537 (0.077)    | 0 (0.000) |    25.36 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |     1033 | 2024-06-16 | Zero Tenacity     | L   | 0.861      | -            | -                | -                | -         |    -5.56 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |     1063 | 2024-06-15 | 9INE              | W   | 0.855      | -            | -                | -                | 0 (0.000) |     4.51 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |     1101 | 2024-06-14 | ARCRED            | L   | 0.848      | -            | -                | -                | -         |    -9.03 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1170 | 2024-06-12 | Nemiga            | W   | 0.835      | 0.143        | 0.314 (0.037)    | 0.704 (0.084)    | 0 (0.000) |    22.76 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1192 | 2024-06-11 | Nexus             | W   | 0.828      | 0.143        | 0.014 (0.002)    | 0.447 (0.053)    | 0 (0.000) |    10.53 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1430 | 2024-06-06 | Zero Tenacity     | L   | 0.795      | -            | -                | -                | -         |    -3.79 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1459 | 2024-06-06 | 1WIN              | W   | 0.794      | 0.372        | 0.033 (0.010)    | 0.718 (0.212)    | 0 (0.000) |    18.75 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1561 | 2024-06-04 | RUSTEC            | W   | 0.780      | -            | -                | -                | 0 (0.000) |     2.56 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1610 | 2024-06-02 | JANO              | W   | 0.767      | -            | -                | -                | 0 (0.000) |     8.37 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1670 | 2024-05-31 | Sangal            | L   | 0.754      | -            | -                | -                | -         |    -3.04 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1678 | 2024-05-31 | SAW               | L   | 0.753      | -            | -                | -                | -         |    -2.18 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1691 | 2024-05-30 | ARCRED            | L   | 0.748      | -            | -                | -                | -         |    -7.96 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1721 | 2024-05-29 | Aurora Young Blud | W   | 0.741      | 0.372        | 0.019 (0.005)    | 0.521 (0.144)    | 0 (0.000) |    14.93 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2290 | 2024-05-10 | Johnny Speeds     | L   | 0.612      | -            | -                | -                | -         |    -1.09 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3242 | 2024-04-03 | Metizport         | L   | 0.367      | -            | -                | -                | -         |    -3.73 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3272 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.362      | -            | -                | -                | -         |    -0.07 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3279 | 2024-04-02 | GamerLegion       | W   | 0.360      | 0.143        | 0.173 (0.009)    | 0.259 (0.013)    | 0 (0.000) |     9.94 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3305 | 2024-03-31 | Passion UA        | W   | 0.347      | 0.276        | 0.173 (0.017)    | 1.000 (0.096)    | -         |     9.03 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3310 | 2024-03-30 | L&G               | W   | 0.340      | -            | -                | -                | -         |     2.04 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3367 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.322      | 0.143        | 0.031 (0.001)    | 0.537 (0.025)    | -         |     7.81 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3376 | 2024-03-27 | BetBoom           | W   | 0.322      | 0.143        | 0.248 (0.011)    | 0.514 (0.024)    | -         |     9.87 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3713 | 2024-03-10 | AURA              | L   | 0.208      | -            | -                | -                | -         |    -5.38 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3757 | 2024-03-08 | Nexus             | L   | 0.195      | -            | -                | -                | -         |    -2.44 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3814 | 2024-03-06 | CYBERSHOKE        | W   | 0.181      | -            | -                | -                | -         |     2.11 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,072.58)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.822 | $750.00        | $616.28         |
| 2024-03-31 |      0.347 | $1,315.00      | $456.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
