### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, ayaka, Margo, meo<br />
Global Rank: [174](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
<br />
Final Rank Value:  651.8<br />
<br />
Final Rank Value (651.8) = Starting Rank Value (663.9) + Head To Head Adjustments (-12.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.9
- 400 + ( ( 0.129 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 663.9


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
|           15 |     1312 | 2024-06-08 | NOFEAR5           | L   | 0.809      | -            | -                | -                | -         |   -12.05 | akiyanora, amore, ayaka, Margo, meo |
|           14 |     1334 | 2024-06-08 | ENCE Athena       | W   | 0.807      | 0.270        | 0.002 (0.001)    | 0.034 (0.007)    | 0 (0.000) |    11.59 | akiyanora, amore, ayaka, Margo, meo |
|           13 |     1771 | 2024-05-26 | NIP Impact        | W   | 0.722      | 0.250        | 0.005 (0.001)    | 0.224 (0.040)    | 0 (0.000) |    13.95 | akiyanora, amore, ayaka, Margo, meo |
|           12 |     1997 | 2024-05-18 | Imperial fe       | L   | 0.668      | -            | -                | -                | -         |    -1.97 | akiyanora, amore, ayaka, Margo, meo |
|           11 |     2379 | 2024-05-05 | Imperial fe       | L   | 0.581      | -            | -                | -                | -         |    -1.75 | akiyanora, amore, ayaka, Margo, meo |
|           10 |     2740 | 2024-04-19 | NAVI Javelins     | L   | 0.475      | -            | -                | -                | -         |    -3.80 | akiyanora, amore, ayaka, Margo, meo |
|            9 |     2954 | 2024-04-11 | Fearless Cheetahs | L   | 0.422      | -            | -                | -                | -         |    -5.81 | akiyanora, amore, ayaka, Margo, meo |
|            8 |     3007 | 2024-04-10 | Permitta W        | L   | 0.414      | -            | -                | -                | -         |    -9.32 | akiyanora, amore, ayaka, Margo, meo |
|            7 |     3090 | 2024-04-08 | Imperial fe       | L   | 0.401      | -            | -                | -                | -         |    -1.36 | akiyanora, amore, ayaka, Margo, meo |
|            6 |     3325 | 2024-03-28 | 1WIN Gang         | W   | 0.329      | 0.331        | 0.001 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     5.09 | akiyanora, amore, ayaka, Margo, meo |
|            5 |     3477 | 2024-03-20 | Spirit fe         | L   | 0.276      | -            | -                | -                | -         |    -4.27 | akiyanora, amore, ayaka, Margo, meo |
|            4 |     3631 | 2024-03-13 | Let Her Cook      | L   | 0.229      | -            | -                | -                | -         |    -1.34 | akiyanora, amore, ayaka, Margo, meo |
|            3 |     3632 | 2024-03-13 | Let Her Cook      | L   | 0.229      | -            | -                | -                | -         |    -1.32 | akiyanora, amore, ayaka, Margo, meo |
|            2 |     4059 | 2024-02-24 | NAVI Javelins     | L   | 0.108      | -            | -                | -                | -         |    -1.01 | akiyanora, amore, ayaka, Margo, meo |
|            1 |     4190 | 2024-02-18 | dream catchers fe | W   | 0.069      | 0.143        | 0.016 (0.000)    | 0.171 (0.002)    | 0 (0.000) |     1.24 | akiyanora, amore, ayaka, Margo, meo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,442.57)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.809 | $300.00        | $242.63         |
| 2024-05-26 |      0.722 | $750.00        | $541.48         |
| 2024-05-05 |      0.581 | $250.00        | $145.28         |
| 2024-04-21 |      0.489 | $1,050.00      | $513.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
