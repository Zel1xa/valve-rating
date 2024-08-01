### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1933.2<br />
<br />
Final Rank Value (1933.2) = Starting Rank Value (1912.0) + Head To Head Adjustments (21.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.664[<sup>2</sup>](#table1)
- Opponent Network: 0.273[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.734<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1912.0
- 400 + ( ( 0.734 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1912.0


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
|           32 |      101 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.209 (0.121)    | 0.381 (0.221)    | 1 (1.000) |     3.58 | chopper, donk, magixx, sh1ro, zont1x |
|           31 |      132 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.18 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      481 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -15.19 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      562 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.201 (0.201)    | 0.637 (0.637)    | 1 (1.000) |     1.03 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      896 | 2024-06-16 | Natus Vincere | W   | 0.894      | 0.729        | 1.000 (0.652)    | 0.331 (0.216)    | 1 (0.894) |    14.01 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      927 | 2024-06-15 | Vitality      | W   | 0.887      | 0.729        | 0.591 (0.382)    | 0.385 (0.249)    | 1 (0.887) |    11.41 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      981 | 2024-06-13 | Virtus.pro    | W   | 0.875      | 0.729        | 0.483 (0.308)    | 0.326 (0.208)    | 1 (0.875) |     5.42 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1012 | 2024-06-12 | G2            | W   | 0.869      | -            | -                | -                | 1 (0.869) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1493 | 2024-06-01 | Vitality      | L   | 0.795      | -            | -                | -                | -         |   -14.81 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1576 | 2024-05-29 | FaZe          | W   | 0.776      | 0.624        | 0.638 (0.309)    | 0.408 (0.198)    | 1 (0.776) |     7.20 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1606 | 2024-05-28 | Natus Vincere | W   | 0.768      | 0.624        | 1.000 (0.479)    | 0.331 (0.159)    | 1 (0.768) |    13.45 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1621 | 2024-05-27 | FlyQuest      | W   | 0.762      | -            | -                | -                | 1 (0.762) |     0.53 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1871 | 2024-05-19 | MOUZ          | L   | 0.707      | -            | -                | -                | -         |   -11.03 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1908 | 2024-05-18 | Falcons       | W   | 0.700      | 0.769        | 0.206 (0.111)    | -                | -         |     1.48 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1973 | 2024-05-16 | HEROIC        | W   | 0.687      | 0.769        | -                | 0.381 (0.201)    | -         |     2.50 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     2035 | 2024-05-15 | Aurora        | W   | 0.679      | 0.769        | 0.432 (0.226)    | 0.798 (0.417)    | -         |     2.93 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     3255 | 2024-03-28 | FaZe          | L   | 0.362      | -            | -                | -                | -         |    -8.58 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     3367 | 2024-03-22 | Natus Vincere | W   | 0.321      | 1.000        | 1.000 (0.321)    | -                | -         |     6.16 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     3381 | 2024-03-21 | Imperial      | W   | 0.316      | 1.000        | -                | 0.719 (0.227)    | -         |     0.29 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3391 | 2024-03-21 | Cloud9        | W   | 0.314      | -            | -                | -                | -         |     0.09 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3644 | 2024-03-10 | Metizport     | W   | 0.242      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3665 | 2024-03-09 | BIG           | W   | 0.235      | -            | -                | -                | -         |     0.16 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3700 | 2024-03-08 | Elevate       | W   | 0.227      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     4070 | 2024-02-21 | HEROIC        | W   | 0.121      | -            | -                | -                | -         |     0.51 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     4101 | 2024-02-20 | MOUZ          | L   | 0.115      | -            | -                | -                | -         |    -2.03 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     4120 | 2024-02-19 | Astralis      | W   | 0.109      | -            | -                | -                | -         |     0.77 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4135 | 2024-02-19 | ENCE          | W   | 0.107      | -            | -                | -                | -         |     0.27 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4329 | 2024-02-11 | FaZe          | W   | 0.054      | -            | -                | -                | -         |     0.43 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4336 | 2024-02-10 | Falcons       | W   | 0.048      | -            | -                | -                | -         |     0.10 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4386 | 2024-02-06 | FaZe          | W   | 0.021      | -            | -                | -                | -         |     0.17 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4415 | 2024-02-04 | Complexity    | W   | 0.008      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4443 | 2024-02-03 | Natus Vincere | W   | 0.001      | -            | -                | -                | -         |     0.02 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($349,298.61)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.894 | $200,000.00    | $178,777.78     |
| 2024-06-02 |      0.802 | $20,000.00     | $16,033.33      |
| 2024-05-19 |      0.707 | $100,000.00    | $70,694.44      |
| 2024-03-31 |      0.382 | $45,000.00     | $17,175.00      |
| 2024-03-10 |      0.242 | $20,000.00     | $4,840.28       |
| 2024-02-11 |      0.054 | $400,000.00    | $21,777.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
