### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, ayaka, Margo, meo<br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
<br />
Final Rank Value:  651.3<br />
<br />
Final Rank Value (651.3) = Starting Rank Value (663.6) + Head To Head Adjustments (-12.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.6
- 400 + ( ( 0.129 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 663.6


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
|           15 |     1284 | 2024-06-08 | NOFEAR5           | L   | 0.818      | -            | -                | -                | -         |   -12.18 | akiyanora, amore, ayaka, Margo, meo |
|           14 |     1306 | 2024-06-08 | ENCE Athena       | W   | 0.817      | 0.270        | 0.002 (0.001)    | 0.035 (0.008)    | 0 (0.000) |    11.73 | akiyanora, amore, ayaka, Margo, meo |
|           13 |     1743 | 2024-05-26 | NIP Impact        | W   | 0.731      | 0.250        | 0.005 (0.001)    | 0.228 (0.042)    | 0 (0.000) |    14.15 | akiyanora, amore, ayaka, Margo, meo |
|           12 |     1969 | 2024-05-18 | Imperial fe       | L   | 0.677      | -            | -                | -                | -         |    -1.99 | akiyanora, amore, ayaka, Margo, meo |
|           11 |     2351 | 2024-05-05 | Imperial fe       | L   | 0.590      | -            | -                | -                | -         |    -1.76 | akiyanora, amore, ayaka, Margo, meo |
|           10 |     2712 | 2024-04-19 | NAVI Javelins     | L   | 0.485      | -            | -                | -                | -         |    -3.85 | akiyanora, amore, ayaka, Margo, meo |
|            9 |     2926 | 2024-04-11 | Fearless Cheetahs | L   | 0.431      | -            | -                | -                | -         |    -5.92 | akiyanora, amore, ayaka, Margo, meo |
|            8 |     2979 | 2024-04-10 | Permitta W        | L   | 0.424      | -            | -                | -                | -         |    -9.52 | akiyanora, amore, ayaka, Margo, meo |
|            7 |     3062 | 2024-04-08 | Imperial fe       | L   | 0.410      | -            | -                | -                | -         |    -1.39 | akiyanora, amore, ayaka, Margo, meo |
|            6 |     3297 | 2024-03-28 | 1WIN Gang         | W   | 0.338      | 0.331        | 0.001 (0.000)    | 0.017 (0.002)    | 0 (0.000) |     5.23 | akiyanora, amore, ayaka, Margo, meo |
|            5 |     3449 | 2024-03-20 | Spirit fe         | L   | 0.285      | -            | -                | -                | -         |    -4.41 | akiyanora, amore, ayaka, Margo, meo |
|            4 |     3603 | 2024-03-13 | Let Her Cook      | L   | 0.238      | -            | -                | -                | -         |    -1.39 | akiyanora, amore, ayaka, Margo, meo |
|            3 |     3604 | 2024-03-13 | Let Her Cook      | L   | 0.238      | -            | -                | -                | -         |    -1.38 | akiyanora, amore, ayaka, Margo, meo |
|            2 |     4031 | 2024-02-24 | NAVI Javelins     | L   | 0.117      | -            | -                | -                | -         |    -1.10 | akiyanora, amore, ayaka, Margo, meo |
|            1 |     4162 | 2024-02-18 | dream catchers fe | W   | 0.078      | 0.143        | 0.016 (0.000)    | 0.173 (0.002)    | 0 (0.000) |     1.41 | akiyanora, amore, ayaka, Margo, meo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,464.11)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.818 | $300.00        | $245.38         |
| 2024-05-26 |      0.731 | $750.00        | $548.35         |
| 2024-05-05 |      0.590 | $250.00        | $147.57         |
| 2024-04-21 |      0.498 | $1,050.00      | $522.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
