### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1643.4<br />
<br />
Final Rank Value (1643.4) = Starting Rank Value (1701.1) + Head To Head Adjustments (-57.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.639[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.849[<sup>2</sup>](#table1)

The average of these factors is 0.636<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1701.1
- 400 + ( ( 0.636 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1701.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |       74 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.73 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      124 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -21.59 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      493 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.80 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      535 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.649 (0.649)    | 0.383 (0.383)    | 1 (1.000) |    22.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      640 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.310 (0.310)    | 0.380 (0.380)    | 1 (1.000) |    12.80 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      989 | 2024-06-15 | Natus Vincere | L   | 0.869      | -            | -                | -                | -         |    -5.23 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1026 | 2024-06-14 | Astralis      | W   | 0.862      | 0.729        | 0.352 (0.221)    | 0.382 (0.240)    | 1 (0.862) |    14.28 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1063 | 2024-06-13 | Spirit        | L   | 0.856      | -            | -                | -                | -         |    -5.39 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1103 | 2024-06-12 | Vitality      | W   | 0.848      | 0.729        | 0.649 (0.401)    | 0.383 (0.237)    | 1 (0.848) |    20.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1649 | 2024-05-29 | BIG           | L   | 0.755      | -            | -                | -                | -         |   -20.77 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1664 | 2024-05-28 | FaZe          | L   | 0.749      | -            | -                | -                | -         |    -9.52 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1685 | 2024-05-27 | HEROIC        | W   | 0.743      | 0.624        | 0.229 (0.106)    | 0.374 (0.173)    | 1 (0.743) |     8.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1977 | 2024-05-17 | Falcons       | L   | 0.674      | -            | -                | -                | -         |   -17.16 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2016 | 2024-05-16 | MOUZ          | L   | 0.667      | -            | -                | -                | -         |    -5.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2115 | 2024-05-14 | Falcons       | W   | 0.655      | 0.769        | 0.224 (0.113)    | -                | 1 (0.655) |     3.60 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2237 | 2024-05-09 | Complexity    | L   | 0.621      | -            | -                | -                | -         |   -10.51 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2256 | 2024-05-08 | The MongolZ   | W   | 0.616      | 0.889        | 1.000 (0.547)    | 0.721 (0.394)    | 1 (0.616) |    14.97 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2272 | 2024-05-07 | GamerLegion   | W   | 0.609      | 0.889        | 0.174 (0.094)    | -                | 1 (0.609) |     0.94 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2460 | 2024-04-28 | SAW           | W   | 0.548      | 0.889        | -                | 0.540 (0.263)    | 1 (0.548) |     1.09 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2491 | 2024-04-27 | fnatic        | W   | 0.540      | 0.889        | 0.371 (0.178)    | 0.708 (0.340)    | 1 (0.540) |     5.09 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2534 | 2024-04-25 | FaZe          | L   | 0.529      | -            | -                | -                | -         |    -7.52 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2557 | 2024-04-24 | SAW           | W   | 0.521      | 0.889        | -                | 0.540 (0.250)    | -         |     0.89 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2580 | 2024-04-23 | fnatic        | L   | 0.514      | -            | -                | -                | -         |   -11.53 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2876 | 2024-04-12 | G2            | L   | 0.439      | -            | -                | -                | -         |    -2.30 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2960 | 2024-04-10 | Astralis      | L   | 0.426      | -            | -                | -                | -         |    -6.89 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3012 | 2024-04-08 | FlyQuest      | W   | 0.419      | -            | -                | -                | -         |     0.65 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3042 | 2024-04-08 | Wildcard      | W   | 0.413      | -            | -                | -                | -         |     0.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3342 | 2024-03-24 | G2            | L   | 0.314      | -            | -                | -                | -         |    -1.63 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3356 | 2024-03-23 | Eternal Fire  | L   | 0.307      | -            | -                | -                | -         |    -4.77 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3373 | 2024-03-22 | HEROIC        | W   | 0.301      | -            | -                | -                | -         |     3.06 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3387 | 2024-03-21 | paiN          | W   | 0.296      | 1.000        | 0.327 (0.097)    | 0.866 (0.256)    | -         |     1.57 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3397 | 2024-03-21 | Imperial      | L   | 0.294      | -            | -                | -                | -         |    -8.54 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3599 | 2024-03-12 | HEROIC        | W   | 0.236      | -            | -                | -                | -         |     2.29 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3615 | 2024-03-11 | Apeks         | W   | 0.229      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3626 | 2024-03-11 | B8            | W   | 0.228      | -            | -                | -                | -         |     0.22 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4208 | 2024-02-15 | Natus Vincere | W   | 0.062      | -            | -                | -                | -         |     1.59 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4240 | 2024-02-14 | fnatic        | W   | 0.056      | -            | -                | -                | -         |     0.55 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4259 | 2024-02-14 | SAW           | W   | 0.054      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($161,192.73)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.874 | $40,000.00     | $34,977.78      |
| 2024-06-02 |      0.782 | $5,000.00      | $3,911.11       |
| 2024-05-12 |      0.641 | $32,000.00     | $20,524.44      |
| 2024-04-14 |      0.453 | $10,000.00     | $4,534.95       |
| 2024-03-31 |      0.362 | $20,000.00     | $7,244.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
