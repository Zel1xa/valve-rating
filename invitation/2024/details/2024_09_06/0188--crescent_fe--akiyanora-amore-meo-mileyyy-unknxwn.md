### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, meo, Mileyyy, unknxwn<br />
Global Rank: [188](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [120]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  615.3<br />
<br />
Final Rank Value (615.3) = Starting Rank Value (638.3) + Head To Head Adjustments (-23.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 638.3
- 400 + ( ( 0.122 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 638.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |       37 | 2024-09-05 | Permitta W        | L   | 1.000      | -            | -                | -                | -         |   -16.57 | akiyanora, amore, meo, Mileyyy, unknxwn |
|           15 |      227 | 2024-08-29 | BIG EQUIPA        | L   | 1.000      | -            | -                | -                | -         |   -12.68 | akiyanora, amore, meo, Mileyyy, unknxwn |
|           14 |     1078 | 2024-08-06 | ENCE Athena       | W   | 0.993      | 0.143        | 0.001 (0.000)    | 0.049 (0.007)    | 0 (0.000) |    13.66 | akiyanora, amore, ayaka, Margo, meo     |
|           13 |     2410 | 2024-06-08 | NOFEAR5           | L   | 0.600      | -            | -                | -                | -         |    -9.08 | akiyanora, amore, ayaka, Margo, meo     |
|           12 |     2432 | 2024-06-08 | ENCE Athena       | W   | 0.599      | 0.270        | 0.001 (0.000)    | 0.049 (0.008)    | 0 (0.000) |     8.67 | akiyanora, amore, ayaka, Margo, meo     |
|           11 |     2869 | 2024-05-26 | NIP Impact        | W   | 0.513      | 0.250        | 0.004 (0.000)    | 0.215 (0.028)    | 0 (0.000) |     9.34 | akiyanora, amore, ayaka, Margo, meo     |
|           10 |     3095 | 2024-05-18 | Imperial fe       | L   | 0.459      | -            | -                | -                | -         |    -2.25 | akiyanora, amore, ayaka, Margo, meo     |
|            9 |     3477 | 2024-05-05 | Imperial fe       | L   | 0.372      | -            | -                | -                | -         |    -1.86 | akiyanora, amore, ayaka, Margo, meo     |
|            8 |     3838 | 2024-04-19 | NAVI Javelins     | L   | 0.267      | -            | -                | -                | -         |    -2.66 | akiyanora, amore, ayaka, Margo, meo     |
|            7 |     4052 | 2024-04-11 | Fearless Cheetahs | L   | 0.213      | -            | -                | -                | -         |    -3.45 | akiyanora, amore, ayaka, Margo, meo     |
|            6 |     4105 | 2024-04-10 | Permitta W        | L   | 0.206      | -            | -                | -                | -         |    -4.54 | akiyanora, amore, ayaka, Margo, meo     |
|            5 |     4188 | 2024-04-08 | Imperial fe       | L   | 0.192      | -            | -                | -                | -         |    -1.04 | akiyanora, amore, ayaka, Margo, meo     |
|            4 |     4423 | 2024-03-28 | 1WIN Gang         | W   | 0.120      | 0.331        | 0.001 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.29 | akiyanora, amore, ayaka, Margo, meo     |
|            3 |     4575 | 2024-03-20 | Spirit fe         | L   | 0.067      | -            | -                | -                | -         |    -1.02 | akiyanora, amore, ayaka, Margo, meo     |
|            2 |     4729 | 2024-03-13 | Let Her Cook      | L   | 0.020      | -            | -                | -                | -         |    -0.43 | akiyanora, amore, ayaka, Margo, meo     |
|            1 |     4730 | 2024-03-13 | Let Her Cook      | L   | 0.020      | -            | -                | -                | -         |    -0.43 | akiyanora, amore, ayaka, Margo, meo     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($951.62)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.600 | $300.00        | $179.95         |
| 2024-05-26 |      0.513 | $750.00        | $384.79         |
| 2024-05-05 |      0.372 | $250.00        | $93.05          |
| 2024-04-21 |      0.280 | $1,050.00      | $293.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
