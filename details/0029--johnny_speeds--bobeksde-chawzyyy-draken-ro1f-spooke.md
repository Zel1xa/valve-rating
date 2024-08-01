### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1218.7<br />
<br />
Final Rank Value (1218.7) = Starting Rank Value (1305.3) + Head To Head Adjustments (-86.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.524[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.650[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1305.3
- 400 + ( ( 0.440 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1305.3


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
|           47 |       58 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.292 (0.042)    | -                | 0 (0.000) |    20.83 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      401 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.504 (0.168)    | 0 (0.000) |     3.28 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      421 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -25.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      437 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.61 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      503 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.521 (0.174)    | -         |     5.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      511 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.92 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      628 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.16 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      681 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.555 (0.206)    | -         |     4.46 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      730 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.26 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      767 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.187 (0.067)    | 0.971 (0.347)    | -         |    13.68 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      768 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.555 (0.199)    | -         |     4.14 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      790 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.521 (0.193)    | -         |     5.78 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      792 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.43 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      816 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.56 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      824 | 2024-07-05 | kONO            | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.547 (0.182)    | -         |     3.50 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      834 | 2024-06-30 | Young Gods      | W   | 0.988      | -            | -                | -                | -         |     1.45 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      856 | 2024-06-27 | Revenant        | W   | 0.966      | 0.333        | 0.027 (0.009)    | -                | -         |     2.59 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      860 | 2024-06-25 | Revenant        | W   | 0.953      | 0.333        | 0.027 (0.009)    | -                | -         |     2.48 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      867 | 2024-06-23 | los kogutos     | W   | 0.940      | -            | -                | -                | -         |     0.26 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |      929 | 2024-06-15 | Lilmix          | W   | 0.887      | 0.377        | 0.023 (0.008)    | -                | 1 (0.887) |     3.19 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |      964 | 2024-06-14 | Lilmix          | W   | 0.880      | 0.377        | 0.023 (0.008)    | -                | 1 (0.880) |     3.14 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1006 | 2024-06-13 | Kappa Bar       | W   | 0.872      | -            | -                | -                | 1 (0.872) |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1110 | 2024-06-09 | Alliance        | W   | 0.848      | -            | -                | -                | 1 (0.848) |     2.93 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1146 | 2024-06-09 | Preasy          | W   | 0.846      | -            | -                | -                | 1 (0.846) |     2.02 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1434 | 2024-06-04 | Enterprise      | L   | 0.812      | -            | -                | -                | -         |   -21.94 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1452 | 2024-06-03 | brazylijski luz | W   | 0.807      | -            | -                | -                | -         |     2.46 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1454 | 2024-06-03 | Zero Tenacity   | W   | 0.806      | 0.371        | 0.139 (0.041)    | 1.000 (0.299)    | -         |     8.24 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1545 | 2024-05-31 | UNiTY           | L   | 0.786      | -            | -                | -                | -         |   -21.16 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1652 | 2024-05-26 | Preasy          | W   | 0.753      | -            | -                | -                | -         |     1.61 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1766 | 2024-05-22 | Permitta        | W   | 0.726      | 0.371        | -                | 0.801 (0.215)    | -         |     2.36 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2097 | 2024-05-14 | kONO            | L   | 0.672      | -            | -                | -                | -         |   -19.31 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2115 | 2024-05-13 | UNiTY           | W   | 0.667      | -            | -                | -                | -         |     2.87 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2120 | 2024-05-13 | ECLOT           | W   | 0.666      | 0.333        | 0.064 (0.014)    | 0.501 (0.111)    | -         |     5.70 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2131 | 2024-05-12 | Verdant         | W   | 0.662      | -            | -                | -                | -         |     2.76 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2144 | 2024-05-12 | Preasy          | L   | 0.659      | -            | -                | -                | -         |   -19.61 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2161 | 2024-05-11 | Lilmix          | W   | 0.655      | -            | -                | -                | 1 (0.655) |     1.91 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2176 | 2024-05-11 | Flying Angels   | W   | 0.653      | -            | -                | -                | 1 (0.653) |     0.28 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2192 | 2024-05-10 | FAVBET          | W   | 0.646      | -            | -                | -                | -         |     1.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2731 | 2024-04-18 | UNiTY           | W   | 0.499      | -            | -                | -                | -         |     2.12 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2797 | 2024-04-16 | Viperio         | W   | 0.487      | -            | -                | -                | -         |     0.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3044 | 2024-04-07 | Alliance        | W   | 0.428      | -            | -                | -                | -         |     1.10 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3052 | 2024-04-07 | Metizport       | L   | 0.426      | -            | -                | -                | -         |   -11.77 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3062 | 2024-04-06 | JANO            | W   | 0.420      | -            | -                | -                | -         |     0.41 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3680 | 2024-03-09 | Alliance        | L   | 0.234      | -            | -                | -                | -         |    -6.80 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3784 | 2024-03-05 | B8              | L   | 0.209      | -            | -                | -                | -         |    -5.04 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3793 | 2024-03-05 | Insilio         | W   | 0.208      | -            | -                | -                | -         |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3800 | 2024-03-05 | Sashi           | W   | 0.208      | -            | -                | -                | -         |     1.92 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,455.40)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.988 | $662.00        | $653.91         |
| 2024-06-27 |      0.966 | $5,000.00      | $4,827.78       |
| 2024-06-15 |      0.887 | $11,615.00     | $10,305.62      |
| 2024-06-09 |      0.848 | $7,224.00      | $6,122.34       |
| 2024-06-06 |      0.826 | $1,000.00      | $825.56         |
| 2024-05-13 |      0.666 | $6,000.00      | $3,993.33       |
| 2024-05-11 |      0.655 | $4,170.00      | $2,730.19       |
| 2024-04-18 |      0.499 | $6,000.00      | $2,996.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
