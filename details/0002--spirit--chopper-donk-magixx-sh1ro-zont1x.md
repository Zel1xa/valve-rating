### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1929.4<br />
<br />
Final Rank Value (1929.4) = Starting Rank Value (1904.3) + Head To Head Adjustments (25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.666[<sup>2</sup>](#table1)
- Opponent Network: 0.273[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.735<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1904.3
- 400 + ( ( 0.735 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1904.3


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
|           30 |       70 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.342 (0.199)    | 0.378 (0.220)    | 1 (1.000) |     3.87 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      237 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.131)    | 0.370 (0.215)    | 1 (1.000) |     3.92 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      267 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      609 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.62 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      687 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.657 (0.657)    | 1 (1.000) |     1.44 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1017 | 2024-06-16 | Natus Vincere | W   | 0.867      | 0.729        | 1.000 (0.632)    | 0.370 (0.234)    | 1 (0.867) |    13.59 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1048 | 2024-06-15 | Vitality      | W   | 0.861      | 0.729        | 0.648 (0.406)    | 0.381 (0.239)    | 1 (0.861) |    11.57 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1112 | 2024-06-13 | Virtus.pro    | W   | 0.848      | 0.729        | 0.498 (0.308)    | 0.321 (0.199)    | 1 (0.848) |     5.37 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1143 | 2024-06-12 | G2            | W   | 0.842      | -            | -                | -                | 1 (0.842) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1606 | 2024-06-01 | Vitality      | L   | 0.768      | -            | -                | -                | -         |   -13.79 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1690 | 2024-05-29 | FaZe          | W   | 0.749      | 0.624        | 0.632 (0.295)    | 0.399 (0.186)    | 1 (0.749) |     6.49 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1720 | 2024-05-28 | Natus Vincere | W   | 0.741      | 0.624        | 1.000 (0.463)    | -                | 1 (0.741) |    12.92 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1735 | 2024-05-27 | FlyQuest      | W   | 0.736      | -            | -                | -                | -         |     0.48 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1958 | 2024-05-19 | MOUZ          | L   | 0.680      | -            | -                | -                | -         |   -10.96 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     1994 | 2024-05-18 | Falcons       | W   | 0.673      | -            | -                | -                | -         |     1.33 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2059 | 2024-05-16 | HEROIC        | W   | 0.660      | 0.769        | -                | 0.370 (0.188)    | -         |     2.56 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     2117 | 2024-05-15 | Aurora        | W   | 0.652      | 0.769        | 0.422 (0.212)    | 0.788 (0.395)    | -         |     2.90 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3308 | 2024-03-28 | FaZe          | L   | 0.335      | -            | -                | -                | -         |    -8.22 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3415 | 2024-03-22 | Natus Vincere | W   | 0.294      | 1.000        | 1.000 (0.294)    | -                | -         |     5.58 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3429 | 2024-03-21 | Imperial      | W   | 0.289      | 1.000        | -                | 0.683 (0.197)    | -         |     0.25 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3439 | 2024-03-21 | Cloud9        | W   | 0.287      | -            | -                | -                | -         |     0.07 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3687 | 2024-03-10 | Metizport     | W   | 0.215      | -            | -                | -                | -         |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3707 | 2024-03-09 | BIG           | W   | 0.208      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3742 | 2024-03-08 | Elevate       | W   | 0.200      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4097 | 2024-02-21 | HEROIC        | W   | 0.094      | -            | -                | -                | -         |     0.39 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4128 | 2024-02-20 | MOUZ          | L   | 0.088      | -            | -                | -                | -         |    -1.61 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4147 | 2024-02-19 | Astralis      | W   | 0.082      | -            | -                | -                | -         |     0.71 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4162 | 2024-02-19 | ENCE          | W   | 0.080      | -            | -                | -                | -         |     0.21 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4347 | 2024-02-11 | FaZe          | W   | 0.028      | -            | -                | -                | -         |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4354 | 2024-02-10 | Falcons       | W   | 0.022      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($350,647.22)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.867 | $200,000.00    | $173,388.89     |
| 2024-06-02 |      0.775 | $20,000.00     | $15,494.44      |
| 2024-05-19 |      0.680 | $100,000.00    | $68,000.00      |
| 2024-03-31 |      0.355 | $45,000.00     | $15,962.50      |
| 2024-03-10 |      0.215 | $20,000.00     | $4,301.39       |
| 2024-02-11 |      0.028 | $400,000.00    | $11,000.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
