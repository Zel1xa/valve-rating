### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.1<br />
<br />
Final Rank Value (856.1) = Starting Rank Value (817.9) + Head To Head Adjustments (38.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 817.9
- 400 + ( ( 0.204 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 817.9


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
|           20 |     1584 | 2024-06-01 | panelinha         | L   | 0.774      | -            | -                | -                | -         |   -12.21 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1615 | 2024-05-31 | TSM Shimmer       | W   | 0.769      | 0.524        | 0.020 (0.008)    | 0.199 (0.080)    | 1 (0.769) |     7.58 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1623 | 2024-05-31 | Let Her Cook      | L   | 0.767      | -            | -                | -                | -         |   -10.67 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1939 | 2024-05-19 | Imperial fe       | W   | 0.686      | 0.281        | 0.128 (0.025)    | 0.299 (0.058)    | 0 (0.000) |    15.93 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1946 | 2024-05-19 | BIG EQUIPA        | W   | 0.685      | 0.281        | 0.017 (0.003)    | 0.151 (0.029)    | 0 (0.000) |     8.81 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1974 | 2024-05-18 | Spirit fe         | W   | 0.679      | 0.281        | 0.005 (0.001)    | 0.141 (0.027)    | 0 (0.000) |     5.16 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2708 | 2024-04-19 | Crescent fe       | W   | 0.487      | 0.331        | 0.005 (0.001)    | 0.078 (0.013)    | 0 (0.000) |     3.86 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2836 | 2024-04-16 | Imperial fe       | W   | 0.467      | 0.303        | 0.128 (0.018)    | 0.299 (0.042)    | 0 (0.000) |    11.34 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2858 | 2024-04-15 | NIP Impact        | W   | 0.460      | 0.303        | 0.005 (0.001)    | 0.228 (0.032)    | 0 (0.000) |     5.47 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2875 | 2024-04-14 | Astralis W        | W   | 0.453      | -            | -                | -                | 0 (0.000) |     3.42 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2889 | 2024-04-13 | Imperial fe       | L   | 0.446      | -            | -                | -                | -         |    -3.11 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2930 | 2024-04-11 | Spirit fe         | W   | 0.433      | 0.303        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.89 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3030 | 2024-04-09 | NIP Impact        | L   | 0.419      | -            | -                | -                | -         |    -8.43 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3156 | 2024-04-04 | Spirit fe         | W   | 0.387      | 0.331        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.57 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3196 | 2024-04-03 | Let Her Cook      | L   | 0.380      | -            | -                | -                | -         |    -4.37 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3568 | 2024-03-14 | 1WIN Gang         | W   | 0.247      | -            | -                | -                | -         |     2.17 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3773 | 2024-03-06 | Fearless Cheetahs | W   | 0.194      | -            | -                | -                | -         |     1.91 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3993 | 2024-02-25 | BIG EQUIPA        | W   | 0.126      | 0.238        | 0.017 (0.001)    | 0.151 (0.005)    | -         |     1.72 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     3998 | 2024-02-25 | ENCE Athena       | W   | 0.125      | -            | -                | -                | -         |     1.06 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4027 | 2024-02-24 | Crescent fe       | W   | 0.119      | -            | -                | -                | -         |     1.12 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,554.45)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.781 | $7,000.00      | $5,468.91       |
| 2024-05-19 |      0.686 | $2,000.00      | $1,372.18       |
| 2024-04-16 |      0.467 | $3,500.00      | $1,633.90       |
| 2024-02-25 |      0.126 | $630.00        | $79.46          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
