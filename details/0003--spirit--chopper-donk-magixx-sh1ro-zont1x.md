### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1931.4<br />
<br />
Final Rank Value (1931.4) = Starting Rank Value (1909.9) + Head To Head Adjustments (21.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.663[<sup>2</sup>](#table1)
- Opponent Network: 0.273[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.734<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1909.9
- 400 + ( ( 0.734 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1909.9


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
|           31 |      107 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.208 (0.121)    | 0.380 (0.221)    | 1 (1.000) |     3.67 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      138 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.18 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      487 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -15.07 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      565 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.201 (0.201)    | 0.637 (0.637)    | 1 (1.000) |     1.04 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      902 | 2024-06-16 | Natus Vincere | W   | 0.892      | 0.729        | 1.000 (0.650)    | 0.331 (0.216)    | 1 (0.892) |    14.00 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      933 | 2024-06-15 | Vitality      | W   | 0.886      | 0.729        | 0.590 (0.381)    | 0.384 (0.248)    | 1 (0.886) |    11.40 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |      987 | 2024-06-13 | Virtus.pro    | W   | 0.874      | 0.729        | 0.484 (0.308)    | 0.326 (0.208)    | 1 (0.874) |     5.43 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1018 | 2024-06-12 | G2            | W   | 0.867      | -            | -                | -                | 1 (0.867) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1499 | 2024-06-01 | Vitality      | L   | 0.793      | -            | -                | -                | -         |   -14.77 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1582 | 2024-05-29 | FaZe          | W   | 0.774      | 0.624        | 0.637 (0.308)    | 0.408 (0.197)    | 1 (0.774) |     7.19 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1612 | 2024-05-28 | Natus Vincere | W   | 0.766      | 0.624        | 1.000 (0.478)    | 0.331 (0.159)    | 1 (0.766) |    13.43 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1627 | 2024-05-27 | FlyQuest      | W   | 0.761      | -            | -                | -                | 1 (0.761) |     0.53 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1877 | 2024-05-19 | MOUZ          | L   | 0.705      | -            | -                | -                | -         |   -10.95 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1914 | 2024-05-18 | Falcons       | W   | 0.698      | 0.769        | 0.205 (0.110)    | -                | -         |     1.48 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1979 | 2024-05-16 | HEROIC        | W   | 0.686      | 0.769        | -                | 0.380 (0.200)    | -         |     2.55 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     2041 | 2024-05-15 | Aurora        | W   | 0.678      | 0.769        | 0.431 (0.225)    | 0.798 (0.416)    | -         |     2.96 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     3261 | 2024-03-28 | FaZe          | L   | 0.360      | -            | -                | -                | -         |    -8.54 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     3373 | 2024-03-22 | Natus Vincere | W   | 0.320      | 1.000        | 1.000 (0.320)    | -                | -         |     6.13 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3387 | 2024-03-21 | Imperial      | W   | 0.314      | 1.000        | -                | 0.719 (0.226)    | -         |     0.29 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3397 | 2024-03-21 | Cloud9        | W   | 0.313      | -            | -                | -                | -         |     0.09 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3650 | 2024-03-10 | Metizport     | W   | 0.240      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3671 | 2024-03-09 | BIG           | W   | 0.234      | -            | -                | -                | -         |     0.16 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3706 | 2024-03-08 | Elevate       | W   | 0.226      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     4076 | 2024-02-21 | HEROIC        | W   | 0.120      | -            | -                | -                | -         |     0.51 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     4107 | 2024-02-20 | MOUZ          | L   | 0.113      | -            | -                | -                | -         |    -1.99 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4126 | 2024-02-19 | Astralis      | W   | 0.107      | -            | -                | -                | -         |     0.76 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4141 | 2024-02-19 | ENCE          | W   | 0.105      | -            | -                | -                | -         |     0.27 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4335 | 2024-02-11 | FaZe          | W   | 0.053      | -            | -                | -                | -         |     0.42 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4342 | 2024-02-10 | Falcons       | W   | 0.047      | -            | -                | -                | -         |     0.10 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4392 | 2024-02-06 | FaZe          | W   | 0.019      | -            | -                | -                | -         |     0.15 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4421 | 2024-02-04 | Complexity    | W   | 0.006      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($347,990.28)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.892 | $200,000.00    | $178,444.44     |
| 2024-06-02 |      0.800 | $20,000.00     | $16,000.00      |
| 2024-05-19 |      0.705 | $100,000.00    | $70,527.78      |
| 2024-03-31 |      0.380 | $45,000.00     | $17,100.00      |
| 2024-03-10 |      0.240 | $20,000.00     | $4,806.94       |
| 2024-02-11 |      0.053 | $400,000.00    | $21,111.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
