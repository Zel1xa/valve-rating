### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1228.8<br />
<br />
Final Rank Value (1228.8) = Starting Rank Value (1293.0) + Head To Head Adjustments (-64.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.387[<sup>2</sup>](#table1)
- Opponent Network: 0.208[<sup>2</sup>](#table1)
- LAN Wins: 0.630[<sup>2</sup>](#table1)

The average of these factors is 0.437<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1293.0
- 400 + ( ( 0.437 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1293.0


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
|           49 |        6 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.55 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |       54 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.318 (0.045)    | -                | 0 (0.000) |    12.81 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      144 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    24.41 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      483 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.465 (0.155)    | -         |     3.04 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      503 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.05 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      518 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.66 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      579 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.535 (0.178)    | -         |     5.22 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      587 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.59 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      702 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.15 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      750 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.522 (0.194)    | -         |     4.03 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      797 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.02 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      834 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.964 (0.345)    | -         |    13.91 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      835 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | -         |     3.74 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      857 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.535 (0.198)    | -         |     4.93 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      859 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.37 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      882 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.60 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      890 | 2024-07-05 | kONO            | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | -         |     3.34 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      900 | 2024-06-30 | Young Gods      | W   | 0.971      | -            | -                | -                | -         |     1.44 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      922 | 2024-06-27 | Revenant        | W   | 0.949      | 0.333        | 0.027 (0.009)    | -                | -         |     2.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      926 | 2024-06-25 | Revenant        | W   | 0.937      | 0.333        | 0.027 (0.008)    | -                | -         |     2.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      933 | 2024-06-23 | los kogutos     | W   | 0.923      | -            | -                | -                | -         |     0.26 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1000 | 2024-06-15 | Lilmix          | W   | 0.871      | 0.377        | 0.023 (0.008)    | -                | 1 (0.871) |     3.10 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1042 | 2024-06-14 | Lilmix          | W   | 0.864      | -            | -                | -                | 1 (0.864) |     3.05 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1084 | 2024-06-13 | Kappa Bar       | W   | 0.856      | -            | -                | -                | 1 (0.856) |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1186 | 2024-06-09 | Alliance        | W   | 0.831      | -            | -                | -                | 1 (0.831) |     2.91 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1221 | 2024-06-09 | Preasy          | W   | 0.829      | -            | -                | -                | 1 (0.829) |     2.01 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1496 | 2024-06-04 | Enterprise      | L   | 0.796      | -            | -                | -                | -         |   -21.38 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1514 | 2024-06-03 | brazylijski luz | W   | 0.791      | -            | -                | -                | -         |     2.22 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1516 | 2024-06-03 | Zero Tenacity   | W   | 0.790      | 0.371        | 0.137 (0.040)    | 1.000 (0.293)    | -         |     8.67 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1606 | 2024-05-31 | UNiTY           | L   | 0.769      | -            | -                | -                | -         |   -20.59 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1711 | 2024-05-26 | Preasy          | W   | 0.737      | -            | -                | -                | -         |     1.61 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1815 | 2024-05-22 | Permitta        | W   | 0.709      | 0.371        | -                | 0.876 (0.230)    | -         |     2.43 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2123 | 2024-05-14 | kONO            | L   | 0.656      | -            | -                | -                | -         |   -18.94 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2139 | 2024-05-13 | UNiTY           | W   | 0.651      | -            | -                | -                | -         |     2.94 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2144 | 2024-05-13 | ECLOT           | W   | 0.649      | 0.333        | 0.063 (0.014)    | 0.559 (0.121)    | -         |     7.77 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2155 | 2024-05-12 | Verdant         | W   | 0.645      | -            | -                | -                | -         |     2.69 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2168 | 2024-05-12 | Preasy          | L   | 0.643      | -            | -                | -                | -         |   -19.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2185 | 2024-05-11 | Lilmix          | W   | 0.638      | -            | -                | -                | 1 (0.638) |     1.88 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2200 | 2024-05-11 | Flying Angels   | W   | 0.636      | -            | -                | -                | 1 (0.636) |     0.29 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2216 | 2024-05-10 | FAVBET          | W   | 0.629      | -            | -                | -                | -         |     1.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2741 | 2024-04-18 | UNiTY           | W   | 0.483      | -            | -                | -                | -         |     2.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2805 | 2024-04-16 | Viperio         | W   | 0.470      | -            | -                | -                | -         |     0.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3051 | 2024-04-07 | Alliance        | W   | 0.411      | -            | -                | -                | -         |     1.10 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3059 | 2024-04-07 | Metizport       | L   | 0.410      | -            | -                | -                | -         |   -11.25 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3069 | 2024-04-06 | JANO            | W   | 0.404      | -            | -                | -                | -         |     0.40 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3667 | 2024-03-09 | Alliance        | L   | 0.217      | -            | -                | -                | -         |    -6.30 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3771 | 2024-03-05 | B8              | L   | 0.192      | -            | -                | -                | -         |    -4.64 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3776 | 2024-03-05 | Insilio         | W   | 0.192      | -            | -                | -                | -         |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3782 | 2024-03-05 | Sashi           | W   | 0.192      | -            | -                | -                | -         |     1.79 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,772.46)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.971 | $662.00        | $643.06         |
| 2024-06-27 |      0.949 | $5,000.00      | $4,745.83       |
| 2024-06-15 |      0.871 | $11,615.00     | $10,115.27      |
| 2024-06-09 |      0.831 | $7,224.00      | $6,003.95       |
| 2024-06-06 |      0.809 | $1,000.00      | $809.17         |
| 2024-05-13 |      0.649 | $6,000.00      | $3,895.00       |
| 2024-05-11 |      0.638 | $4,170.00      | $2,661.85       |
| 2024-04-18 |      0.483 | $6,000.00      | $2,898.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
