### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, meo, Mileyyy, unknxwn<br />
Global Rank: [188](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [120]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  615.4<br />
<br />
Final Rank Value (615.4) = Starting Rank Value (638.2) + Head To Head Adjustments (-22.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 638.2
- 400 + ( ( 0.122 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 638.2


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
|           16 |       41 | 2024-09-05 | Permitta W        | L   | 1.000      | -            | -                | -                | -         |   -16.57 | akiyanora, amore, meo, Mileyyy, unknxwn |
|           15 |      232 | 2024-08-29 | BIG EQUIPA        | L   | 1.000      | -            | -                | -                | -         |   -12.70 | akiyanora, amore, meo, Mileyyy, unknxwn |
|           14 |     1083 | 2024-08-06 | ENCE Athena       | W   | 0.989      | 0.143        | 0.001 (0.000)    | 0.049 (0.007)    | 0 (0.000) |    13.60 | akiyanora, amore, ayaka, Margo, meo     |
|           13 |     2415 | 2024-06-08 | NOFEAR5           | L   | 0.596      | -            | -                | -                | -         |    -9.03 | akiyanora, amore, ayaka, Margo, meo     |
|           12 |     2437 | 2024-06-08 | ENCE Athena       | W   | 0.595      | 0.270        | 0.001 (0.000)    | 0.049 (0.008)    | 0 (0.000) |     8.61 | akiyanora, amore, ayaka, Margo, meo     |
|           11 |     2874 | 2024-05-26 | NIP Impact        | W   | 0.509      | 0.250        | 0.004 (0.000)    | 0.215 (0.027)    | 0 (0.000) |     9.26 | akiyanora, amore, ayaka, Margo, meo     |
|           10 |     3100 | 2024-05-18 | Imperial fe       | L   | 0.455      | -            | -                | -                | -         |    -2.24 | akiyanora, amore, ayaka, Margo, meo     |
|            9 |     3482 | 2024-05-05 | Imperial fe       | L   | 0.368      | -            | -                | -                | -         |    -1.85 | akiyanora, amore, ayaka, Margo, meo     |
|            8 |     3843 | 2024-04-19 | NAVI Javelins     | L   | 0.263      | -            | -                | -                | -         |    -2.62 | akiyanora, amore, ayaka, Margo, meo     |
|            7 |     4057 | 2024-04-11 | Fearless Cheetahs | L   | 0.209      | -            | -                | -                | -         |    -3.39 | akiyanora, amore, ayaka, Margo, meo     |
|            6 |     4110 | 2024-04-10 | Permitta W        | L   | 0.202      | -            | -                | -                | -         |    -4.46 | akiyanora, amore, ayaka, Margo, meo     |
|            5 |     4193 | 2024-04-08 | Imperial fe       | L   | 0.188      | -            | -                | -                | -         |    -1.02 | akiyanora, amore, ayaka, Margo, meo     |
|            4 |     4428 | 2024-03-28 | 1WIN Gang         | W   | 0.116      | 0.331        | 0.001 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.25 | akiyanora, amore, ayaka, Margo, meo     |
|            3 |     4580 | 2024-03-20 | Spirit fe         | L   | 0.063      | -            | -                | -                | -         |    -0.96 | akiyanora, amore, ayaka, Margo, meo     |
|            2 |     4734 | 2024-03-13 | Let Her Cook      | L   | 0.016      | -            | -                | -                | -         |    -0.35 | akiyanora, amore, ayaka, Margo, meo     |
|            1 |     4735 | 2024-03-13 | Let Her Cook      | L   | 0.016      | -            | -                | -                | -         |    -0.35 | akiyanora, amore, ayaka, Margo, meo     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($942.21)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.596 | $300.00        | $178.75         |
| 2024-05-26 |      0.509 | $750.00        | $381.79         |
| 2024-05-05 |      0.368 | $250.00        | $92.05          |
| 2024-04-21 |      0.276 | $1,050.00      | $289.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
