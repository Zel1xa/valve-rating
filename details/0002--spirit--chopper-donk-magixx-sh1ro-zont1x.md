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
Final Rank Value (1929.4) = Starting Rank Value (1904.3) + Head To Head Adjustments (25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.665[<sup>2</sup>](#table1)
- Opponent Network: 0.269[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.734<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1904.3
- 400 + ( ( 0.734 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1904.3


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
|           30 |       78 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.342 (0.199)    | 0.373 (0.217)    | 1 (1.000) |     3.87 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      245 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.131)    | 0.365 (0.212)    | 1 (1.000) |     3.91 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      275 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      617 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.62 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      695 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.649 (0.649)    | 1 (1.000) |     1.43 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1025 | 2024-06-16 | Natus Vincere | W   | 0.866      | 0.729        | 1.000 (0.631)    | 0.365 (0.231)    | 1 (0.866) |    13.57 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1056 | 2024-06-15 | Vitality      | W   | 0.859      | 0.729        | 0.648 (0.406)    | 0.376 (0.236)    | 1 (0.859) |    11.54 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1120 | 2024-06-13 | Virtus.pro    | W   | 0.847      | 0.729        | 0.498 (0.307)    | 0.317 (0.196)    | 1 (0.847) |     5.35 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1151 | 2024-06-12 | G2            | W   | 0.841      | -            | -                | -                | 1 (0.841) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1614 | 2024-06-01 | Vitality      | L   | 0.767      | -            | -                | -                | -         |   -13.78 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1698 | 2024-05-29 | FaZe          | W   | 0.748      | 0.624        | 0.631 (0.294)    | 0.394 (0.184)    | 1 (0.748) |     6.46 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1728 | 2024-05-28 | Natus Vincere | W   | 0.740      | 0.624        | 1.000 (0.462)    | -                | 1 (0.740) |    12.90 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1743 | 2024-05-27 | FlyQuest      | W   | 0.734      | -            | -                | -                | -         |     0.48 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1966 | 2024-05-19 | MOUZ          | L   | 0.679      | -            | -                | -                | -         |   -10.97 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     2002 | 2024-05-18 | Falcons       | W   | 0.672      | -            | -                | -                | -         |     1.33 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2067 | 2024-05-16 | HEROIC        | W   | 0.659      | 0.769        | -                | 0.365 (0.185)    | -         |     2.55 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     2125 | 2024-05-15 | Aurora        | W   | 0.651      | 0.769        | 0.422 (0.211)    | 0.779 (0.390)    | -         |     2.94 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3316 | 2024-03-28 | FaZe          | L   | 0.334      | -            | -                | -                | -         |    -8.20 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3423 | 2024-03-22 | Natus Vincere | W   | 0.293      | 1.000        | 1.000 (0.293)    | -                | -         |     5.56 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3437 | 2024-03-21 | Imperial      | W   | 0.288      | 1.000        | -                | 0.674 (0.194)    | -         |     0.25 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3447 | 2024-03-21 | Cloud9        | W   | 0.286      | -            | -                | -                | -         |     0.07 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3695 | 2024-03-10 | Metizport     | W   | 0.214      | -            | -                | -                | -         |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3715 | 2024-03-09 | BIG           | W   | 0.207      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3750 | 2024-03-08 | Elevate       | W   | 0.199      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4105 | 2024-02-21 | HEROIC        | W   | 0.093      | -            | -                | -                | -         |     0.38 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4136 | 2024-02-20 | MOUZ          | L   | 0.087      | -            | -                | -                | -         |    -1.59 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4155 | 2024-02-19 | Astralis      | W   | 0.081      | -            | -                | -                | -         |     0.70 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4170 | 2024-02-19 | ENCE          | W   | 0.079      | -            | -                | -                | -         |     0.21 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4355 | 2024-02-11 | FaZe          | W   | 0.026      | -            | -                | -                | -         |     0.18 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4362 | 2024-02-10 | Falcons       | W   | 0.020      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($349,775.00)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.866 | $200,000.00    | $173,166.67     |
| 2024-06-02 |      0.774 | $20,000.00     | $15,472.22      |
| 2024-05-19 |      0.679 | $100,000.00    | $67,888.89      |
| 2024-03-31 |      0.354 | $45,000.00     | $15,912.50      |
| 2024-03-10 |      0.214 | $20,000.00     | $4,279.17       |
| 2024-02-11 |      0.026 | $400,000.00    | $10,555.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
