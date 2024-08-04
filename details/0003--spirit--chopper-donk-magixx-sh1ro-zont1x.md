### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1928.3<br />
<br />
Final Rank Value (1928.3) = Starting Rank Value (1903.4) + Head To Head Adjustments (25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.668[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.736<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1903.4
- 400 + ( ( 0.736 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1903.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |       19 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.311 (0.180)    | 0.380 (0.221)    | 1 (1.000) |     3.75 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      186 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.229 (0.133)    | 0.375 (0.218)    | 1 (1.000) |     3.87 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      216 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      557 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.72 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      638 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.210 (0.210)    | 0.659 (0.659)    | 1 (1.000) |     1.46 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      964 | 2024-06-16 | Natus Vincere | W   | 0.877      | 0.729        | 1.000 (0.640)    | 0.331 (0.212)    | 1 (0.877) |    13.64 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |      995 | 2024-06-15 | Vitality      | W   | 0.871      | 0.729        | 0.649 (0.412)    | 0.383 (0.243)    | 1 (0.871) |    11.62 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1059 | 2024-06-13 | Virtus.pro    | W   | 0.859      | 0.729        | 0.496 (0.311)    | 0.324 (0.203)    | 1 (0.859) |     5.42 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1090 | 2024-06-12 | G2            | W   | 0.852      | -            | -                | -                | 1 (0.852) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1553 | 2024-06-01 | Vitality      | L   | 0.779      | -            | -                | -                | -         |   -14.06 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1637 | 2024-05-29 | FaZe          | W   | 0.759      | 0.624        | 0.643 (0.304)    | 0.403 (0.191)    | 1 (0.759) |     6.63 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1667 | 2024-05-28 | Natus Vincere | W   | 0.752      | 0.624        | 1.000 (0.469)    | -                | 1 (0.752) |    13.03 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1682 | 2024-05-27 | FlyQuest      | W   | 0.746      | -            | -                | -                | -         |     0.50 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1905 | 2024-05-19 | MOUZ          | L   | 0.691      | -            | -                | -                | -         |   -11.15 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1941 | 2024-05-18 | Falcons       | W   | 0.684      | -            | -                | -                | -         |     1.38 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     2006 | 2024-05-16 | HEROIC        | W   | 0.671      | 0.769        | -                | 0.375 (0.193)    | -         |     2.59 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2064 | 2024-05-15 | Aurora        | W   | 0.663      | 0.769        | 0.424 (0.216)    | 0.794 (0.405)    | -         |     2.90 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     3254 | 2024-03-28 | FaZe          | L   | 0.346      | -            | -                | -                | -         |    -8.42 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3361 | 2024-03-22 | Natus Vincere | W   | 0.305      | 1.000        | 1.000 (0.305)    | -                | -         |     5.76 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3375 | 2024-03-21 | Imperial      | W   | 0.300      | 1.000        | -                | 0.685 (0.205)    | -         |     0.27 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3385 | 2024-03-21 | Cloud9        | W   | 0.298      | -            | -                | -                | -         |     0.08 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3632 | 2024-03-10 | Metizport     | W   | 0.226      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3652 | 2024-03-09 | BIG           | W   | 0.219      | -            | -                | -                | -         |     0.23 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3687 | 2024-03-08 | Elevate       | W   | 0.211      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     4042 | 2024-02-21 | HEROIC        | W   | 0.105      | -            | -                | -                | -         |     0.43 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4073 | 2024-02-20 | MOUZ          | L   | 0.098      | -            | -                | -                | -         |    -1.80 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4092 | 2024-02-19 | Astralis      | W   | 0.092      | -            | -                | -                | -         |     0.67 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4107 | 2024-02-19 | ENCE          | W   | 0.090      | -            | -                | -                | -         |     0.23 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4291 | 2024-02-11 | FaZe          | W   | 0.038      | -            | -                | -                | -         |     0.28 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4298 | 2024-02-10 | Falcons       | W   | 0.032      | -            | -                | -                | -         |     0.06 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4347 | 2024-02-06 | FaZe          | W   | 0.005      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($358,933.33)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.877 | $200,000.00    | $175,500.00     |
| 2024-06-02 |      0.785 | $20,000.00     | $15,705.56      |
| 2024-05-19 |      0.691 | $100,000.00    | $69,055.56      |
| 2024-03-31 |      0.365 | $45,000.00     | $16,437.50      |
| 2024-03-10 |      0.226 | $20,000.00     | $4,512.50       |
| 2024-02-11 |      0.038 | $400,000.00    | $15,222.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
