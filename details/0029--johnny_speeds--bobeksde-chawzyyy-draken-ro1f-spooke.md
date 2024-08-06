### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1239.1<br />
<br />
Final Rank Value (1239.1) = Starting Rank Value (1302.8) + Head To Head Adjustments (-63.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.624[<sup>2</sup>](#table1)

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
|           52 |       13 | 2024-08-05 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           51 |       21 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.34 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       38 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.509 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    23.61 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       70 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      119 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.315 (0.045)    | -                | -         |    13.00 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      210 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.29 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      550 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.457 (0.152)    | -         |     3.01 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      570 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.14 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      585 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.66 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      646 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.534 (0.178)    | -         |     5.10 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      654 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.50 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      769 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      817 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.513 (0.190)    | -         |     3.96 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      865 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.81 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      902 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.980 (0.351)    | -         |    13.73 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      903 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.513 (0.184)    | -         |     3.66 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      925 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.534 (0.198)    | -         |     4.82 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      927 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.44 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      950 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.54 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      958 | 2024-07-05 | kONO            | W   | 0.987      | 0.333        | 0.028 (0.009)    | 0.565 (0.186)    | -         |     3.21 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      968 | 2024-06-30 | Young Gods      | W   | 0.955      | -            | -                | -                | -         |     1.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      990 | 2024-06-27 | Revenant        | W   | 0.933      | 0.333        | 0.027 (0.009)    | -                | -         |     2.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      994 | 2024-06-25 | Revenant        | W   | 0.920      | 0.333        | 0.027 (0.008)    | -                | -         |     2.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |     1001 | 2024-06-23 | los kogutos     | W   | 0.907      | -            | -                | -                | -         |     0.24 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1068 | 2024-06-15 | Lilmix          | W   | 0.854      | -            | -                | -                | 1 (0.854) |     2.93 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1110 | 2024-06-14 | Lilmix          | W   | 0.847      | -            | -                | -                | 1 (0.847) |     2.88 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1152 | 2024-06-13 | Kappa Bar       | W   | 0.839      | -            | -                | -                | 1 (0.839) |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1254 | 2024-06-09 | Alliance        | W   | 0.815      | -            | -                | -                | 1 (0.815) |     2.73 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1289 | 2024-06-09 | Preasy          | W   | 0.813      | -            | -                | -                | 1 (0.813) |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1564 | 2024-06-04 | Enterprise      | L   | 0.779      | -            | -                | -                | -         |   -21.03 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1582 | 2024-06-03 | brazylijski luz | W   | 0.775      | -            | -                | -                | -         |     2.07 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1584 | 2024-06-03 | Zero Tenacity   | W   | 0.774      | 0.371        | 0.143 (0.041)    | 1.000 (0.287)    | -         |     8.26 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1674 | 2024-05-31 | UNiTY           | L   | 0.753      | -            | -                | -                | -         |   -20.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1779 | 2024-05-26 | Preasy          | W   | 0.720      | -            | -                | -                | -         |     1.47 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1883 | 2024-05-22 | Permitta        | W   | 0.693      | 0.371        | -                | 0.940 (0.241)    | -         |     2.40 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2191 | 2024-05-14 | kONO            | L   | 0.640      | -            | -                | -                | -         |   -18.53 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2207 | 2024-05-13 | UNiTY           | W   | 0.634      | -            | -                | -                | -         |     2.77 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2212 | 2024-05-13 | ECLOT           | W   | 0.633      | 0.333        | 0.061 (0.013)    | -                | -         |     7.41 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2223 | 2024-05-12 | Verdant         | W   | 0.629      | -            | -                | -                | -         |     2.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2236 | 2024-05-12 | Preasy          | L   | 0.626      | -            | -                | -                | -         |   -18.70 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2253 | 2024-05-11 | Lilmix          | W   | 0.622      | -            | -                | -                | 1 (0.622) |     1.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2268 | 2024-05-11 | Flying Angels   | W   | 0.620      | -            | -                | -                | 1 (0.620) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2284 | 2024-05-10 | FAVBET          | W   | 0.613      | -            | -                | -                | -         |     1.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2810 | 2024-04-18 | UNiTY           | W   | 0.467      | -            | -                | -                | -         |     2.03 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2874 | 2024-04-16 | Viperio         | W   | 0.454      | -            | -                | -                | -         |     0.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3120 | 2024-04-07 | Alliance        | W   | 0.395      | -            | -                | -                | -         |     1.00 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3128 | 2024-04-07 | Metizport       | L   | 0.393      | -            | -                | -                | -         |   -10.90 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3138 | 2024-04-06 | JANO            | W   | 0.388      | -            | -                | -                | -         |     0.37 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3737 | 2024-03-09 | Alliance        | L   | 0.201      | -            | -                | -                | -         |    -5.85 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3841 | 2024-03-05 | B8              | L   | 0.176      | -            | -                | -                | -         |    -4.30 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3846 | 2024-03-05 | Insilio         | W   | 0.176      | -            | -                | -                | -         |     0.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3852 | 2024-03-05 | Sashi           | W   | 0.175      | -            | -                | -                | -         |     1.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,089.51)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.955 | $662.00        | $632.21         |
| 2024-06-27 |      0.933 | $5,000.00      | $4,663.89       |
| 2024-06-15 |      0.854 | $11,615.00     | $9,924.91       |
| 2024-06-09 |      0.815 | $7,224.00      | $5,885.55       |
| 2024-06-06 |      0.793 | $1,000.00      | $792.78         |
| 2024-05-13 |      0.633 | $6,000.00      | $3,796.67       |
| 2024-05-11 |      0.622 | $4,170.00      | $2,593.51       |
| 2024-04-18 |      0.467 | $6,000.00      | $2,800.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
