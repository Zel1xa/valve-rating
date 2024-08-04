### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.2<br />
<br />
Final Rank Value (856.2) = Starting Rank Value (818.0) + Head To Head Adjustments (38.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 818.0
- 400 + ( ( 0.204 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 818.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1560 | 2024-06-01 | panelinha         | L   | 0.775      | -            | -                | -                | -         |   -12.22 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1591 | 2024-05-31 | TSM Shimmer       | W   | 0.770      | 0.524        | 0.020 (0.008)    | 0.199 (0.080)    | 1 (0.770) |     7.59 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1599 | 2024-05-31 | Let Her Cook      | L   | 0.768      | -            | -                | -                | -         |   -10.69 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1915 | 2024-05-19 | Imperial fe       | W   | 0.687      | 0.281        | 0.128 (0.025)    | 0.299 (0.058)    | 0 (0.000) |    15.95 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1922 | 2024-05-19 | BIG EQUIPA        | W   | 0.686      | 0.281        | 0.017 (0.003)    | 0.151 (0.029)    | 0 (0.000) |     8.82 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1950 | 2024-05-18 | Spirit fe         | W   | 0.680      | 0.281        | 0.005 (0.001)    | 0.141 (0.027)    | 0 (0.000) |     5.17 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2684 | 2024-04-19 | Crescent fe       | W   | 0.488      | 0.331        | 0.005 (0.001)    | 0.078 (0.013)    | 0 (0.000) |     3.87 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2812 | 2024-04-16 | Imperial fe       | W   | 0.468      | 0.303        | 0.128 (0.018)    | 0.299 (0.042)    | 0 (0.000) |    11.37 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2834 | 2024-04-15 | NIP Impact        | W   | 0.461      | 0.303        | 0.005 (0.001)    | 0.228 (0.032)    | 0 (0.000) |     5.43 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2851 | 2024-04-14 | Astralis W        | W   | 0.454      | -            | -                | -                | 0 (0.000) |     3.43 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2865 | 2024-04-13 | Imperial fe       | L   | 0.447      | -            | -                | -                | -         |    -3.12 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2906 | 2024-04-11 | Spirit fe         | W   | 0.434      | 0.303        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.90 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3006 | 2024-04-09 | NIP Impact        | L   | 0.420      | -            | -                | -                | -         |    -8.49 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3132 | 2024-04-04 | Spirit fe         | W   | 0.388      | 0.331        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.57 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3172 | 2024-04-03 | Let Her Cook      | L   | 0.381      | -            | -                | -                | -         |    -4.39 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3544 | 2024-03-14 | 1WIN Gang         | W   | 0.248      | -            | -                | -                | -         |     2.18 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3749 | 2024-03-06 | Fearless Cheetahs | W   | 0.195      | -            | -                | -                | -         |     1.92 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3969 | 2024-02-25 | BIG EQUIPA        | W   | 0.127      | 0.238        | 0.017 (0.001)    | 0.151 (0.005)    | -         |     1.73 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     3974 | 2024-02-25 | ENCE Athena       | W   | 0.126      | -            | -                | -                | -         |     1.07 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4003 | 2024-02-24 | Crescent fe       | W   | 0.120      | -            | -                | -                | -         |     1.13 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,568.43)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.782 | $7,000.00      | $5,476.37       |
| 2024-05-19 |      0.687 | $2,000.00      | $1,374.31       |
| 2024-04-16 |      0.468 | $3,500.00      | $1,637.63       |
| 2024-02-25 |      0.127 | $630.00        | $80.14          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
