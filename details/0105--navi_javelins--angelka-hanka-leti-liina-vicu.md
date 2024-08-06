### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.4<br />
<br />
Final Rank Value (855.4) = Starting Rank Value (818.2) + Head To Head Adjustments (37.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.087[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 818.2
- 400 + ( ( 0.203 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 818.2


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
|           20 |     1634 | 2024-06-01 | panelinha         | L   | 0.761      | -            | -                | -                | -         |   -11.97 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1665 | 2024-05-31 | TSM Shimmer       | W   | 0.756      | 0.524        | 0.020 (0.008)    | 0.191 (0.075)    | 1 (0.756) |     7.50 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1673 | 2024-05-31 | Let Her Cook      | L   | 0.754      | -            | -                | -                | -         |   -10.41 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1989 | 2024-05-19 | Imperial fe       | W   | 0.673      | 0.281        | 0.128 (0.024)    | 0.287 (0.054)    | 0 (0.000) |    15.64 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1996 | 2024-05-19 | BIG EQUIPA        | W   | 0.672      | 0.281        | 0.017 (0.003)    | 0.142 (0.027)    | 0 (0.000) |     8.65 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     2024 | 2024-05-18 | Spirit fe         | W   | 0.666      | 0.281        | 0.005 (0.001)    | 0.136 (0.025)    | 0 (0.000) |     5.12 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2758 | 2024-04-19 | Crescent fe       | W   | 0.474      | 0.331        | 0.004 (0.001)    | 0.081 (0.013)    | 0 (0.000) |     3.82 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2886 | 2024-04-16 | Imperial fe       | W   | 0.453      | 0.303        | 0.128 (0.018)    | 0.287 (0.039)    | 0 (0.000) |    11.02 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2908 | 2024-04-15 | NIP Impact        | W   | 0.447      | 0.303        | 0.005 (0.001)    | 0.219 (0.030)    | 0 (0.000) |     5.31 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2925 | 2024-04-14 | Astralis W        | W   | 0.439      | -            | -                | -                | 0 (0.000) |     3.33 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2939 | 2024-04-13 | Imperial fe       | L   | 0.433      | -            | -                | -                | -         |    -3.02 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2980 | 2024-04-11 | Spirit fe         | W   | 0.419      | 0.303        | 0.005 (0.001)    | 0.136 (0.017)    | 0 (0.000) |     3.80 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3080 | 2024-04-09 | NIP Impact        | L   | 0.406      | -            | -                | -                | -         |    -8.15 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3206 | 2024-04-04 | Spirit fe         | W   | 0.374      | 0.331        | 0.005 (0.001)    | 0.136 (0.017)    | 0 (0.000) |     3.46 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3246 | 2024-04-03 | Let Her Cook      | L   | 0.367      | -            | -                | -                | -         |    -4.20 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3618 | 2024-03-14 | 1WIN Gang         | W   | 0.234      | -            | -                | -                | -         |     2.06 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3823 | 2024-03-06 | Fearless Cheetahs | W   | 0.181      | -            | -                | -                | -         |     1.78 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4043 | 2024-02-25 | BIG EQUIPA        | W   | 0.113      | 0.238        | 0.017 (0.000)    | 0.142 (0.004)    | -         |     1.53 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4048 | 2024-02-25 | ENCE Athena       | W   | 0.112      | -            | -                | -                | -         |     0.95 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4077 | 2024-02-24 | Crescent fe       | W   | 0.106      | -            | -                | -                | -         |     1.00 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,379.08)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.768 | $7,000.00      | $5,375.42       |
| 2024-05-19 |      0.673 | $2,000.00      | $1,345.46       |
| 2024-04-16 |      0.453 | $3,500.00      | $1,587.15       |
| 2024-02-25 |      0.113 | $630.00        | $71.05          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
