### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1217.8<br />
<br />
Final Rank Value (1217.8) = Starting Rank Value (1304.0) + Head To Head Adjustments (-86.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.524[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.650[<sup>2</sup>](#table1)

The average of these factors is 0.439<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1304.0
- 400 + ( ( 0.439 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1304.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       65 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.292 (0.042)    | -                | 0 (0.000) |    20.88 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      407 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.504 (0.168)    | 0 (0.000) |     3.29 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      427 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -25.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      443 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.63 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      509 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.522 (0.174)    | -         |     5.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      517 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.91 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      634 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.16 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      687 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.555 (0.206)    | -         |     4.46 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      736 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.25 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      773 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.186 (0.067)    | 0.970 (0.347)    | -         |    13.73 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      774 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.555 (0.199)    | -         |     4.15 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      796 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.522 (0.193)    | -         |     5.79 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      798 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.42 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      822 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.57 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      830 | 2024-07-05 | kONO            | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.547 (0.182)    | -         |     3.50 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      840 | 2024-06-30 | Young Gods      | W   | 0.986      | -            | -                | -                | -         |     1.45 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      862 | 2024-06-27 | Revenant        | W   | 0.964      | 0.333        | 0.027 (0.009)    | -                | -         |     2.59 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      866 | 2024-06-25 | Revenant        | W   | 0.951      | 0.333        | 0.027 (0.009)    | -                | -         |     2.48 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      873 | 2024-06-23 | los kogutos     | W   | 0.938      | -            | -                | -                | -         |     0.26 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |      935 | 2024-06-15 | Lilmix          | W   | 0.886      | 0.377        | 0.023 (0.008)    | -                | 1 (0.886) |     3.19 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |      970 | 2024-06-14 | Lilmix          | W   | 0.879      | 0.377        | 0.023 (0.008)    | -                | 1 (0.879) |     3.14 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1012 | 2024-06-13 | Kappa Bar       | W   | 0.871      | -            | -                | -                | 1 (0.871) |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1116 | 2024-06-09 | Alliance        | W   | 0.846      | -            | -                | -                | 1 (0.846) |     2.93 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1152 | 2024-06-09 | Preasy          | W   | 0.844      | -            | -                | -                | 1 (0.844) |     2.02 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1440 | 2024-06-04 | Enterprise      | L   | 0.811      | -            | -                | -                | -         |   -21.89 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1458 | 2024-06-03 | brazylijski luz | W   | 0.806      | -            | -                | -                | -         |     2.47 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1460 | 2024-06-03 | Zero Tenacity   | W   | 0.805      | 0.371        | 0.139 (0.041)    | 1.000 (0.298)    | -         |     8.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1551 | 2024-05-31 | UNiTY           | L   | 0.784      | -            | -                | -                | -         |   -21.12 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1658 | 2024-05-26 | Preasy          | W   | 0.751      | -            | -                | -                | -         |     1.61 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1772 | 2024-05-22 | Permitta        | W   | 0.724      | 0.371        | -                | 0.801 (0.215)    | -         |     2.35 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2103 | 2024-05-14 | kONO            | L   | 0.671      | -            | -                | -                | -         |   -19.26 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2121 | 2024-05-13 | UNiTY           | W   | 0.665      | -            | -                | -                | -         |     2.87 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2126 | 2024-05-13 | ECLOT           | W   | 0.664      | 0.333        | 0.064 (0.014)    | 0.501 (0.111)    | -         |     5.68 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2137 | 2024-05-12 | Verdant         | W   | 0.660      | -            | -                | -                | -         |     2.76 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2150 | 2024-05-12 | Preasy          | L   | 0.657      | -            | -                | -                | -         |   -19.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2167 | 2024-05-11 | Lilmix          | W   | 0.653      | -            | -                | -                | 1 (0.653) |     1.91 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2182 | 2024-05-11 | Flying Angels   | W   | 0.651      | -            | -                | -                | 1 (0.651) |     0.28 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2198 | 2024-05-10 | FAVBET          | W   | 0.644      | -            | -                | -                | -         |     1.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2737 | 2024-04-18 | UNiTY           | W   | 0.498      | -            | -                | -                | -         |     2.12 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2803 | 2024-04-16 | Viperio         | W   | 0.485      | -            | -                | -                | -         |     0.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3050 | 2024-04-07 | Alliance        | W   | 0.426      | -            | -                | -                | -         |     1.10 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3058 | 2024-04-07 | Metizport       | L   | 0.424      | -            | -                | -                | -         |   -11.72 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3068 | 2024-04-06 | JANO            | W   | 0.419      | -            | -                | -                | -         |     0.41 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3686 | 2024-03-09 | Alliance        | L   | 0.232      | -            | -                | -                | -         |    -6.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3790 | 2024-03-05 | B8              | L   | 0.207      | -            | -                | -                | -         |    -5.00 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3799 | 2024-03-05 | Insilio         | W   | 0.207      | -            | -                | -                | -         |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3806 | 2024-03-05 | Sashi           | W   | 0.206      | -            | -                | -                | -         |     1.91 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,385.95)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.986 | $662.00        | $652.81         |
| 2024-06-27 |      0.964 | $5,000.00      | $4,819.44       |
| 2024-06-15 |      0.886 | $11,615.00     | $10,286.27      |
| 2024-06-09 |      0.846 | $7,224.00      | $6,110.30       |
| 2024-06-06 |      0.824 | $1,000.00      | $823.89         |
| 2024-05-13 |      0.664 | $6,000.00      | $3,983.33       |
| 2024-05-11 |      0.653 | $4,170.00      | $2,723.24       |
| 2024-04-18 |      0.498 | $6,000.00      | $2,986.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
