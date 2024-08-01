### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [15](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1448.4<br />
<br />
Final Rank Value (1448.4) = Starting Rank Value (1441.1) + Head To Head Adjustments (7.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.593[<sup>1</sup>](#table2)
- Bounty Collected: 0.512[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.745[<sup>2</sup>](#table1)

The average of these factors is 0.506<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1441.1
- 400 + ( ( 0.506 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1441.1


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
|           29 |       81 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.176 (0.102)    | 0.273 (0.159)    | 1 (1.000) |     5.12 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           28 |      115 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.89 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           27 |      895 | 2024-06-16 | Complexity       | L   | 0.894      | -            | -                | -                | -         |    -8.72 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           26 |      901 | 2024-06-16 | ENCE             | W   | 0.893      | 0.500        | 0.174 (0.078)    | 0.403 (0.180)    | 1 (0.893) |    10.34 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      928 | 2024-06-15 | The MongolZ      | W   | 0.887      | 0.500        | 1.000 (0.444)    | 0.719 (0.319)    | 1 (0.887) |    25.57 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      937 | 2024-06-15 | Party Astronauts | W   | 0.886      | 0.500        | 0.042 (0.019)    | 0.532 (0.236)    | 1 (0.886) |     2.23 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |      972 | 2024-06-14 | Aurora           | L   | 0.879      | -            | -                | -                | -         |   -14.85 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1597 | 2024-05-28 | Liquid           | L   | 0.770      | -            | -                | -                | -         |   -10.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1618 | 2024-05-27 | Monte            | W   | 0.763      | 0.624        | 0.081 (0.039)    | 0.614 (0.292)    | 1 (0.763) |     2.08 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1630 | 2024-05-27 | G2               | L   | 0.762      | -            | -                | -                | -         |    -1.46 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1908 | 2024-05-18 | Spirit           | L   | 0.700      | -            | -                | -                | -         |    -1.48 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1940 | 2024-05-17 | Virtus.pro       | W   | 0.693      | 0.769        | 0.483 (0.258)    | 0.326 (0.174)    | 1 (0.693) |    17.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     2019 | 2024-05-15 | BetBoom          | W   | 0.681      | 0.769        | 0.257 (0.135)    | 0.551 (0.289)    | 1 (0.681) |     9.25 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     2084 | 2024-05-14 | Virtus.pro       | L   | 0.675      | -            | -                | -                | -         |    -3.91 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2468 | 2024-04-27 | G2               | L   | 0.560      | -            | -                | -                | -         |    -0.93 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2492 | 2024-04-26 | BetBoom          | L   | 0.553      | -            | -                | -                | -         |    -9.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2518 | 2024-04-25 | TYLOO            | W   | 0.547      | 0.889        | 0.020 (0.010)    | 0.094 (0.046)    | 1 (0.547) |     0.40 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2538 | 2024-04-24 | The MongolZ      | L   | 0.540      | -            | -                | -                | -         |    -1.12 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     3743 | 2024-03-06 | Metizport        | L   | 0.215      | -            | -                | -                | -         |    -6.46 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|           10 |     4211 | 2024-02-16 | AMKAL            | L   | 0.086      | -            | -                | -                | -         |    -2.28 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            9 |     4237 | 2024-02-15 | Eternal Fire     | L   | 0.080      | -            | -                | -                | -         |    -0.45 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            8 |     4266 | 2024-02-14 | FaZe             | L   | 0.075      | -            | -                | -                | -         |    -0.42 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            7 |     4271 | 2024-02-14 | 3DMAX            | W   | 0.074      | 0.143        | -                | 1.000 (0.011)    | 1 (0.074) |     1.87 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            6 |     4336 | 2024-02-10 | Spirit           | L   | 0.048      | -            | -                | -                | -         |    -0.10 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4352 | 2024-02-09 | ENCE             | W   | 0.042      | 1.000        | 0.174 (0.007)    | 0.403 (0.017)    | 1 (0.042) |     0.73 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4385 | 2024-02-06 | Natus Vincere    | W   | 0.021      | 1.000        | 1.000 (0.021)    | -                | -         |     0.63 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4394 | 2024-02-05 | Complexity       | W   | 0.015      | -            | -                | -                | -         |     0.36 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4409 | 2024-02-04 | Rebels           | W   | 0.008      | -            | -                | -                | -         |     0.02 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4451 | 2024-02-03 | Eternal Fire     | L   | 0.000      | -            | -                | -                | -         |    -0.00 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,424.79)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.894 | $20,000.00     | $17,877.78      |
| 2024-06-02 |      0.802 | $5,000.00      | $4,008.33       |
| 2024-05-19 |      0.707 | $50,000.00     | $35,347.22      |
| 2024-05-12 |      0.661 | $7,000.00      | $4,625.83       |
| 2024-03-10 |      0.242 | $5,000.00      | $1,210.07       |
| 2024-02-11 |      0.054 | $80,000.00     | $4,355.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
