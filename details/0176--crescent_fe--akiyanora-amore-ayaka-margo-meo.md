### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, ayaka, Margo, meo<br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
<br />
Final Rank Value:  655.0<br />
<br />
Final Rank Value (655.0) = Starting Rank Value (666.5) + Head To Head Adjustments (-11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.300[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.5
- 400 + ( ( 0.129 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 666.5


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
|           14 |     1170 | 2024-06-08 | NOFEAR5           | L   | 0.842      | -            | -                | -                | -         |   -12.58 | akiyanora, amore, ayaka, Margo, meo |
|           13 |     1191 | 2024-06-08 | ENCE Athena       | W   | 0.840      | 0.270        | 0.002 (0.001)    | 0.038 (0.009)    | 0 (0.000) |    12.02 | akiyanora, amore, ayaka, Margo, meo |
|           12 |     1644 | 2024-05-26 | NIP Impact        | W   | 0.755      | 0.250        | 0.005 (0.001)    | 0.190 (0.036)    | 0 (0.000) |    14.54 | akiyanora, amore, ayaka, Margo, meo |
|           11 |     1895 | 2024-05-18 | Imperial fe       | L   | 0.701      | -            | -                | -                | -         |    -1.99 | akiyanora, amore, ayaka, Margo, meo |
|           10 |     2289 | 2024-05-05 | Imperial fe       | L   | 0.614      | -            | -                | -                | -         |    -1.78 | akiyanora, amore, ayaka, Margo, meo |
|            9 |     2660 | 2024-04-19 | NAVI Javelins     | L   | 0.508      | -            | -                | -                | -         |    -3.80 | akiyanora, amore, ayaka, Margo, meo |
|            8 |     2878 | 2024-04-11 | Fearless Cheetahs | L   | 0.455      | -            | -                | -                | -         |    -6.20 | akiyanora, amore, ayaka, Margo, meo |
|            7 |     2931 | 2024-04-10 | Permitta W        | L   | 0.447      | -            | -                | -                | -         |   -10.09 | akiyanora, amore, ayaka, Margo, meo |
|            6 |     3014 | 2024-04-08 | Imperial fe       | L   | 0.434      | -            | -                | -                | -         |    -1.43 | akiyanora, amore, ayaka, Margo, meo |
|            5 |     3257 | 2024-03-28 | 1WIN Gang         | W   | 0.362      | 0.331        | 0.001 (0.000)    | 0.017 (0.002)    | 0 (0.000) |     5.57 | akiyanora, amore, ayaka, Margo, meo |
|            4 |     3414 | 2024-03-20 | Spirit fe         | L   | 0.308      | -            | -                | -                | -         |    -4.87 | akiyanora, amore, ayaka, Margo, meo |
|            3 |     3572 | 2024-03-13 | Let Her Cook      | L   | 0.262      | -            | -                | -                | -         |    -1.48 | akiyanora, amore, ayaka, Margo, meo |
|            2 |     4013 | 2024-02-24 | NAVI Javelins     | L   | 0.140      | -            | -                | -                | -         |    -1.29 | akiyanora, amore, ayaka, Margo, meo |
|            1 |     4148 | 2024-02-18 | dream catchers fe | W   | 0.101      | 0.143        | 0.016 (0.000)    | 0.170 (0.002)    | 0 (0.000) |     1.83 | akiyanora, amore, ayaka, Margo, meo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,519.59)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.842 | $300.00        | $252.46         |
| 2024-05-26 |      0.755 | $750.00        | $566.06         |
| 2024-05-05 |      0.614 | $250.00        | $153.47         |
| 2024-04-21 |      0.522 | $1,050.00      | $547.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
