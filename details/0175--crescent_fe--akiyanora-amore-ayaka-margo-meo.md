### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, ayaka, Margo, meo<br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
<br />
Final Rank Value:  652.3<br />
<br />
Final Rank Value (652.3) = Starting Rank Value (663.7) + Head To Head Adjustments (-11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.7
- 400 + ( ( 0.129 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 663.7


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
|           14 |     1244 | 2024-06-08 | NOFEAR5           | L   | 0.825      | -            | -                | -                | -         |   -12.32 | akiyanora, amore, ayaka, Margo, meo |
|           13 |     1266 | 2024-06-08 | ENCE Athena       | W   | 0.824      | 0.270        | 0.002 (0.001)    | 0.036 (0.008)    | 0 (0.000) |    11.79 | akiyanora, amore, ayaka, Margo, meo |
|           12 |     1703 | 2024-05-26 | NIP Impact        | W   | 0.738      | 0.250        | 0.005 (0.001)    | 0.229 (0.042)    | 0 (0.000) |    14.21 | akiyanora, amore, ayaka, Margo, meo |
|           11 |     1929 | 2024-05-18 | Imperial fe       | L   | 0.685      | -            | -                | -                | -         |    -2.01 | akiyanora, amore, ayaka, Margo, meo |
|           10 |     2311 | 2024-05-05 | Imperial fe       | L   | 0.598      | -            | -                | -                | -         |    -1.79 | akiyanora, amore, ayaka, Margo, meo |
|            9 |     2671 | 2024-04-19 | NAVI Javelins     | L   | 0.492      | -            | -                | -                | -         |    -3.91 | akiyanora, amore, ayaka, Margo, meo |
|            8 |     2885 | 2024-04-11 | Fearless Cheetahs | L   | 0.438      | -            | -                | -                | -         |    -6.02 | akiyanora, amore, ayaka, Margo, meo |
|            7 |     2938 | 2024-04-10 | Permitta W        | L   | 0.431      | -            | -                | -                | -         |    -9.70 | akiyanora, amore, ayaka, Margo, meo |
|            6 |     3021 | 2024-04-08 | Imperial fe       | L   | 0.417      | -            | -                | -                | -         |    -1.42 | akiyanora, amore, ayaka, Margo, meo |
|            5 |     3256 | 2024-03-28 | 1WIN Gang         | W   | 0.345      | 0.331        | 0.001 (0.000)    | 0.017 (0.002)    | 0 (0.000) |     5.32 | akiyanora, amore, ayaka, Margo, meo |
|            4 |     3408 | 2024-03-20 | Spirit fe         | L   | 0.292      | -            | -                | -                | -         |    -4.54 | akiyanora, amore, ayaka, Margo, meo |
|            3 |     3562 | 2024-03-13 | Let Her Cook      | L   | 0.245      | -            | -                | -                | -         |    -1.44 | akiyanora, amore, ayaka, Margo, meo |
|            2 |     3989 | 2024-02-24 | NAVI Javelins     | L   | 0.124      | -            | -                | -                | -         |    -1.16 | akiyanora, amore, ayaka, Margo, meo |
|            1 |     4120 | 2024-02-18 | dream catchers fe | W   | 0.085      | 0.143        | 0.016 (0.000)    | 0.172 (0.002)    | 0 (0.000) |     1.53 | akiyanora, amore, ayaka, Margo, meo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,481.08)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.825 | $300.00        | $247.54         |
| 2024-05-26 |      0.738 | $750.00        | $553.77         |
| 2024-05-05 |      0.598 | $250.00        | $149.38         |
| 2024-04-21 |      0.505 | $1,050.00      | $530.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
