### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  856.3<br />
<br />
Final Rank Value (856.3) = Starting Rank Value (818.0) + Head To Head Adjustments (38.3)<br />

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
|           20 |     1552 | 2024-06-01 | panelinha         | L   | 0.776      | -            | -                | -                | -         |   -12.23 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1583 | 2024-05-31 | TSM Shimmer       | W   | 0.771      | 0.524        | 0.020 (0.008)    | 0.199 (0.080)    | 1 (0.771) |     7.59 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1591 | 2024-05-31 | Let Her Cook      | L   | 0.769      | -            | -                | -                | -         |   -10.70 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1907 | 2024-05-19 | Imperial fe       | W   | 0.688      | 0.281        | 0.128 (0.025)    | 0.299 (0.058)    | 0 (0.000) |    15.96 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1914 | 2024-05-19 | BIG EQUIPA        | W   | 0.687      | 0.281        | 0.017 (0.003)    | 0.151 (0.029)    | 0 (0.000) |     8.83 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1942 | 2024-05-18 | Spirit fe         | W   | 0.681      | 0.281        | 0.005 (0.001)    | 0.141 (0.027)    | 0 (0.000) |     5.17 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2676 | 2024-04-19 | Crescent fe       | W   | 0.489      | 0.331        | 0.005 (0.001)    | 0.078 (0.013)    | 0 (0.000) |     3.87 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2804 | 2024-04-16 | Imperial fe       | W   | 0.469      | 0.303        | 0.128 (0.018)    | 0.299 (0.042)    | 0 (0.000) |    11.39 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2826 | 2024-04-15 | NIP Impact        | W   | 0.462      | 0.303        | 0.005 (0.001)    | 0.229 (0.032)    | 0 (0.000) |     5.44 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2843 | 2024-04-14 | Astralis W        | W   | 0.454      | -            | -                | -                | 0 (0.000) |     3.44 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2857 | 2024-04-13 | Imperial fe       | L   | 0.448      | -            | -                | -                | -         |    -3.13 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2898 | 2024-04-11 | Spirit fe         | W   | 0.434      | 0.303        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.91 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     2998 | 2024-04-09 | NIP Impact        | L   | 0.421      | -            | -                | -                | -         |    -8.51 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3124 | 2024-04-04 | Spirit fe         | W   | 0.389      | 0.331        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.58 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3164 | 2024-04-03 | Let Her Cook      | L   | 0.382      | -            | -                | -                | -         |    -4.39 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3536 | 2024-03-14 | 1WIN Gang         | W   | 0.249      | -            | -                | -                | -         |     2.18 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3741 | 2024-03-06 | Fearless Cheetahs | W   | 0.196      | -            | -                | -                | -         |     1.92 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3961 | 2024-02-25 | BIG EQUIPA        | W   | 0.128      | 0.238        | 0.017 (0.001)    | 0.151 (0.005)    | -         |     1.74 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     3966 | 2024-02-25 | ENCE Athena       | W   | 0.127      | -            | -                | -                | -         |     1.08 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     3995 | 2024-02-24 | Crescent fe       | W   | 0.121      | -            | -                | -                | -         |     1.14 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,577.86)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.783 | $7,000.00      | $5,481.39       |
| 2024-05-19 |      0.688 | $2,000.00      | $1,375.74       |
| 2024-04-16 |      0.469 | $3,500.00      | $1,640.14       |
| 2024-02-25 |      0.128 | $630.00        | $80.59          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
