### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1929.0<br />
<br />
Final Rank Value (1929.0) = Starting Rank Value (1904.1) + Head To Head Adjustments (24.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.665[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.733<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1904.1
- 400 + ( ( 0.733 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1904.1


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
|           30 |       81 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.342 (0.198)    | 0.373 (0.217)    | 1 (1.000) |     3.86 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      248 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.131)    | 0.364 (0.211)    | 1 (1.000) |     3.90 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      278 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      620 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.60 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      698 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.648 (0.648)    | 1 (1.000) |     1.43 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1028 | 2024-06-16 | Natus Vincere | W   | 0.864      | 0.729        | 1.000 (0.630)    | 0.365 (0.230)    | 1 (0.864) |    13.54 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1059 | 2024-06-15 | Vitality      | W   | 0.857      | 0.729        | 0.647 (0.405)    | 0.376 (0.235)    | 1 (0.857) |    11.51 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1123 | 2024-06-13 | Virtus.pro    | W   | 0.845      | 0.729        | 0.498 (0.307)    | 0.316 (0.195)    | 1 (0.845) |     5.33 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1154 | 2024-06-12 | G2            | W   | 0.839      | -            | -                | -                | 1 (0.839) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1617 | 2024-06-01 | Vitality      | L   | 0.765      | -            | -                | -                | -         |   -13.74 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1701 | 2024-05-29 | FaZe          | W   | 0.745      | 0.624        | 0.629 (0.292)    | 0.393 (0.183)    | 1 (0.745) |     6.41 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1731 | 2024-05-28 | Natus Vincere | W   | 0.738      | 0.624        | 1.000 (0.461)    | -                | 1 (0.738) |    12.86 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1746 | 2024-05-27 | FlyQuest      | W   | 0.732      | -            | -                | -                | -         |     0.47 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1969 | 2024-05-19 | MOUZ          | L   | 0.677      | -            | -                | -                | -         |   -10.95 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     2005 | 2024-05-18 | Falcons       | W   | 0.670      | -            | -                | -                | -         |     1.32 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2070 | 2024-05-16 | HEROIC        | W   | 0.657      | 0.769        | -                | 0.364 (0.184)    | -         |     2.53 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     2128 | 2024-05-15 | Aurora        | W   | 0.649      | 0.769        | 0.421 (0.210)    | 0.777 (0.388)    | -         |     2.94 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3319 | 2024-03-28 | FaZe          | L   | 0.332      | -            | -                | -                | -         |    -8.16 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3426 | 2024-03-22 | Natus Vincere | W   | 0.291      | 1.000        | 1.000 (0.291)    | -                | -         |     5.52 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3440 | 2024-03-21 | Imperial      | W   | 0.286      | 1.000        | -                | 0.674 (0.192)    | -         |     0.24 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3450 | 2024-03-21 | Cloud9        | W   | 0.284      | -            | -                | -                | -         |     0.07 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3698 | 2024-03-10 | Metizport     | W   | 0.212      | -            | -                | -                | -         |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3718 | 2024-03-09 | BIG           | W   | 0.205      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3753 | 2024-03-08 | Elevate       | W   | 0.197      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4108 | 2024-02-21 | HEROIC        | W   | 0.091      | -            | -                | -                | -         |     0.37 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4139 | 2024-02-20 | MOUZ          | L   | 0.084      | -            | -                | -                | -         |    -1.55 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4158 | 2024-02-19 | Astralis      | W   | 0.079      | -            | -                | -                | -         |     0.68 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4173 | 2024-02-19 | ENCE          | W   | 0.076      | -            | -                | -                | -         |     0.20 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4358 | 2024-02-11 | FaZe          | W   | 0.024      | -            | -                | -                | -         |     0.17 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4365 | 2024-02-10 | Falcons       | W   | 0.018      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($348,030.56)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.864 | $200,000.00    | $172,722.22     |
| 2024-06-02 |      0.771 | $20,000.00     | $15,427.78      |
| 2024-05-19 |      0.677 | $100,000.00    | $67,666.67      |
| 2024-03-31 |      0.351 | $45,000.00     | $15,812.50      |
| 2024-03-10 |      0.212 | $20,000.00     | $4,234.72       |
| 2024-02-11 |      0.024 | $400,000.00    | $9,666.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
