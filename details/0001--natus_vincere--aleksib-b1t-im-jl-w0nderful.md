### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1967.7<br />
<br />
Final Rank Value (1967.7) = Starting Rank Value (1987.1) + Head To Head Adjustments (-19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.765[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.771<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1987.1
- 400 + ( ( 0.771 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1987.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |       41 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.52 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |      361 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.500 (0.500)    | 1 (1.000) |    15.58 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |      396 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.378 (0.378)    | 1 (1.000) |    13.46 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      427 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.638 (0.638)    | 0.408 (0.408)    | 1 (1.000) |     7.86 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      571 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.286 (0.286)    | 0.495 (0.495)    | 1 (1.000) |     3.88 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      896 | 2024-06-16 | Spirit       | L   | 0.894      | -            | -                | -                | -         |   -14.01 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      914 | 2024-06-15 | Virtus.pro   | W   | 0.889      | 0.729        | 0.483 (0.313)    | 0.326 (0.211)    | 1 (0.889) |     5.18 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      997 | 2024-06-13 | FaZe         | W   | 0.874      | 0.729        | 0.638 (0.407)    | 0.408 (0.260)    | 1 (0.874) |     7.44 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |     1026 | 2024-06-12 | Astralis     | W   | 0.867      | 0.729        | -                | 0.385 (0.243)    | 1 (0.867) |     5.70 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1585 | 2024-05-29 | HEROIC       | L   | 0.775      | -            | -                | -                | -         |   -21.77 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1606 | 2024-05-28 | Spirit       | L   | 0.768      | -            | -                | -                | -         |   -13.45 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1624 | 2024-05-27 | BIG          | W   | 0.762      | -            | -                | -                | 1 (0.762) |     0.40 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     2229 | 2024-05-08 | FaZe         | L   | 0.635      | -            | -                | -                | -         |   -15.30 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     2279 | 2024-05-05 | Complexity   | L   | 0.615      | -            | -                | -                | -         |   -16.86 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     2354 | 2024-05-02 | BIG          | W   | 0.593      | -            | -                | -                | 1 (0.593) |     0.25 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     2378 | 2024-05-01 | FlyQuest     | W   | 0.587      | -            | -                | -                | -         |     0.21 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     3229 | 2024-03-31 | FaZe         | W   | 0.382      | -            | -                | -                | -         |     2.34 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     3234 | 2024-03-30 | G2           | W   | 0.376      | 1.000        | 1.000 (0.376)    | 0.500 (0.188)    | -         |     6.07 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     3244 | 2024-03-29 | Eternal Fire | W   | 0.368      | 1.000        | 0.757 (0.278)    | -                | -         |     2.31 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     3342 | 2024-03-24 | paiN         | W   | 0.335      | 1.000        | -                | 0.801 (0.268)    | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3351 | 2024-03-23 | Cloud9       | L   | 0.329      | -            | -                | -                | -         |   -10.29 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3367 | 2024-03-22 | Spirit       | L   | 0.321      | -            | -                | -                | -         |    -6.16 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3383 | 2024-03-21 | G2           | W   | 0.316      | 1.000        | 1.000 (0.316)    | -                | -         |     5.12 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3400 | 2024-03-21 | The MongolZ  | W   | 0.313      | 1.000        | 1.000 (0.313)    | 0.719 (0.225)    | -         |     4.30 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     4201 | 2024-02-16 | BetBoom      | W   | 0.088      | -            | -                | -                | -         |     0.13 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     4230 | 2024-02-15 | Virtus.pro   | L   | 0.081      | -            | -                | -                | -         |    -2.09 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     4261 | 2024-02-14 | Enterprise   | W   | 0.076      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     4279 | 2024-02-14 | KOI          | W   | 0.073      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4385 | 2024-02-06 | Falcons      | L   | 0.021      | -            | -                | -                | -         |    -0.63 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4393 | 2024-02-05 | Eternal Fire | W   | 0.015      | -            | -                | -                | -         |     0.09 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4413 | 2024-02-04 | Apeks        | W   | 0.008      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4443 | 2024-02-03 | Spirit       | L   | 0.001      | -            | -                | -                | -         |    -0.02 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($687,658.47)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.894 | $85,000.00     | $75,980.56      |
| 2024-06-02 |      0.802 | $5,000.00      | $4,008.33       |
| 2024-05-12 |      0.661 | $23,500.00     | $15,529.58      |
| 2024-03-31 |      0.382 | $500,000.00    | $190,833.33     |
| 2024-02-11 |      0.054 | $24,000.00     | $1,306.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
