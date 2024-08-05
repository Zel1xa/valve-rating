### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, ayaka, Margo, meo<br />
Global Rank: [174](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
<br />
Final Rank Value:  651.7<br />
<br />
Final Rank Value (651.7) = Starting Rank Value (664.0) + Head To Head Adjustments (-12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 664.0
- 400 + ( ( 0.129 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 664.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1305 | 2024-06-08 | NOFEAR5           | L   | 0.813      | -            | -                | -                | -         |   -12.12 | akiyanora, amore, ayaka, Margo, meo |
|           14 |     1327 | 2024-06-08 | ENCE Athena       | W   | 0.812      | 0.270        | 0.002 (0.001)    | 0.034 (0.008)    | 0 (0.000) |    11.66 | akiyanora, amore, ayaka, Margo, meo |
|           13 |     1764 | 2024-05-26 | NIP Impact        | W   | 0.727      | 0.250        | 0.005 (0.001)    | 0.225 (0.041)    | 0 (0.000) |    14.05 | akiyanora, amore, ayaka, Margo, meo |
|           12 |     1990 | 2024-05-18 | Imperial fe       | L   | 0.673      | -            | -                | -                | -         |    -1.98 | akiyanora, amore, ayaka, Margo, meo |
|           11 |     2372 | 2024-05-05 | Imperial fe       | L   | 0.586      | -            | -                | -                | -         |    -1.76 | akiyanora, amore, ayaka, Margo, meo |
|           10 |     2733 | 2024-04-19 | NAVI Javelins     | L   | 0.480      | -            | -                | -                | -         |    -3.83 | akiyanora, amore, ayaka, Margo, meo |
|            9 |     2947 | 2024-04-11 | Fearless Cheetahs | L   | 0.427      | -            | -                | -                | -         |    -5.86 | akiyanora, amore, ayaka, Margo, meo |
|            8 |     3000 | 2024-04-10 | Permitta W        | L   | 0.419      | -            | -                | -                | -         |    -9.42 | akiyanora, amore, ayaka, Margo, meo |
|            7 |     3083 | 2024-04-08 | Imperial fe       | L   | 0.406      | -            | -                | -                | -         |    -1.38 | akiyanora, amore, ayaka, Margo, meo |
|            6 |     3318 | 2024-03-28 | 1WIN Gang         | W   | 0.334      | 0.331        | 0.001 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     5.17 | akiyanora, amore, ayaka, Margo, meo |
|            5 |     3470 | 2024-03-20 | Spirit fe         | L   | 0.280      | -            | -                | -                | -         |    -4.34 | akiyanora, amore, ayaka, Margo, meo |
|            4 |     3624 | 2024-03-13 | Let Her Cook      | L   | 0.234      | -            | -                | -                | -         |    -1.37 | akiyanora, amore, ayaka, Margo, meo |
|            3 |     3625 | 2024-03-13 | Let Her Cook      | L   | 0.234      | -            | -                | -                | -         |    -1.35 | akiyanora, amore, ayaka, Margo, meo |
|            2 |     4052 | 2024-02-24 | NAVI Javelins     | L   | 0.112      | -            | -                | -                | -         |    -1.06 | akiyanora, amore, ayaka, Margo, meo |
|            1 |     4183 | 2024-02-18 | dream catchers fe | W   | 0.073      | 0.143        | 0.016 (0.000)    | 0.170 (0.002)    | 0 (0.000) |     1.33 | akiyanora, amore, ayaka, Margo, meo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,453.66)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.813 | $300.00        | $244.04         |
| 2024-05-26 |      0.727 | $750.00        | $545.02         |
| 2024-05-05 |      0.586 | $250.00        | $146.46         |
| 2024-04-21 |      0.493 | $1,050.00      | $518.15         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
