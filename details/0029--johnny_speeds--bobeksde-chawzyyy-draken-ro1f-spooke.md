### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1224.8<br />
<br />
Final Rank Value (1224.8) = Starting Rank Value (1295.0) + Head To Head Adjustments (-70.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.631[<sup>2</sup>](#table1)

The average of these factors is 0.437<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1295.0
- 400 + ( ( 0.437 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1295.0


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
|           48 |        4 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.62 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |       46 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.318 (0.045)    | -                | 0 (0.000) |    12.98 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      122 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.290 (0.041)    | -                | 0 (0.000) |    21.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      460 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.441 (0.147)    | -         |     2.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      480 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -25.97 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      494 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.70 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      556 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.553 (0.184)    | -         |     5.29 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      564 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.85 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      675 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.17 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      724 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.540 (0.200)    | -         |     4.08 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      768 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.92 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           37 |      804 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.998 (0.357)    | -         |    14.02 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      805 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.540 (0.193)    | -         |     3.78 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      827 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.553 (0.205)    | -         |     5.00 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           34 |      829 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.46 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      852 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.69 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      860 | 2024-07-05 | kONO            | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.555 (0.185)    | -         |     3.36 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           31 |      870 | 2024-06-30 | Young Gods      | W   | 0.973      | -            | -                | -                | -         |     1.46 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      894 | 2024-06-25 | Revenant        | W   | 0.938      | 0.333        | 0.027 (0.008)    | -                | -         |     2.46 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      900 | 2024-06-23 | los kogutos     | W   | 0.925      | -            | -                | -                | -         |     0.26 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |      958 | 2024-06-15 | Lilmix          | W   | 0.873      | 0.377        | 0.023 (0.008)    | -                | 1 (0.873) |     3.10 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |      992 | 2024-06-14 | Lilmix          | W   | 0.866      | 0.377        | 0.023 (0.007)    | -                | 1 (0.866) |     3.05 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1034 | 2024-06-13 | Kappa Bar       | W   | 0.858      | -            | -                | -                | 1 (0.858) |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1131 | 2024-06-09 | Alliance        | W   | 0.833      | -            | -                | -                | 1 (0.833) |     2.92 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1166 | 2024-06-09 | Preasy          | W   | 0.831      | -            | -                | -                | 1 (0.831) |     2.01 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1435 | 2024-06-04 | Enterprise      | L   | 0.798      | -            | -                | -                | -         |   -21.42 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1453 | 2024-06-03 | brazylijski luz | W   | 0.793      | -            | -                | -                | -         |     2.22 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1455 | 2024-06-03 | Zero Tenacity   | W   | 0.792      | 0.371        | 0.137 (0.040)    | 1.000 (0.293)    | -         |     8.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1543 | 2024-05-31 | UNiTY           | L   | 0.771      | -            | -                | -                | -         |   -20.64 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1647 | 2024-05-26 | Preasy          | W   | 0.738      | -            | -                | -                | -         |     1.61 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1751 | 2024-05-22 | Permitta        | W   | 0.711      | 0.371        | -                | 0.887 (0.234)    | -         |     2.43 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2058 | 2024-05-14 | kONO            | L   | 0.658      | -            | -                | -                | -         |   -19.01 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2074 | 2024-05-13 | UNiTY           | W   | 0.652      | -            | -                | -                | -         |     2.94 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2079 | 2024-05-13 | ECLOT           | W   | 0.651      | 0.333        | 0.063 (0.014)    | 0.578 (0.125)    | -         |     7.80 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2090 | 2024-05-12 | Verdant         | W   | 0.647      | -            | -                | -                | -         |     2.68 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2103 | 2024-05-12 | Preasy          | L   | 0.644      | -            | -                | -                | -         |   -19.14 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2120 | 2024-05-11 | Lilmix          | W   | 0.640      | -            | -                | -                | 1 (0.640) |     1.88 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2135 | 2024-05-11 | Flying Angels   | W   | 0.638      | -            | -                | -                | 1 (0.638) |     0.29 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2151 | 2024-05-10 | FAVBET          | W   | 0.631      | -            | -                | -                | -         |     1.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2675 | 2024-04-18 | UNiTY           | W   | 0.485      | -            | -                | -                | -         |     2.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2739 | 2024-04-16 | Viperio         | W   | 0.472      | -            | -                | -                | -         |     0.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     2985 | 2024-04-07 | Alliance        | W   | 0.413      | -            | -                | -                | -         |     1.11 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     2993 | 2024-04-07 | Metizport       | L   | 0.411      | -            | -                | -                | -         |   -11.31 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3003 | 2024-04-06 | JANO            | W   | 0.406      | -            | -                | -                | -         |     0.40 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3594 | 2024-03-09 | Alliance        | L   | 0.219      | -            | -                | -                | -         |    -6.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3698 | 2024-03-05 | B8              | L   | 0.194      | -            | -                | -                | -         |    -4.67 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3703 | 2024-03-05 | Insilio         | W   | 0.194      | -            | -                | -                | -         |     0.58 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3709 | 2024-03-05 | Sashi           | W   | 0.193      | -            | -                | -                | -         |     1.81 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,781.57)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.973 | $662.00        | $644.19         |
| 2024-06-25 |      0.938 | $5,000.00      | $4,692.13       |
| 2024-06-15 |      0.873 | $11,615.00     | $10,135.16      |
| 2024-06-09 |      0.833 | $7,224.00      | $6,016.32       |
| 2024-06-06 |      0.811 | $1,000.00      | $810.88         |
| 2024-05-13 |      0.651 | $6,000.00      | $3,905.28       |
| 2024-05-11 |      0.640 | $4,170.00      | $2,668.99       |
| 2024-04-18 |      0.485 | $6,000.00      | $2,908.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
