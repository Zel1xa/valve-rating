### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1219.9<br />
<br />
Final Rank Value (1219.9) = Starting Rank Value (1305.2) + Head To Head Adjustments (-85.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.203[<sup>2</sup>](#table1)
- LAN Wins: 0.652[<sup>2</sup>](#table1)

The average of these factors is 0.439<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1305.2
- 400 + ( ( 0.439 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1305.2


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
|           47 |       29 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    24.59 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      369 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.465 (0.155)    | 0 (0.000) |     2.98 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      389 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.07 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      404 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.61 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      465 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.487 (0.162)    | -         |     5.20 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      473 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.68 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      588 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.19 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      636 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.523 (0.194)    | -         |     3.98 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      684 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.23 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      721 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.185 (0.066)    | 0.973 (0.348)    | -         |    14.04 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      722 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.523 (0.187)    | -         |     3.67 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      744 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.487 (0.180)    | -         |     4.91 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      746 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.43 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      769 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.56 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      777 | 2024-07-05 | kONO            | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.537 (0.179)    | -         |     3.33 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      787 | 2024-06-30 | Young Gods      | W   | 0.992      | -            | -                | -                | -         |     1.46 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      809 | 2024-06-27 | Revenant        | W   | 0.970      | 0.333        | 0.027 (0.009)    | -                | -         |     2.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      813 | 2024-06-25 | Revenant        | W   | 0.957      | 0.333        | 0.027 (0.009)    | -                | -         |     2.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      820 | 2024-06-23 | los kogutos     | W   | 0.944      | -            | -                | -                | -         |     0.26 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |      887 | 2024-06-15 | Lilmix          | W   | 0.892      | 0.377        | 0.023 (0.008)    | -                | 1 (0.892) |     3.21 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |      929 | 2024-06-14 | Lilmix          | W   | 0.885      | 0.377        | 0.023 (0.008)    | -                | 1 (0.885) |     3.16 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |      971 | 2024-06-13 | Kappa Bar       | W   | 0.877      | -            | -                | -                | 1 (0.877) |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1073 | 2024-06-09 | Alliance        | W   | 0.852      | -            | -                | -                | 1 (0.852) |     2.92 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1108 | 2024-06-09 | Preasy          | W   | 0.850      | -            | -                | -                | 1 (0.850) |     2.02 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1383 | 2024-06-04 | Enterprise      | L   | 0.817      | -            | -                | -                | -         |   -21.98 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1401 | 2024-06-03 | brazylijski luz | W   | 0.812      | -            | -                | -                | -         |     2.26 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1403 | 2024-06-03 | Zero Tenacity   | W   | 0.811      | 0.371        | 0.138 (0.041)    | 1.000 (0.300)    | -         |     8.86 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1493 | 2024-05-31 | UNiTY           | L   | 0.790      | -            | -                | -                | -         |   -21.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1598 | 2024-05-26 | Preasy          | W   | 0.757      | -            | -                | -                | -         |     1.62 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1702 | 2024-05-22 | Permitta        | W   | 0.730      | 0.371        | -                | 0.799 (0.216)    | -         |     2.34 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2010 | 2024-05-14 | kONO            | L   | 0.677      | -            | -                | -                | -         |   -19.55 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2026 | 2024-05-13 | UNiTY           | W   | 0.671      | -            | -                | -                | -         |     2.99 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2031 | 2024-05-13 | ECLOT           | W   | 0.670      | 0.333        | 0.064 (0.014)    | 0.502 (0.112)    | -         |     5.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2042 | 2024-05-12 | Verdant         | W   | 0.666      | -            | -                | -                | -         |     2.72 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2055 | 2024-05-12 | Preasy          | L   | 0.664      | -            | -                | -                | -         |   -19.74 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2072 | 2024-05-11 | Lilmix          | W   | 0.659      | -            | -                | -                | 1 (0.659) |     1.94 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2087 | 2024-05-11 | Flying Angels   | W   | 0.657      | -            | -                | -                | 1 (0.657) |     0.29 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2103 | 2024-05-10 | FAVBET          | W   | 0.650      | -            | -                | -                | -         |     1.19 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2629 | 2024-04-18 | UNiTY           | W   | 0.504      | -            | -                | -                | -         |     2.22 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2693 | 2024-04-16 | Viperio         | W   | 0.491      | -            | -                | -                | -         |     0.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     2939 | 2024-04-07 | Alliance        | W   | 0.432      | -            | -                | -                | -         |     1.10 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     2947 | 2024-04-07 | Metizport       | L   | 0.430      | -            | -                | -                | -         |   -11.83 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     2957 | 2024-04-06 | JANO            | W   | 0.425      | -            | -                | -                | -         |     0.41 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3556 | 2024-03-09 | Alliance        | L   | 0.238      | -            | -                | -                | -         |    -6.93 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3660 | 2024-03-05 | B8              | L   | 0.213      | -            | -                | -                | -         |    -5.15 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3665 | 2024-03-05 | Insilio         | W   | 0.213      | -            | -                | -                | -         |     0.61 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3671 | 2024-03-05 | Sashi           | W   | 0.212      | -            | -                | -                | -         |     1.97 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,636.16)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.992 | $662.00        | $656.78         |
| 2024-06-27 |      0.970 | $5,000.00      | $4,849.47       |
| 2024-06-15 |      0.892 | $11,615.00     | $10,356.01      |
| 2024-06-09 |      0.852 | $7,224.00      | $6,153.68       |
| 2024-06-06 |      0.830 | $1,000.00      | $829.89         |
| 2024-05-13 |      0.670 | $6,000.00      | $4,019.36       |
| 2024-05-11 |      0.659 | $4,170.00      | $2,748.28       |
| 2024-04-18 |      0.504 | $6,000.00      | $3,022.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
