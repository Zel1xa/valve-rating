### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1238.4<br />
<br />
Final Rank Value (1238.4) = Starting Rank Value (1302.8) + Head To Head Adjustments (-64.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.626[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1302.8
- 400 + ( ( 0.440 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1302.8


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
|           52 |        7 | 2024-08-05 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           51 |       15 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.33 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       32 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.508 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    23.57 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       64 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      113 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.316 (0.045)    | -                | -         |    13.03 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      204 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.31 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      544 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.458 (0.153)    | -         |     2.99 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      564 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.13 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      579 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.67 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      640 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.533 (0.178)    | -         |     5.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      648 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.51 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      763 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.13 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      811 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.514 (0.190)    | -         |     3.96 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      859 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.80 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      896 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.983 (0.352)    | -         |    13.77 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      897 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.514 (0.184)    | -         |     3.66 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      919 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.533 (0.197)    | -         |     4.83 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      921 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.43 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      944 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.55 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      952 | 2024-07-05 | kONO            | W   | 0.991      | 0.333        | 0.028 (0.009)    | 0.566 (0.187)    | -         |     3.19 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      962 | 2024-06-30 | Young Gods      | W   | 0.959      | -            | -                | -                | -         |     1.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      984 | 2024-06-27 | Revenant        | W   | 0.937      | 0.333        | 0.027 (0.009)    | -                | -         |     2.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      988 | 2024-06-25 | Revenant        | W   | 0.925      | 0.333        | 0.027 (0.008)    | -                | -         |     2.41 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      995 | 2024-06-23 | los kogutos     | W   | 0.911      | -            | -                | -                | -         |     0.25 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1062 | 2024-06-15 | Lilmix          | W   | 0.859      | -            | -                | -                | 1 (0.859) |     2.96 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1104 | 2024-06-14 | Lilmix          | W   | 0.852      | -            | -                | -                | 1 (0.852) |     2.90 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1146 | 2024-06-13 | Kappa Bar       | W   | 0.844      | -            | -                | -                | 1 (0.844) |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1248 | 2024-06-09 | Alliance        | W   | 0.819      | -            | -                | -                | 1 (0.819) |     2.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1283 | 2024-06-09 | Preasy          | W   | 0.817      | -            | -                | -                | 1 (0.817) |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1558 | 2024-06-04 | Enterprise      | L   | 0.784      | -            | -                | -                | -         |   -21.14 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1576 | 2024-06-03 | brazylijski luz | W   | 0.779      | -            | -                | -                | -         |     2.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1578 | 2024-06-03 | Zero Tenacity   | W   | 0.778      | 0.371        | 0.143 (0.041)    | 1.000 (0.288)    | -         |     8.24 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1668 | 2024-05-31 | UNiTY           | L   | 0.757      | -            | -                | -                | -         |   -20.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1773 | 2024-05-26 | Preasy          | W   | 0.725      | -            | -                | -                | -         |     1.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1877 | 2024-05-22 | Permitta        | W   | 0.697      | 0.371        | -                | 0.902 (0.233)    | -         |     2.41 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2185 | 2024-05-14 | kONO            | L   | 0.644      | -            | -                | -                | -         |   -18.68 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2201 | 2024-05-13 | UNiTY           | W   | 0.638      | -            | -                | -                | -         |     2.81 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2206 | 2024-05-13 | ECLOT           | W   | 0.637      | 0.333        | 0.062 (0.013)    | -                | -         |     7.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2217 | 2024-05-12 | Verdant         | W   | 0.633      | -            | -                | -                | -         |     2.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2230 | 2024-05-12 | Preasy          | L   | 0.631      | -            | -                | -                | -         |   -18.82 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2247 | 2024-05-11 | Lilmix          | W   | 0.626      | -            | -                | -                | 1 (0.626) |     1.76 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2262 | 2024-05-11 | Flying Angels   | W   | 0.624      | -            | -                | -                | 1 (0.624) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2278 | 2024-05-10 | FAVBET          | W   | 0.617      | -            | -                | -                | -         |     1.10 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2804 | 2024-04-18 | UNiTY           | W   | 0.471      | -            | -                | -                | -         |     2.07 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2868 | 2024-04-16 | Viperio         | W   | 0.458      | -            | -                | -                | -         |     0.36 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3114 | 2024-04-07 | Alliance        | W   | 0.399      | -            | -                | -                | -         |     1.02 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3122 | 2024-04-07 | Metizport       | L   | 0.398      | -            | -                | -                | -         |   -11.39 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3132 | 2024-04-06 | JANO            | W   | 0.392      | -            | -                | -                | -         |     0.37 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3731 | 2024-03-09 | Alliance        | L   | 0.205      | -            | -                | -                | -         |    -5.97 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3835 | 2024-03-05 | B8              | L   | 0.180      | -            | -                | -                | -         |    -4.40 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3840 | 2024-03-05 | Insilio         | W   | 0.180      | -            | -                | -                | -         |     0.52 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3846 | 2024-03-05 | Sashi           | W   | 0.180      | -            | -                | -                | -         |     1.64 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,268.93)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.959 | $662.00        | $635.06         |
| 2024-06-27 |      0.937 | $5,000.00      | $4,685.42       |
| 2024-06-15 |      0.859 | $11,615.00     | $9,974.92       |
| 2024-06-09 |      0.819 | $7,224.00      | $5,916.66       |
| 2024-06-06 |      0.797 | $1,000.00      | $797.08         |
| 2024-05-13 |      0.637 | $6,000.00      | $3,822.50       |
| 2024-05-11 |      0.626 | $4,170.00      | $2,611.46       |
| 2024-04-18 |      0.471 | $6,000.00      | $2,825.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
