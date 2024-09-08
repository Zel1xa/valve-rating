### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, meo, Mileyyy, unknxwn<br />
Global Rank: [187](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [119]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  612.9<br />
<br />
Final Rank Value (612.9) = Starting Rank Value (635.4) + Head To Head Adjustments (-22.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 635.4
- 400 + ( ( 0.122 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 635.4


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
|           16 |       72 | 2024-09-05 | Permitta W        | L   | 1.000      | -            | -                | -                | -         |   -16.57 | akiyanora, amore, meo, Mileyyy, unknxwn |
|           15 |      264 | 2024-08-29 | BIG EQUIPA        | L   | 1.000      | -            | -                | -                | -         |   -12.76 | akiyanora, amore, meo, Mileyyy, unknxwn |
|           14 |     1115 | 2024-08-06 | ENCE Athena       | W   | 0.981      | 0.143        | 0.001 (0.000)    | 0.048 (0.007)    | 0 (0.000) |    13.50 | akiyanora, amore, ayaka, Margo, meo     |
|           13 |     2447 | 2024-06-08 | NOFEAR5           | L   | 0.588      | -            | -                | -                | -         |    -8.92 | akiyanora, amore, ayaka, Margo, meo     |
|           12 |     2469 | 2024-06-08 | ENCE Athena       | W   | 0.587      | 0.270        | 0.001 (0.000)    | 0.048 (0.008)    | 0 (0.000) |     8.50 | akiyanora, amore, ayaka, Margo, meo     |
|           11 |     2906 | 2024-05-26 | NIP Impact        | W   | 0.501      | 0.250        | 0.004 (0.000)    | 0.208 (0.026)    | 0 (0.000) |     9.08 | akiyanora, amore, ayaka, Margo, meo     |
|           10 |     3132 | 2024-05-18 | Imperial fe       | L   | 0.447      | -            | -                | -                | -         |    -2.27 | akiyanora, amore, ayaka, Margo, meo     |
|            9 |     3514 | 2024-05-05 | Imperial fe       | L   | 0.360      | -            | -                | -                | -         |    -1.86 | akiyanora, amore, ayaka, Margo, meo     |
|            8 |     3875 | 2024-04-19 | NAVI Javelins     | L   | 0.255      | -            | -                | -                | -         |    -2.57 | akiyanora, amore, ayaka, Margo, meo     |
|            7 |     4089 | 2024-04-11 | Fearless Cheetahs | L   | 0.201      | -            | -                | -                | -         |    -3.27 | akiyanora, amore, ayaka, Margo, meo     |
|            6 |     4142 | 2024-04-10 | Permitta W        | L   | 0.194      | -            | -                | -                | -         |    -4.27 | akiyanora, amore, ayaka, Margo, meo     |
|            5 |     4225 | 2024-04-08 | Imperial fe       | L   | 0.180      | -            | -                | -                | -         |    -1.01 | akiyanora, amore, ayaka, Margo, meo     |
|            4 |     4460 | 2024-03-28 | 1WIN Gang         | W   | 0.108      | 0.331        | 0.001 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.17 | akiyanora, amore, ayaka, Margo, meo     |
|            3 |     4612 | 2024-03-20 | Spirit fe         | L   | 0.055      | -            | -                | -                | -         |    -0.84 | akiyanora, amore, ayaka, Margo, meo     |
|            2 |     4766 | 2024-03-13 | Let Her Cook      | L   | 0.008      | -            | -                | -                | -         |    -0.18 | akiyanora, amore, ayaka, Margo, meo     |
|            1 |     4767 | 2024-03-13 | Let Her Cook      | L   | 0.008      | -            | -                | -                | -         |    -0.18 | akiyanora, amore, ayaka, Margo, meo     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($923.61)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.588 | $300.00        | $176.38         |
| 2024-05-26 |      0.501 | $750.00        | $375.85         |
| 2024-05-05 |      0.360 | $250.00        | $90.07          |
| 2024-04-21 |      0.268 | $1,050.00      | $281.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
