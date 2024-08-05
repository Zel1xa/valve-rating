### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.4<br />
<br />
Final Rank Value (855.4) = Starting Rank Value (817.6) + Head To Head Adjustments (37.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 817.6
- 400 + ( ( 0.204 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 817.6


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
|           20 |     1601 | 2024-06-01 | panelinha         | L   | 0.769      | -            | -                | -                | -         |   -12.11 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1632 | 2024-05-31 | TSM Shimmer       | W   | 0.763      | 0.524        | 0.020 (0.008)    | 0.198 (0.079)    | 1 (0.763) |     7.55 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1640 | 2024-05-31 | Let Her Cook      | L   | 0.761      | -            | -                | -                | -         |   -10.56 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1956 | 2024-05-19 | Imperial fe       | W   | 0.680      | 0.281        | 0.128 (0.025)    | 0.298 (0.057)    | 0 (0.000) |    15.80 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1963 | 2024-05-19 | BIG EQUIPA        | W   | 0.679      | 0.281        | 0.017 (0.003)    | 0.149 (0.028)    | 0 (0.000) |     8.74 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1991 | 2024-05-18 | Spirit fe         | W   | 0.673      | 0.281        | 0.005 (0.001)    | 0.140 (0.027)    | 0 (0.000) |     5.14 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2725 | 2024-04-19 | Crescent fe       | W   | 0.481      | 0.331        | 0.005 (0.001)    | 0.077 (0.012)    | 0 (0.000) |     3.83 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2853 | 2024-04-16 | Imperial fe       | W   | 0.461      | 0.303        | 0.128 (0.018)    | 0.298 (0.042)    | 0 (0.000) |    11.20 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2875 | 2024-04-15 | NIP Impact        | W   | 0.454      | 0.303        | 0.005 (0.001)    | 0.228 (0.031)    | 0 (0.000) |     5.40 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2892 | 2024-04-14 | Astralis W        | W   | 0.447      | -            | -                | -                | 0 (0.000) |     3.38 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2906 | 2024-04-13 | Imperial fe       | L   | 0.440      | -            | -                | -                | -         |    -3.08 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2947 | 2024-04-11 | Spirit fe         | W   | 0.427      | 0.303        | 0.005 (0.001)    | 0.140 (0.018)    | 0 (0.000) |     3.85 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3047 | 2024-04-09 | NIP Impact        | L   | 0.414      | -            | -                | -                | -         |    -8.31 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3173 | 2024-04-04 | Spirit fe         | W   | 0.381      | 0.331        | 0.005 (0.001)    | 0.140 (0.018)    | 0 (0.000) |     3.52 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3213 | 2024-04-03 | Let Her Cook      | L   | 0.375      | -            | -                | -                | -         |    -4.30 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3585 | 2024-03-14 | 1WIN Gang         | W   | 0.242      | -            | -                | -                | -         |     2.13 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3790 | 2024-03-06 | Fearless Cheetahs | W   | 0.188      | -            | -                | -                | -         |     1.85 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4010 | 2024-02-25 | BIG EQUIPA        | W   | 0.120      | 0.238        | 0.017 (0.000)    | 0.149 (0.004)    | -         |     1.64 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4015 | 2024-02-25 | ENCE Athena       | W   | 0.119      | -            | -                | -                | -         |     1.01 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4044 | 2024-02-24 | Crescent fe       | W   | 0.114      | -            | -                | -                | -         |     1.07 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,479.38)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.776 | $7,000.00      | $5,428.89       |
| 2024-05-19 |      0.680 | $2,000.00      | $1,360.74       |
| 2024-04-16 |      0.461 | $3,500.00      | $1,613.89       |
| 2024-02-25 |      0.120 | $630.00        | $75.86          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
