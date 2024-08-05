### Roster Details<br />
Team Name: FAVBET<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  850.9<br />
<br />
Final Rank Value (850.9) = Starting Rank Value (759.1) + Head To Head Adjustments (91.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.289[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.072[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.1
- 400 + ( ( 0.174 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 759.1


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
|           26 |      290 | 2024-07-23 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -9.75 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           25 |      591 | 2024-07-16 | ECLOT             | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.502 (0.072)    | 0 (0.000) |    23.70 | bondik, j3kie, Marix, Smash, t3ns1on    |
|           24 |      846 | 2024-06-16 | Zero Tenacity     | L   | 0.899      | -            | -                | -                | -         |    -5.81 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           23 |      876 | 2024-06-15 | 9INE              | W   | 0.892      | -            | -                | -                | 0 (0.000) |     4.75 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           22 |      914 | 2024-06-14 | ARCRED            | L   | 0.886      | -            | -                | -                | -         |   -10.73 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           21 |      983 | 2024-06-12 | Nemiga            | W   | 0.872      | 0.143        | 0.322 (0.040)    | 0.698 (0.087)    | 0 (0.000) |    23.72 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           20 |     1005 | 2024-06-11 | Nexus             | W   | 0.866      | 0.143        | 0.014 (0.002)    | 0.465 (0.058)    | 0 (0.000) |    10.89 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           19 |     1243 | 2024-06-06 | Zero Tenacity     | L   | 0.833      | -            | -                | -                | -         |    -3.94 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           18 |     1272 | 2024-06-06 | 1WIN              | W   | 0.831      | 0.372        | 0.027 (0.008)    | 0.630 (0.195)    | 0 (0.000) |    18.99 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           17 |     1374 | 2024-06-04 | RUSTEC            | W   | 0.818      | -            | -                | -                | 0 (0.000) |     2.69 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           16 |     1423 | 2024-06-02 | JANO              | W   | 0.804      | 0.372        | 0.001 (0.000)    | 0.046 (0.014)    | 0 (0.000) |     8.85 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           15 |     1483 | 2024-05-31 | Sangal            | L   | 0.792      | -            | -                | -                | -         |    -3.37 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           14 |     1491 | 2024-05-31 | SAW               | L   | 0.791      | -            | -                | -                | -         |    -2.01 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           13 |     1504 | 2024-05-30 | ARCRED            | L   | 0.786      | -            | -                | -                | -         |    -9.90 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           12 |     1534 | 2024-05-29 | Aurora Young Blud | W   | 0.779      | 0.372        | 0.003 (0.001)    | 0.416 (0.120)    | 0 (0.000) |    12.58 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           11 |     2103 | 2024-05-10 | Johnny Speeds     | L   | 0.650      | -            | -                | -                | -         |    -1.19 | bondik, guthriee, j3kie, Smash, t3ns1on |
|           10 |     3055 | 2024-04-03 | Metizport         | L   | 0.405      | -            | -                | -                | -         |    -4.01 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            9 |     3085 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.399      | -            | -                | -                | -         |    -0.10 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            8 |     3092 | 2024-04-02 | GamerLegion       | W   | 0.398      | 0.143        | 0.175 (0.010)    | 0.273 (0.016)    | 0 (0.000) |    11.10 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            7 |     3118 | 2024-03-31 | Passion UA        | W   | 0.385      | 0.276        | 0.171 (0.018)    | 1.000 (0.106)    | 0 (0.000) |     9.88 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            6 |     3123 | 2024-03-30 | L&G               | W   | 0.378      | -            | -                | -                | -         |     2.26 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            5 |     3180 | 2024-03-27 | ALTERNATE aTTaX   | W   | 0.360      | 0.143        | 0.032 (0.002)    | 0.564 (0.029)    | -         |     8.80 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            4 |     3189 | 2024-03-27 | BetBoom           | W   | 0.359      | 0.143        | 0.256 (0.013)    | 0.554 (0.028)    | -         |    11.06 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            3 |     3526 | 2024-03-10 | AURA              | L   | 0.246      | -            | -                | -                | -         |    -6.28 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            2 |     3570 | 2024-03-08 | Nexus             | L   | 0.232      | -            | -                | -                | -         |    -2.92 | bondik, guthriee, j3kie, Smash, t3ns1on |
|            1 |     3627 | 2024-03-06 | CYBERSHOKE        | W   | 0.219      | -            | -                | -                | -         |     2.58 | bondik, guthriee, j3kie, Smash, t3ns1on |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,150.56)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.859 | $750.00        | $644.61         |
| 2024-03-31 |      0.385 | $1,315.00      | $505.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
