### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1263.7<br />
<br />
Final Rank Value (1263.7) = Starting Rank Value (1305.4) + Head To Head Adjustments (-41.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.624[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1305.4
- 400 + ( ( 0.440 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1305.4


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
|           54 |        9 | 2024-08-06 | BLEED           | W   | 1.000      | 0.143        | 0.125 (0.018)    | -                | 0 (0.000) |    17.48 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           53 |       12 | 2024-08-06 | Metizport       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.54 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           52 |       31 | 2024-08-05 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.83 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           51 |       39 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.21 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       56 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.510 (0.073)    | 1.000 (0.143)    | -         |    23.61 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       88 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | -         |     2.46 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      137 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.314 (0.045)    | -                | -         |    12.99 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      228 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.28 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      568 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.447 (0.149)    | -         |     3.01 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      588 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.10 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      603 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.64 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      664 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.523 (0.174)    | -         |     5.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      672 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.44 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      787 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.08 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      835 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.540 (0.200)    | -         |     4.03 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      883 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.85 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      920 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.958 (0.343)    | -         |    13.68 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      921 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.540 (0.193)    | -         |     3.74 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      943 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | -                | 0.523 (0.194)    | -         |     4.82 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      945 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.47 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      968 | 2024-07-07 | lajtbitexe      | W   | 0.999      | -            | -                | -                | -         |     1.52 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      976 | 2024-07-05 | kONO            | W   | 0.985      | 0.333        | 0.028 (0.009)    | 0.553 (0.182)    | -         |     3.17 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      986 | 2024-06-30 | Young Gods      | W   | 0.953      | -            | -                | -                | -         |     1.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |     1008 | 2024-06-27 | Revenant        | W   | 0.931      | 0.333        | 0.027 (0.009)    | -                | -         |     2.46 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |     1012 | 2024-06-25 | Revenant        | W   | 0.919      | -            | -                | -                | -         |     2.36 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |     1019 | 2024-06-23 | los kogutos     | W   | 0.905      | -            | -                | -                | -         |     0.24 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1086 | 2024-06-15 | Lilmix          | W   | 0.853      | -            | -                | -                | 1 (0.853) |     2.90 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1128 | 2024-06-14 | Lilmix          | W   | 0.846      | -            | -                | -                | 1 (0.846) |     2.85 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1170 | 2024-06-13 | Kappa Bar       | W   | 0.838      | -            | -                | -                | 1 (0.838) |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1272 | 2024-06-09 | Alliance        | W   | 0.813      | -            | -                | -                | 1 (0.813) |     2.71 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1307 | 2024-06-09 | Preasy          | W   | 0.811      | -            | -                | -                | 1 (0.811) |     0.55 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1582 | 2024-06-04 | Enterprise      | L   | 0.778      | -            | -                | -                | -         |   -21.00 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1600 | 2024-06-03 | brazylijski luz | W   | 0.773      | -            | -                | -                | -         |     2.04 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1602 | 2024-06-03 | Zero Tenacity   | W   | 0.772      | 0.371        | 0.143 (0.041)    | 1.000 (0.286)    | -         |     8.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1692 | 2024-05-31 | UNiTY           | L   | 0.751      | -            | -                | -                | -         |   -20.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1797 | 2024-05-26 | Preasy          | W   | 0.718      | -            | -                | -                | -         |     1.45 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1901 | 2024-05-22 | Permitta        | W   | 0.691      | 0.371        | 0.039 (0.010)    | 0.919 (0.235)    | -         |     2.48 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2209 | 2024-05-14 | kONO            | L   | 0.638      | -            | -                | -                | -         |   -18.50 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2225 | 2024-05-13 | UNiTY           | W   | 0.632      | -            | -                | -                | -         |     2.73 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2230 | 2024-05-13 | ECLOT           | W   | 0.631      | 0.333        | 0.061 (0.013)    | -                | -         |     7.38 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2241 | 2024-05-12 | Verdant         | W   | 0.627      | -            | -                | -                | -         |     2.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2254 | 2024-05-12 | Preasy          | L   | 0.625      | -            | -                | -                | -         |   -18.65 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2271 | 2024-05-11 | Lilmix          | W   | 0.620      | -            | -                | -                | 1 (0.620) |     1.72 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2286 | 2024-05-11 | Flying Angels   | W   | 0.618      | -            | -                | -                | 1 (0.618) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2302 | 2024-05-10 | FAVBET          | W   | 0.611      | -            | -                | -                | -         |     1.08 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2828 | 2024-04-18 | UNiTY           | W   | 0.465      | -            | -                | -                | -         |     2.00 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2892 | 2024-04-16 | Viperio         | W   | 0.452      | -            | -                | -                | -         |     0.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3138 | 2024-04-07 | Alliance        | W   | 0.393      | -            | -                | -                | -         |     0.99 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3146 | 2024-04-07 | Metizport       | L   | 0.392      | -            | -                | -                | -         |   -10.83 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3156 | 2024-04-06 | JANO            | W   | 0.386      | -            | -                | -                | -         |     0.36 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3755 | 2024-03-09 | Alliance        | L   | 0.199      | -            | -                | -                | -         |    -5.80 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3859 | 2024-03-05 | B8              | L   | 0.174      | -            | -                | -                | -         |    -4.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3864 | 2024-03-05 | Insilio         | W   | 0.174      | -            | -                | -                | -         |     0.50 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3870 | 2024-03-05 | Sashi           | W   | 0.173      | -            | -                | -                | -         |     1.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,014.28)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.953 | $662.00        | $631.01         |
| 2024-06-27 |      0.931 | $5,000.00      | $4,654.86       |
| 2024-06-15 |      0.853 | $11,615.00     | $9,903.94       |
| 2024-06-09 |      0.813 | $7,224.00      | $5,872.51       |
| 2024-06-06 |      0.791 | $1,000.00      | $790.97         |
| 2024-05-13 |      0.631 | $6,000.00      | $3,785.83       |
| 2024-05-11 |      0.620 | $4,170.00      | $2,585.98       |
| 2024-04-18 |      0.465 | $6,000.00      | $2,789.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
