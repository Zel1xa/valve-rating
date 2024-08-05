### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1045.1<br />
<br />
Final Rank Value (1045.1) = Starting Rank Value (1009.7) + Head To Head Adjustments (35.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.405[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.224[<sup>2</sup>](#table1)

The average of these factors is 0.296<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1009.7
- 400 + ( ( 0.296 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1009.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     2156 | 2024-05-07 | FaZe              | L   | 0.633      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           34 |     2195 | 2024-05-05 | FURIA             | W   | 0.618      | 0.889        | 0.284 (0.156)    | 0.495 (0.272)    | 1 (0.618) |    18.87 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           33 |     2219 | 2024-05-04 | FORZE             | W   | 0.611      | 0.889        | 0.060 (0.032)    | 0.188 (0.102)    | 1 (0.611) |     7.86 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           32 |     2249 | 2024-05-02 | ENCE              | L   | 0.599      | -            | -                | -                | -         |    -1.85 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2272 | 2024-05-01 | Liquid            | L   | 0.593      | -            | -                | -                | -         |    -1.27 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2296 | 2024-04-30 | FORZE             | W   | 0.586      | 0.889        | 0.060 (0.031)    | 0.188 (0.098)    | 1 (0.586) |     7.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2551 | 2024-04-19 | OG                | L   | 0.513      | -            | -                | -                | -         |    -6.91 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2617 | 2024-04-18 | paiN              | L   | 0.505      | -            | -                | -                | -         |    -1.52 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2738 | 2024-04-13 | Rebels            | W   | 0.472      | 0.500        | 0.040 (0.010)    | 0.596 (0.141)    | 0 (0.000) |     7.27 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2752 | 2024-04-12 | Sangal            | W   | 0.465      | 0.500        | 0.219 (0.051)    | 0.824 (0.192)    | 0 (0.000) |     9.54 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     3046 | 2024-04-03 | Metizport         | L   | 0.406      | -            | -                | -                | -         |    -7.70 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     3056 | 2024-04-03 | Apeks             | W   | 0.405      | -            | -                | -                | 0 (0.000) |     5.00 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     3084 | 2024-04-02 | GamerLegion       | W   | 0.399      | 0.143        | 0.175 (0.010)    | 0.273 (0.016)    | 0 (0.000) |     8.62 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3093 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.398      | -            | -                | -                | -         |    -0.30 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3117 | 2024-03-31 | RUSH B            | L   | 0.385      | -            | -                | -                | -         |    -8.60 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3147 | 2024-03-28 | Betera            | L   | 0.366      | -            | -                | -                | -         |    -9.81 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3215 | 2024-03-26 | System5           | W   | 0.353      | 0.500        | -                | 0.086 (0.015)    | 0 (0.000) |     1.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3444 | 2024-03-13 | PERA              | W   | 0.266      | 0.500        | 0.048 (0.006)    | 0.452 (0.060)    | -         |     3.17 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3547 | 2024-03-09 | Metizport         | L   | 0.239      | -            | -                | -                | -         |    -4.79 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           16 |     3587 | 2024-03-07 | Imperial          | W   | 0.227      | 0.535        | 0.243 (0.029)    | 0.685 (0.083)    | -         |     5.93 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           15 |     3659 | 2024-03-05 | SAW               | L   | 0.213      | -            | -                | -                | -         |    -1.88 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3724 | 2024-03-03 | Gaimin Gladiators | L   | 0.197      | -            | -                | -                | -         |    -3.35 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           13 |     3729 | 2024-03-02 | 3DMAX             | L   | 0.193      | -            | -                | -                | -         |    -0.14 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           12 |     3772 | 2024-02-29 | PARIVISION        | W   | 0.178      | 0.500        | -                | 0.452 (0.040)    | -         |     3.42 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           11 |     3940 | 2024-02-21 | Astralis          | L   | 0.124      | -            | -                | -                | -         |    -0.08 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|           10 |     3970 | 2024-02-20 | Apeks             | L   | 0.117      | -            | -                | -                | -         |    -2.32 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            9 |     3985 | 2024-02-19 | Nexus             | W   | 0.113      | -            | -                | -                | 1 (0.113) |     0.97 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            8 |     3994 | 2024-02-19 | Gaimin Gladiators | L   | 0.111      | -            | -                | -                | -         |    -1.92 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            7 |     4004 | 2024-02-18 | Aurora            | W   | 0.106      | 0.143        | 0.429 (0.007)    | -                | -         |     3.28 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4010 | 2024-02-18 | SINNERS           | W   | 0.105      | -            | -                | -                | -         |     1.79 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            5 |     4035 | 2024-02-17 | Aurora            | W   | 0.099      | 0.143        | 0.429 (0.006)    | -                | -         |     3.04 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            4 |     4040 | 2024-02-17 | The Chosen Few    | W   | 0.098      | -            | -                | -                | -         |     0.41 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4240 | 2024-02-06 | G2                | L   | 0.024      | -            | -                | -                | -         |    -0.00 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4250 | 2024-02-05 | Cloud9            | W   | 0.018      | -            | -                | -                | 1 (0.018) |     0.32 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4272 | 2024-02-04 | GamerLegion       | L   | 0.011      | -            | -                | -                | -         |    -0.27 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,437.23)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.852 | $4,000.00      | $3,408.19       |
| 2024-05-12 |      0.665 | $17,500.00     | $11,640.50      |
| 2024-04-20 |      0.520 | $5,000.00      | $2,600.39       |
| 2024-03-10 |      0.246 | $7,500.00      | $1,847.64       |
| 2024-02-11 |      0.059 | $16,000.00     | $940.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
