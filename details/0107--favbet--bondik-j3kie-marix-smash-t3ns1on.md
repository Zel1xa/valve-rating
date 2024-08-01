### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  849.1<br />
<br />
Final Rank Value (849.1) = Starting Rank Value (758.9) + Head To Head Adjustments (90.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.289[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.9
- 400 + ( ( 0.174 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 758.9


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
|           26 |      323 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -9.66 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      634 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.501 (0.072)    | 0 (0.000) |    23.70 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |      895 | 2024-06-16 | Zero Tenacity     | L   | 0.893      | -            | -                | -                | -         |    -7.26 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |      923 | 2024-06-15 | 9INE              | W   | 0.887      | -            | -                | -                | 0 (0.000) |     4.85 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |      954 | 2024-06-14 | ARCRED            | L   | 0.880      | -            | -                | -                | -         |   -10.67 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |     1022 | 2024-06-12 | Nemiga            | W   | 0.867      | 0.143        | 0.324 (0.040)    | 0.697 (0.086)    | 0 (0.000) |    23.37 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1045 | 2024-06-11 | Nexus             | W   | 0.860      | 0.143        | 0.014 (0.002)    | 0.504 (0.062)    | 0 (0.000) |    10.85 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1295 | 2024-06-06 | Zero Tenacity     | L   | 0.827      | -            | -                | -                | -         |    -4.22 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1324 | 2024-06-06 | 1WIN              | W   | 0.826      | 0.372        | 0.027 (0.008)    | 0.629 (0.193)    | 0 (0.000) |    18.90 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1429 | 2024-06-04 | RUSTEC            | W   | 0.812      | -            | -                | -                | 0 (0.000) |     2.67 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1479 | 2024-06-02 | JANO              | W   | 0.799      | 0.372        | 0.001 (0.000)    | 0.065 (0.019)    | 0 (0.000) |     9.28 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1539 | 2024-05-31 | Sangal            | L   | 0.786      | -            | -                | -                | -         |    -3.67 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1547 | 2024-05-31 | SAW               | L   | 0.785      | -            | -                | -                | -         |    -2.06 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1560 | 2024-05-30 | ARCRED            | L   | 0.780      | -            | -                | -                | -         |    -9.83 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1590 | 2024-05-29 | Aurora Young Blud | W   | 0.773      | 0.372        | 0.003 (0.001)    | 0.449 (0.129)    | 0 (0.000) |    13.46 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2196 | 2024-05-10 | Johnny Speeds     | L   | 0.644      | -            | -                | -                | -         |    -1.18 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3170 | 2024-04-03 | Metizport         | L   | 0.399      | -            | -                | -                | -         |    -4.04 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3202 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.394      | -            | -                | -                | -         |    -0.17 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3209 | 2024-04-02 | GamerLegion       | W   | 0.392      | 0.143        | 0.176 (0.010)    | 0.273 (0.015)    | 0 (0.000) |    10.88 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3235 | 2024-03-31 | Passion UA        | W   | 0.379      | 0.276        | 0.173 (0.018)    | 1.000 (0.105)    | 0 (0.000) |     9.82 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3240 | 2024-03-30 | L&G               | W   | 0.372      | -            | -                | -                | -         |     2.23 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3298 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.354      | 0.143        | 0.032 (0.002)    | 0.563 (0.028)    | -         |     8.60 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3307 | 2024-03-27 | BetBoom           | W   | 0.354      | 0.143        | 0.257 (0.013)    | 0.551 (0.028)    | -         |    10.87 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3653 | 2024-03-10 | AURA              | L   | 0.240      | -            | -                | -                | -         |    -6.14 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3698 | 2024-03-08 | Nexus             | L   | 0.227      | -            | -                | -                | -         |    -2.83 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3755 | 2024-03-06 | CYBERSHOKE        | W   | 0.213      | -            | -                | -                | -         |     2.51 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,138.73)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.854 | $750.00        | $640.31         |
| 2024-03-31 |      0.379 | $1,315.00      | $498.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
