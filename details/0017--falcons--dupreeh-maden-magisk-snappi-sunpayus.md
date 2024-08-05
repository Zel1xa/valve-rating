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
Final Rank Value (1430.4) = Starting Rank Value (1419.1) + Head To Head Adjustments (11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.604[<sup>1</sup>](#table2)
- Bounty Collected: 0.506[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.715[<sup>2</sup>](#table1)

The average of these factors is 0.498<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1419.1
- 400 + ( ( 0.498 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1419.1


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
|           26 |       99 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.73 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      219 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.101)    | 0.269 (0.157)    | 1 (1.000) |     5.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      252 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.63 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1018 | 2024-06-16 | Complexity       | L   | 0.867      | -            | -                | -                | -         |    -7.52 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1023 | 2024-06-16 | ENCE             | W   | 0.866      | 0.500        | 0.168 (0.073)    | 0.438 (0.190)    | 1 (0.866) |    11.25 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1052 | 2024-06-15 | The MongolZ      | W   | 0.860      | 0.500        | 1.000 (0.430)    | 0.719 (0.309)    | 1 (0.860) |    25.06 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1062 | 2024-06-15 | Party Astronauts | W   | 0.859      | 0.500        | 0.041 (0.018)    | 0.529 (0.227)    | 1 (0.859) |     2.18 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1103 | 2024-06-14 | Aurora           | L   | 0.852      | -            | -                | -                | -         |   -13.61 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1711 | 2024-05-28 | Liquid           | L   | 0.743      | -            | -                | -                | -         |    -6.33 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1732 | 2024-05-27 | Monte            | W   | 0.736      | 0.624        | 0.080 (0.037)    | 0.618 (0.284)    | 1 (0.736) |     2.28 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1744 | 2024-05-27 | G2               | L   | 0.735      | -            | -                | -                | -         |    -1.23 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     1994 | 2024-05-18 | Spirit           | L   | 0.673      | -            | -                | -                | -         |    -1.33 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2026 | 2024-05-17 | Virtus.pro       | W   | 0.666      | 0.769        | 0.498 (0.255)    | 0.321 (0.164)    | 1 (0.666) |    17.05 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2105 | 2024-05-15 | BetBoom          | W   | 0.654      | 0.769        | 0.249 (0.125)    | 0.536 (0.270)    | 1 (0.654) |     9.24 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2164 | 2024-05-14 | Virtus.pro       | L   | 0.648      | -            | -                | -                | -         |    -3.49 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2539 | 2024-04-27 | G2               | L   | 0.533      | -            | -                | -                | -         |    -0.77 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2564 | 2024-04-26 | BetBoom          | L   | 0.526      | -            | -                | -                | -         |    -8.52 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2590 | 2024-04-25 | TYLOO            | W   | 0.520      | 0.889        | 0.019 (0.009)    | 0.090 (0.042)    | 1 (0.520) |     0.43 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2610 | 2024-04-24 | The MongolZ      | L   | 0.513      | -            | -                | -                | -         |    -0.95 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3785 | 2024-03-06 | Metizport        | L   | 0.188      | -            | -                | -                | -         |    -5.71 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4238 | 2024-02-16 | AMKAL            | L   | 0.059      | -            | -                | -                | -         |    -1.54 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4264 | 2024-02-15 | Eternal Fire     | L   | 0.053      | -            | -                | -                | -         |    -0.29 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4293 | 2024-02-14 | FaZe             | L   | 0.048      | -            | -                | -                | -         |    -0.28 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4298 | 2024-02-14 | 3DMAX            | W   | 0.047      | 0.143        | 0.508 (0.003)    | 1.000 (0.007)    | 1 (0.047) |     1.21 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4354 | 2024-02-10 | Spirit           | L   | 0.022      | -            | -                | -                | -         |    -0.04 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4367 | 2024-02-09 | ENCE             | W   | 0.015      | 1.000        | 0.168 (0.002)    | 0.438 (0.007)    | 1 (0.015) |     0.27 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,425.07)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.867 | $20,000.00     | $17,338.89      |
| 2024-06-02 |      0.775 | $5,000.00      | $3,873.61       |
| 2024-05-19 |      0.680 | $50,000.00     | $34,000.00      |
| 2024-05-12 |      0.634 | $7,000.00      | $4,437.22       |
| 2024-03-10 |      0.215 | $5,000.00      | $1,075.35       |
| 2024-02-11 |      0.028 | $80,000.00     | $2,200.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
