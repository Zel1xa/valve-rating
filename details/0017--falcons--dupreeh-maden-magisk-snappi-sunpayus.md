### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1430.4<br />
<br />
Final Rank Value (1430.4) = Starting Rank Value (1419.0) + Head To Head Adjustments (11.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.604[<sup>1</sup>](#table2)
- Bounty Collected: 0.506[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.715[<sup>2</sup>](#table1)

The average of these factors is 0.497<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1419.0
- 400 + ( ( 0.497 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1419.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      107 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.74 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      227 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.101)    | 0.266 (0.155)    | 1 (1.000) |     5.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      260 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.63 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1026 | 2024-06-16 | Complexity       | L   | 0.866      | -            | -                | -                | -         |    -7.51 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1031 | 2024-06-16 | ENCE             | W   | 0.865      | 0.500        | 0.174 (0.075)    | 0.432 (0.187)    | 1 (0.865) |    11.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1060 | 2024-06-15 | The MongolZ      | W   | 0.859      | 0.500        | 1.000 (0.430)    | 0.710 (0.305)    | 1 (0.859) |    25.03 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1070 | 2024-06-15 | Party Astronauts | W   | 0.858      | 0.500        | 0.041 (0.018)    | 0.523 (0.224)    | 1 (0.858) |     2.17 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1111 | 2024-06-14 | Aurora           | L   | 0.851      | -            | -                | -                | -         |   -13.50 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1719 | 2024-05-28 | Liquid           | L   | 0.742      | -            | -                | -                | -         |    -6.31 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1740 | 2024-05-27 | Monte            | W   | 0.735      | 0.624        | 0.080 (0.037)    | 0.611 (0.280)    | 1 (0.735) |     2.28 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1752 | 2024-05-27 | G2               | L   | 0.733      | -            | -                | -                | -         |    -1.23 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2002 | 2024-05-18 | Spirit           | L   | 0.672      | -            | -                | -                | -         |    -1.33 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2034 | 2024-05-17 | Virtus.pro       | W   | 0.665      | 0.769        | 0.498 (0.255)    | 0.317 (0.162)    | 1 (0.665) |    17.01 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2113 | 2024-05-15 | BetBoom          | W   | 0.653      | 0.769        | 0.249 (0.125)    | 0.529 (0.266)    | 1 (0.653) |     9.21 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2172 | 2024-05-14 | Virtus.pro       | L   | 0.647      | -            | -                | -                | -         |    -3.49 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2547 | 2024-04-27 | G2               | L   | 0.532      | -            | -                | -                | -         |    -0.77 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2572 | 2024-04-26 | BetBoom          | L   | 0.525      | -            | -                | -                | -         |    -8.52 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2598 | 2024-04-25 | TYLOO            | W   | 0.518      | 0.889        | 0.019 (0.009)    | 0.089 (0.041)    | 1 (0.518) |     0.43 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2618 | 2024-04-24 | The MongolZ      | L   | 0.512      | -            | -                | -                | -         |    -0.95 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3793 | 2024-03-06 | Metizport        | L   | 0.187      | -            | -                | -                | -         |    -5.68 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4246 | 2024-02-16 | AMKAL            | L   | 0.058      | -            | -                | -                | -         |    -1.51 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4272 | 2024-02-15 | Eternal Fire     | L   | 0.052      | -            | -                | -                | -         |    -0.29 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4301 | 2024-02-14 | FaZe             | L   | 0.047      | -            | -                | -                | -         |    -0.28 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4306 | 2024-02-14 | 3DMAX            | W   | 0.046      | 0.143        | 0.508 (0.003)    | 1.000 (0.007)    | 1 (0.046) |     1.18 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4362 | 2024-02-10 | Spirit           | L   | 0.020      | -            | -                | -                | -         |    -0.04 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4375 | 2024-02-09 | ENCE             | W   | 0.014      | 1.000        | 0.174 (0.002)    | 0.432 (0.006)    | 1 (0.014) |     0.25 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,239.51)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.866 | $20,000.00     | $17,316.67      |
| 2024-06-02 |      0.774 | $5,000.00      | $3,868.06       |
| 2024-05-19 |      0.679 | $50,000.00     | $33,944.44      |
| 2024-05-12 |      0.633 | $7,000.00      | $4,429.44       |
| 2024-03-10 |      0.214 | $5,000.00      | $1,069.79       |
| 2024-02-11 |      0.026 | $80,000.00     | $2,111.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
