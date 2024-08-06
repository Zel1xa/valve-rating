### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.3<br />
<br />
Final Rank Value (855.3) = Starting Rank Value (817.8) + Head To Head Adjustments (37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 817.8
- 400 + ( ( 0.204 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 817.8


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
|           20 |     1612 | 2024-06-01 | panelinha         | L   | 0.765      | -            | -                | -                | -         |   -12.05 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1643 | 2024-05-31 | TSM Shimmer       | W   | 0.760      | 0.524        | 0.020 (0.008)    | 0.195 (0.078)    | 1 (0.760) |     7.53 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1651 | 2024-05-31 | Let Her Cook      | L   | 0.758      | -            | -                | -                | -         |   -10.49 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1967 | 2024-05-19 | Imperial fe       | W   | 0.677      | 0.281        | 0.128 (0.024)    | 0.294 (0.056)    | 0 (0.000) |    15.73 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1974 | 2024-05-19 | BIG EQUIPA        | W   | 0.676      | 0.281        | 0.017 (0.003)    | 0.146 (0.028)    | 0 (0.000) |     8.70 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     2002 | 2024-05-18 | Spirit fe         | W   | 0.670      | 0.281        | 0.005 (0.001)    | 0.139 (0.026)    | 0 (0.000) |     5.13 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2736 | 2024-04-19 | Crescent fe       | W   | 0.478      | 0.331        | 0.005 (0.001)    | 0.076 (0.012)    | 0 (0.000) |     3.81 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2864 | 2024-04-16 | Imperial fe       | W   | 0.458      | 0.303        | 0.128 (0.018)    | 0.294 (0.041)    | 0 (0.000) |    11.13 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2886 | 2024-04-15 | NIP Impact        | W   | 0.451      | 0.303        | 0.005 (0.001)    | 0.225 (0.031)    | 0 (0.000) |     5.36 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2903 | 2024-04-14 | Astralis W        | W   | 0.444      | -            | -                | -                | 0 (0.000) |     3.36 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2917 | 2024-04-13 | Imperial fe       | L   | 0.437      | -            | -                | -                | -         |    -3.05 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2958 | 2024-04-11 | Spirit fe         | W   | 0.424      | 0.303        | 0.005 (0.001)    | 0.139 (0.018)    | 0 (0.000) |     3.83 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3058 | 2024-04-09 | NIP Impact        | L   | 0.410      | -            | -                | -                | -         |    -8.24 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3184 | 2024-04-04 | Spirit fe         | W   | 0.378      | 0.331        | 0.005 (0.001)    | 0.139 (0.017)    | 0 (0.000) |     3.50 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3224 | 2024-04-03 | Let Her Cook      | L   | 0.371      | -            | -                | -                | -         |    -4.26 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3596 | 2024-03-14 | 1WIN Gang         | W   | 0.238      | -            | -                | -                | -         |     2.10 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3801 | 2024-03-06 | Fearless Cheetahs | W   | 0.185      | -            | -                | -                | -         |     1.82 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4021 | 2024-02-25 | BIG EQUIPA        | W   | 0.117      | 0.238        | 0.017 (0.000)    | 0.146 (0.004)    | -         |     1.59 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4026 | 2024-02-25 | ENCE Athena       | W   | 0.116      | -            | -                | -                | -         |     0.99 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4055 | 2024-02-24 | Crescent fe       | W   | 0.110      | -            | -                | -                | -         |     1.04 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,435.61)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.772 | $7,000.00      | $5,405.56       |
| 2024-05-19 |      0.677 | $2,000.00      | $1,354.07       |
| 2024-04-16 |      0.458 | $3,500.00      | $1,602.22       |
| 2024-02-25 |      0.117 | $630.00        | $73.76          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
