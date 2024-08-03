### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  858.0<br />
<br />
Final Rank Value (858.0) = Starting Rank Value (819.5) + Head To Head Adjustments (38.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 819.5
- 400 + ( ( 0.205 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 819.5


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
|           20 |     1486 | 2024-06-01 | panelinha         | L   | 0.781      | -            | -                | -                | -         |   -12.32 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1516 | 2024-05-31 | TSM Shimmer       | W   | 0.775      | 0.524        | 0.020 (0.008)    | 0.206 (0.084)    | 1 (0.775) |     7.61 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1524 | 2024-05-31 | Let Her Cook      | L   | 0.774      | -            | -                | -                | -         |   -10.84 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1838 | 2024-05-19 | Imperial fe       | W   | 0.693      | 0.281        | 0.129 (0.025)    | 0.310 (0.060)    | 0 (0.000) |    16.08 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1845 | 2024-05-19 | BIG EQUIPA        | W   | 0.692      | 0.281        | 0.017 (0.003)    | 0.157 (0.031)    | 0 (0.000) |     8.87 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1873 | 2024-05-18 | Spirit fe         | W   | 0.686      | 0.281        | 0.005 (0.001)    | 0.145 (0.028)    | 0 (0.000) |     5.17 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2605 | 2024-04-19 | Crescent fe       | W   | 0.494      | 0.331        | 0.005 (0.001)    | 0.081 (0.013)    | 0 (0.000) |     3.91 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2733 | 2024-04-16 | Imperial fe       | W   | 0.473      | 0.303        | 0.129 (0.018)    | 0.310 (0.044)    | 0 (0.000) |    11.51 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2755 | 2024-04-15 | NIP Impact        | W   | 0.467      | 0.303        | 0.005 (0.001)    | 0.236 (0.033)    | 0 (0.000) |     5.49 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2772 | 2024-04-14 | Astralis W        | W   | 0.459      | -            | -                | -                | 0 (0.000) |     3.46 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2786 | 2024-04-13 | Imperial fe       | L   | 0.453      | -            | -                | -                | -         |    -3.15 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2827 | 2024-04-11 | Spirit fe         | W   | 0.439      | 0.303        | 0.005 (0.001)    | 0.145 (0.019)    | 0 (0.000) |     3.93 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     2927 | 2024-04-09 | NIP Impact        | L   | 0.426      | -            | -                | -                | -         |    -8.61 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3053 | 2024-04-04 | Spirit fe         | W   | 0.394      | 0.331        | 0.005 (0.001)    | 0.145 (0.019)    | 0 (0.000) |     3.60 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3093 | 2024-04-03 | Let Her Cook      | L   | 0.387      | -            | -                | -                | -         |    -4.48 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3459 | 2024-03-14 | 1WIN Gang         | W   | 0.254      | -            | -                | -                | -         |     2.21 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3662 | 2024-03-06 | Fearless Cheetahs | W   | 0.200      | -            | -                | -                | -         |     1.96 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3882 | 2024-02-25 | BIG EQUIPA        | W   | 0.133      | 0.238        | 0.017 (0.001)    | 0.157 (0.005)    | -         |     1.80 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     3887 | 2024-02-25 | ENCE Athena       | W   | 0.132      | -            | -                | -                | -         |     1.11 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     3916 | 2024-02-24 | Crescent fe       | W   | 0.126      | -            | -                | -                | -         |     1.18 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,640.47)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.788 | $7,000.00      | $5,514.77       |
| 2024-05-19 |      0.693 | $2,000.00      | $1,385.28       |
| 2024-04-16 |      0.473 | $3,500.00      | $1,656.83       |
| 2024-02-25 |      0.133 | $630.00        | $83.59          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
