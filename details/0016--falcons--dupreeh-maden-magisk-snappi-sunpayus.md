### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1448.3<br />
<br />
Final Rank Value (1448.3) = Starting Rank Value (1438.9) + Head To Head Adjustments (9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.593[<sup>1</sup>](#table2)
- Bounty Collected: 0.511[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.744[<sup>2</sup>](#table1)

The average of these factors is 0.505<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1438.9
- 400 + ( ( 0.505 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1438.9


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
|           28 |       88 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.176 (0.102)    | 0.273 (0.158)    | 1 (1.000) |     5.11 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           27 |      121 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.83 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           26 |      901 | 2024-06-16 | Complexity       | L   | 0.892      | -            | -                | -                | -         |    -8.69 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      907 | 2024-06-16 | ENCE             | W   | 0.891      | 0.500        | 0.173 (0.077)    | 0.403 (0.180)    | 1 (0.891) |    10.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      934 | 2024-06-15 | The MongolZ      | W   | 0.886      | 0.500        | 1.000 (0.443)    | 0.719 (0.319)    | 1 (0.886) |    25.54 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |      943 | 2024-06-15 | Party Astronauts | W   | 0.884      | 0.500        | 0.042 (0.018)    | 0.532 (0.235)    | 1 (0.884) |     2.22 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |      978 | 2024-06-14 | Aurora           | L   | 0.878      | -            | -                | -                | -         |   -14.79 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1603 | 2024-05-28 | Liquid           | L   | 0.768      | -            | -                | -                | -         |    -8.68 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1624 | 2024-05-27 | Monte            | W   | 0.761      | 0.624        | 0.081 (0.039)    | 0.614 (0.292)    | 1 (0.761) |     2.08 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1636 | 2024-05-27 | G2               | L   | 0.760      | -            | -                | -                | -         |    -1.44 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1914 | 2024-05-18 | Spirit           | L   | 0.698      | -            | -                | -                | -         |    -1.48 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1946 | 2024-05-17 | Virtus.pro       | W   | 0.692      | 0.769        | 0.484 (0.257)    | 0.326 (0.173)    | 1 (0.692) |    17.40 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     2025 | 2024-05-15 | BetBoom          | W   | 0.680      | 0.769        | 0.257 (0.134)    | 0.551 (0.288)    | 1 (0.680) |     9.29 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2090 | 2024-05-14 | Virtus.pro       | L   | 0.673      | -            | -                | -                | -         |    -3.88 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2474 | 2024-04-27 | G2               | L   | 0.558      | -            | -                | -                | -         |    -0.91 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2498 | 2024-04-26 | BetBoom          | L   | 0.552      | -            | -                | -                | -         |    -9.18 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2524 | 2024-04-25 | TYLOO            | W   | 0.545      | 0.889        | 0.020 (0.010)    | 0.094 (0.046)    | 1 (0.545) |     0.40 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2544 | 2024-04-24 | The MongolZ      | L   | 0.538      | -            | -                | -                | -         |    -1.10 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     3749 | 2024-03-06 | Metizport        | L   | 0.214      | -            | -                | -                | -         |    -6.40 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            9 |     4217 | 2024-02-16 | AMKAL            | L   | 0.085      | -            | -                | -                | -         |    -2.23 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            8 |     4243 | 2024-02-15 | Eternal Fire     | L   | 0.078      | -            | -                | -                | -         |    -0.44 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            7 |     4272 | 2024-02-14 | FaZe             | L   | 0.073      | -            | -                | -                | -         |    -0.41 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            6 |     4277 | 2024-02-14 | 3DMAX            | W   | 0.072      | 0.143        | -                | 1.000 (0.010)    | 1 (0.072) |     1.83 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4342 | 2024-02-10 | Spirit           | L   | 0.047      | -            | -                | -                | -         |    -0.10 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4358 | 2024-02-09 | ENCE             | W   | 0.040      | 1.000        | 0.173 (0.007)    | 0.403 (0.016)    | 1 (0.040) |     0.70 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4391 | 2024-02-06 | Natus Vincere    | W   | 0.019      | 1.000        | 1.000 (0.019)    | -                | -         |     0.58 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4400 | 2024-02-05 | Complexity       | W   | 0.013      | -            | -                | -                | -         |     0.32 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4415 | 2024-02-04 | Rebels           | W   | 0.007      | -            | -                | -                | -         |     0.02 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,146.46)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $20,000.00     | $17,844.44      |
| 2024-06-02 |      0.800 | $5,000.00      | $4,000.00       |
| 2024-05-19 |      0.705 | $50,000.00     | $35,263.89      |
| 2024-05-12 |      0.659 | $7,000.00      | $4,614.17       |
| 2024-03-10 |      0.240 | $5,000.00      | $1,201.74       |
| 2024-02-11 |      0.053 | $80,000.00     | $4,222.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
