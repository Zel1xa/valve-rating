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
|           15 |     1306 | 2024-06-08 | NOFEAR5           | L   | 0.813      | -            | -                | -                | -         |   -12.11 | akiyanora, amore, ayaka, Margo, meo |
|           14 |     1328 | 2024-06-08 | ENCE Athena       | W   | 0.812      | 0.270        | 0.002 (0.001)    | 0.034 (0.007)    | 0 (0.000) |    11.66 | akiyanora, amore, ayaka, Margo, meo |
|           13 |     1765 | 2024-05-26 | NIP Impact        | W   | 0.726      | 0.250        | 0.005 (0.001)    | 0.225 (0.041)    | 0 (0.000) |    14.05 | akiyanora, amore, ayaka, Margo, meo |
|           12 |     1991 | 2024-05-18 | Imperial fe       | L   | 0.673      | -            | -                | -                | -         |    -1.98 | akiyanora, amore, ayaka, Margo, meo |
|           11 |     2373 | 2024-05-05 | Imperial fe       | L   | 0.585      | -            | -                | -                | -         |    -1.75 | akiyanora, amore, ayaka, Margo, meo |
|           10 |     2734 | 2024-04-19 | NAVI Javelins     | L   | 0.480      | -            | -                | -                | -         |    -3.82 | akiyanora, amore, ayaka, Margo, meo |
|            9 |     2948 | 2024-04-11 | Fearless Cheetahs | L   | 0.426      | -            | -                | -                | -         |    -5.86 | akiyanora, amore, ayaka, Margo, meo |
|            8 |     3001 | 2024-04-10 | Permitta W        | L   | 0.419      | -            | -                | -                | -         |    -9.41 | akiyanora, amore, ayaka, Margo, meo |
|            7 |     3084 | 2024-04-08 | Imperial fe       | L   | 0.405      | -            | -                | -                | -         |    -1.37 | akiyanora, amore, ayaka, Margo, meo |
|            6 |     3319 | 2024-03-28 | 1WIN Gang         | W   | 0.333      | 0.331        | 0.001 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     5.16 | akiyanora, amore, ayaka, Margo, meo |
|            5 |     3471 | 2024-03-20 | Spirit fe         | L   | 0.280      | -            | -                | -                | -         |    -4.34 | akiyanora, amore, ayaka, Margo, meo |
|            4 |     3625 | 2024-03-13 | Let Her Cook      | L   | 0.233      | -            | -                | -                | -         |    -1.36 | akiyanora, amore, ayaka, Margo, meo |
|            3 |     3626 | 2024-03-13 | Let Her Cook      | L   | 0.233      | -            | -                | -                | -         |    -1.35 | akiyanora, amore, ayaka, Margo, meo |
|            2 |     4053 | 2024-02-24 | NAVI Javelins     | L   | 0.112      | -            | -                | -                | -         |    -1.05 | akiyanora, amore, ayaka, Margo, meo |
|            1 |     4184 | 2024-02-18 | dream catchers fe | W   | 0.073      | 0.143        | 0.016 (0.000)    | 0.170 (0.002)    | 0 (0.000) |     1.32 | akiyanora, amore, ayaka, Margo, meo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,452.68)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.813 | $300.00        | $243.92         |
| 2024-05-26 |      0.726 | $750.00        | $544.70         |
| 2024-05-05 |      0.585 | $250.00        | $146.35         |
| 2024-04-21 |      0.493 | $1,050.00      | $517.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
