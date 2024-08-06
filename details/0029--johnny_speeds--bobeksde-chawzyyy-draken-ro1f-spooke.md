### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1238.3<br />
<br />
Final Rank Value (1238.3) = Starting Rank Value (1302.6) + Head To Head Adjustments (-64.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.625[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1302.6
- 400 + ( ( 0.440 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1302.6


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
|           52 |        9 | 2024-08-05 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           51 |       17 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.35 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       34 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.509 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    23.59 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       66 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      115 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.315 (0.045)    | -                | -         |    13.02 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      206 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.31 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      546 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.457 (0.152)    | -         |     2.99 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      566 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.13 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      581 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.66 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      642 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.533 (0.178)    | -         |     5.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      650 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.51 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      765 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.12 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      813 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.514 (0.190)    | -         |     3.96 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      861 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.80 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      898 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.982 (0.351)    | -         |    13.76 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      899 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.514 (0.184)    | -         |     3.66 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      921 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.533 (0.198)    | -         |     4.83 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      923 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.43 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      946 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.55 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      954 | 2024-07-05 | kONO            | W   | 0.990      | 0.333        | 0.028 (0.009)    | 0.566 (0.187)    | -         |     3.18 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      964 | 2024-06-30 | Young Gods      | W   | 0.958      | -            | -                | -                | -         |     1.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      986 | 2024-06-27 | Revenant        | W   | 0.935      | 0.333        | 0.027 (0.009)    | -                | -         |     2.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      990 | 2024-06-25 | Revenant        | W   | 0.923      | 0.333        | 0.027 (0.008)    | -                | -         |     2.40 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      997 | 2024-06-23 | los kogutos     | W   | 0.909      | -            | -                | -                | -         |     0.25 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1064 | 2024-06-15 | Lilmix          | W   | 0.857      | -            | -                | -                | 1 (0.857) |     2.95 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1106 | 2024-06-14 | Lilmix          | W   | 0.850      | -            | -                | -                | 1 (0.850) |     2.90 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1148 | 2024-06-13 | Kappa Bar       | W   | 0.842      | -            | -                | -                | 1 (0.842) |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1250 | 2024-06-09 | Alliance        | W   | 0.817      | -            | -                | -                | 1 (0.817) |     2.74 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1285 | 2024-06-09 | Preasy          | W   | 0.815      | -            | -                | -                | 1 (0.815) |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1560 | 2024-06-04 | Enterprise      | L   | 0.782      | -            | -                | -                | -         |   -21.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1578 | 2024-06-03 | brazylijski luz | W   | 0.777      | -            | -                | -                | -         |     2.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1580 | 2024-06-03 | Zero Tenacity   | W   | 0.776      | 0.371        | 0.143 (0.041)    | 1.000 (0.288)    | -         |     8.21 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1670 | 2024-05-31 | UNiTY           | L   | 0.755      | -            | -                | -                | -         |   -20.30 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1775 | 2024-05-26 | Preasy          | W   | 0.723      | -            | -                | -                | -         |     1.48 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1879 | 2024-05-22 | Permitta        | W   | 0.695      | 0.371        | -                | 0.901 (0.232)    | -         |     2.40 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2187 | 2024-05-14 | kONO            | L   | 0.642      | -            | -                | -                | -         |   -18.63 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2203 | 2024-05-13 | UNiTY           | W   | 0.637      | -            | -                | -                | -         |     2.80 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2208 | 2024-05-13 | ECLOT           | W   | 0.635      | 0.333        | 0.062 (0.013)    | -                | -         |     7.46 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2219 | 2024-05-12 | Verdant         | W   | 0.631      | -            | -                | -                | -         |     2.53 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2232 | 2024-05-12 | Preasy          | L   | 0.629      | -            | -                | -                | -         |   -18.77 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2249 | 2024-05-11 | Lilmix          | W   | 0.624      | -            | -                | -                | 1 (0.624) |     1.76 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2264 | 2024-05-11 | Flying Angels   | W   | 0.623      | -            | -                | -                | 1 (0.623) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2280 | 2024-05-10 | FAVBET          | W   | 0.615      | -            | -                | -                | -         |     1.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2806 | 2024-04-18 | UNiTY           | W   | 0.469      | -            | -                | -                | -         |     2.06 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2870 | 2024-04-16 | Viperio         | W   | 0.456      | -            | -                | -                | -         |     0.36 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3116 | 2024-04-07 | Alliance        | W   | 0.398      | -            | -                | -                | -         |     1.01 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3124 | 2024-04-07 | Metizport       | L   | 0.396      | -            | -                | -                | -         |   -11.34 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3134 | 2024-04-06 | JANO            | W   | 0.390      | -            | -                | -                | -         |     0.37 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3733 | 2024-03-09 | Alliance        | L   | 0.204      | -            | -                | -                | -         |    -5.92 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3837 | 2024-03-05 | B8              | L   | 0.178      | -            | -                | -                | -         |    -4.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3842 | 2024-03-05 | Insilio         | W   | 0.178      | -            | -                | -                | -         |     0.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3848 | 2024-03-05 | Sashi           | W   | 0.178      | -            | -                | -                | -         |     1.62 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,193.69)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.958 | $662.00        | $633.87         |
| 2024-06-27 |      0.935 | $5,000.00      | $4,676.39       |
| 2024-06-15 |      0.857 | $11,615.00     | $9,953.95       |
| 2024-06-09 |      0.817 | $7,224.00      | $5,903.61       |
| 2024-06-06 |      0.795 | $1,000.00      | $795.28         |
| 2024-05-13 |      0.635 | $6,000.00      | $3,811.67       |
| 2024-05-11 |      0.624 | $4,170.00      | $2,603.93       |
| 2024-04-18 |      0.469 | $6,000.00      | $2,815.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
