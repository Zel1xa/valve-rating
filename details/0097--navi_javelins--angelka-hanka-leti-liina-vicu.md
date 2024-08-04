### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.7<br />
<br />
Final Rank Value (856.7) = Starting Rank Value (818.2) + Head To Head Adjustments (38.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 818.2
- 400 + ( ( 0.205 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 818.2


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
|           20 |     1548 | 2024-06-01 | panelinha         | L   | 0.779      | -            | -                | -                | -         |   -12.29 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1579 | 2024-05-31 | TSM Shimmer       | W   | 0.774      | 0.524        | 0.020 (0.008)    | 0.199 (0.081)    | 1 (0.774) |     7.61 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1587 | 2024-05-31 | Let Her Cook      | L   | 0.772      | -            | -                | -                | -         |   -10.81 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1903 | 2024-05-19 | Imperial fe       | W   | 0.691      | 0.281        | 0.128 (0.025)    | 0.299 (0.058)    | 0 (0.000) |    16.03 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1910 | 2024-05-19 | BIG EQUIPA        | W   | 0.690      | 0.281        | 0.017 (0.003)    | 0.152 (0.029)    | 0 (0.000) |     8.86 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1938 | 2024-05-18 | Spirit fe         | W   | 0.684      | 0.281        | 0.005 (0.001)    | 0.140 (0.027)    | 0 (0.000) |     5.17 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2671 | 2024-04-19 | Crescent fe       | W   | 0.492      | 0.331        | 0.005 (0.001)    | 0.078 (0.013)    | 0 (0.000) |     3.91 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2799 | 2024-04-16 | Imperial fe       | W   | 0.472      | 0.303        | 0.128 (0.018)    | 0.299 (0.043)    | 0 (0.000) |    11.46 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2821 | 2024-04-15 | NIP Impact        | W   | 0.465      | 0.303        | 0.005 (0.001)    | 0.229 (0.032)    | 0 (0.000) |     5.48 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2838 | 2024-04-14 | Astralis W        | W   | 0.458      | -            | -                | -                | 0 (0.000) |     3.46 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2852 | 2024-04-13 | Imperial fe       | L   | 0.451      | -            | -                | -                | -         |    -3.15 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2893 | 2024-04-11 | Spirit fe         | W   | 0.438      | 0.303        | 0.005 (0.001)    | 0.140 (0.019)    | 0 (0.000) |     3.93 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     2993 | 2024-04-09 | NIP Impact        | L   | 0.424      | -            | -                | -                | -         |    -8.57 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3119 | 2024-04-04 | Spirit fe         | W   | 0.392      | 0.331        | 0.005 (0.001)    | 0.140 (0.018)    | 0 (0.000) |     3.60 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3159 | 2024-04-03 | Let Her Cook      | L   | 0.385      | -            | -                | -                | -         |    -4.46 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3531 | 2024-03-14 | 1WIN Gang         | W   | 0.252      | -            | -                | -                | -         |     2.21 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3735 | 2024-03-06 | Fearless Cheetahs | W   | 0.199      | -            | -                | -                | -         |     1.95 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3955 | 2024-02-25 | BIG EQUIPA        | W   | 0.131      | 0.238        | 0.017 (0.001)    | 0.152 (0.005)    | -         |     1.78 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     3960 | 2024-02-25 | ENCE Athena       | W   | 0.130      | -            | -                | -                | -         |     1.10 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     3989 | 2024-02-24 | Crescent fe       | W   | 0.124      | -            | -                | -                | -         |     1.16 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,617.98)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.786 | $7,000.00      | $5,502.78       |
| 2024-05-19 |      0.691 | $2,000.00      | $1,381.85       |
| 2024-04-16 |      0.472 | $3,500.00      | $1,650.83       |
| 2024-02-25 |      0.131 | $630.00        | $82.51          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
