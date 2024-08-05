### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1462.0<br />
<br />
Final Rank Value (1462.0) = Starting Rank Value (1454.4) + Head To Head Adjustments (7.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.611[<sup>1</sup>](#table2)
- Bounty Collected: 0.513[<sup>2</sup>](#table1)
- Opponent Network: 0.173[<sup>2</sup>](#table1)
- LAN Wins: 0.748[<sup>2</sup>](#table1)

The average of these factors is 0.511<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1454.4
- 400 + ( ( 0.511 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1454.4


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
|           29 |       53 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.175 (0.102)    | 0.273 (0.159)    | 1 (1.000) |     4.96 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           28 |       86 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.78 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           27 |      852 | 2024-06-16 | Complexity       | L   | 0.898      | -            | -                | -                | -         |    -8.61 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           26 |      857 | 2024-06-16 | ENCE             | W   | 0.897      | 0.500        | 0.173 (0.078)    | 0.404 (0.181)    | 1 (0.897) |    10.80 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      886 | 2024-06-15 | The MongolZ      | W   | 0.892      | 0.500        | 1.000 (0.446)    | 0.719 (0.320)    | 1 (0.892) |    25.64 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      896 | 2024-06-15 | Party Astronauts | W   | 0.890      | 0.500        | 0.041 (0.018)    | 0.533 (0.237)    | 1 (0.890) |     2.04 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |      937 | 2024-06-14 | Aurora           | L   | 0.884      | -            | -                | -                | -         |   -15.23 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1545 | 2024-05-28 | Liquid           | L   | 0.774      | -            | -                | -                | -         |   -10.00 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1566 | 2024-05-27 | Monte            | W   | 0.767      | 0.624        | 0.080 (0.039)    | 0.613 (0.293)    | 1 (0.767) |     2.08 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1578 | 2024-05-27 | G2               | L   | 0.766      | -            | -                | -                | -         |    -1.56 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1828 | 2024-05-18 | Spirit           | L   | 0.704      | -            | -                | -                | -         |    -1.54 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1860 | 2024-05-17 | Virtus.pro       | W   | 0.698      | 0.769        | 0.494 (0.265)    | 0.327 (0.175)    | 1 (0.698) |    17.68 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1939 | 2024-05-15 | BetBoom          | W   | 0.686      | 0.769        | 0.256 (0.135)    | 0.554 (0.292)    | 1 (0.686) |     9.20 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1998 | 2024-05-14 | Virtus.pro       | L   | 0.679      | -            | -                | -                | -         |    -3.79 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2373 | 2024-04-27 | G2               | L   | 0.564      | -            | -                | -                | -         |    -0.99 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2398 | 2024-04-26 | BetBoom          | L   | 0.558      | -            | -                | -                | -         |    -9.41 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2424 | 2024-04-25 | TYLOO            | W   | 0.551      | 0.889        | 0.020 (0.010)    | 0.095 (0.047)    | 1 (0.551) |     0.38 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2444 | 2024-04-24 | The MongolZ      | L   | 0.544      | -            | -                | -                | -         |    -1.18 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     3619 | 2024-03-06 | Metizport        | L   | 0.220      | -            | -                | -                | -         |    -6.60 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|           10 |     4072 | 2024-02-16 | AMKAL            | L   | 0.091      | -            | -                | -                | -         |    -2.41 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            9 |     4098 | 2024-02-15 | Eternal Fire     | L   | 0.084      | -            | -                | -                | -         |    -0.49 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            8 |     4127 | 2024-02-14 | FaZe             | L   | 0.079      | -            | -                | -                | -         |    -0.46 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            7 |     4132 | 2024-02-14 | 3DMAX            | W   | 0.078      | 0.143        | -                | 1.000 (0.011)    | 1 (0.078) |     1.95 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            6 |     4188 | 2024-02-10 | Spirit           | L   | 0.053      | -            | -                | -                | -         |    -0.12 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4201 | 2024-02-09 | ENCE             | W   | 0.046      | 1.000        | 0.173 (0.008)    | 0.404 (0.019)    | 1 (0.046) |     0.80 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4236 | 2024-02-06 | Natus Vincere    | W   | 0.025      | 1.000        | 1.000 (0.025)    | -                | -         |     0.76 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4245 | 2024-02-05 | Complexity       | W   | 0.019      | -            | -                | -                | -         |     0.46 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4260 | 2024-02-04 | Rebels           | W   | 0.013      | -            | -                | -                | -         |     0.03 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4302 | 2024-02-03 | Eternal Fire     | L   | 0.004      | -            | -                | -                | -         |    -0.03 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($76,649.23)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.23) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.898 | $20,000.00     | $17,964.54      |
| 2024-06-02 |      0.806 | $5,000.00      | $4,030.02       |
| 2024-05-19 |      0.711 | $50,000.00     | $35,564.12      |
| 2024-05-12 |      0.665 | $7,000.00      | $4,656.20       |
| 2024-03-10 |      0.246 | $5,000.00      | $1,231.76       |
| 2024-02-11 |      0.059 | $80,000.00     | $4,702.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
