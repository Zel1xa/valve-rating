### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [54](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1025.7<br />
<br />
Final Rank Value (1025.7) = Starting Rank Value (990.4) + Head To Head Adjustments (35.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.449[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.210[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 990.4
- 400 + ( ( 0.289 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 990.4


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
|           33 |     2273 | 2024-05-07 | FaZe              | L   | 0.609      | -            | -                | -                | -         |    -0.38 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           32 |     2312 | 2024-05-05 | FURIA             | W   | 0.595      | 0.889        | 0.284 (0.150)    | 0.491 (0.259)    | 1 (0.595) |    18.14 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2336 | 2024-05-04 | FORZE             | W   | 0.587      | 0.889        | 0.058 (0.030)    | 0.177 (0.093)    | 1 (0.587) |     7.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2366 | 2024-05-02 | ENCE              | L   | 0.575      | -            | -                | -                | -         |    -1.78 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2389 | 2024-05-01 | Liquid            | L   | 0.569      | -            | -                | -                | -         |    -1.01 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2413 | 2024-04-30 | FORZE             | W   | 0.562      | 0.889        | 0.058 (0.029)    | 0.177 (0.089)    | 1 (0.562) |     7.29 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2668 | 2024-04-19 | OG                | L   | 0.489      | -            | -                | -                | -         |    -6.60 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2734 | 2024-04-18 | paiN              | L   | 0.481      | -            | -                | -                | -         |    -1.44 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2855 | 2024-04-13 | Rebels            | W   | 0.448      | 0.500        | 0.038 (0.009)    | 0.599 (0.134)    | 0 (0.000) |     7.11 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2869 | 2024-04-12 | Sangal            | W   | 0.441      | 0.500        | 0.219 (0.048)    | 0.862 (0.190)    | 0 (0.000) |     9.50 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     3163 | 2024-04-03 | Metizport         | L   | 0.382      | -            | -                | -                | -         |    -7.09 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3173 | 2024-04-03 | Apeks             | W   | 0.381      | -            | -                | -                | 0 (0.000) |     4.68 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3201 | 2024-04-02 | GamerLegion       | W   | 0.375      | 0.143        | 0.174 (0.009)    | 0.271 (0.015)    | 0 (0.000) |     8.16 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3210 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.374      | -            | -                | -                | -         |    -0.23 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3234 | 2024-03-31 | RUSH B            | L   | 0.362      | -            | -                | -                | -         |    -7.80 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3264 | 2024-03-28 | Betera            | L   | 0.342      | -            | -                | -                | -         |    -9.06 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3332 | 2024-03-26 | System5           | W   | 0.329      | 0.500        | -                | 0.085 (0.014)    | 0 (0.000) |     1.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3561 | 2024-03-13 | PERA              | W   | 0.242      | 0.500        | 0.048 (0.006)    | 0.453 (0.055)    | 0 (0.000) |     3.02 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3664 | 2024-03-09 | Metizport         | L   | 0.215      | -            | -                | -                | -         |    -4.21 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           14 |     3704 | 2024-03-07 | Imperial          | W   | 0.203      | 0.535        | 0.237 (0.026)    | 0.685 (0.074)    | -         |     5.28 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3776 | 2024-03-05 | SAW               | L   | 0.189      | -            | -                | -                | -         |    -1.65 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           12 |     3841 | 2024-03-03 | Gaimin Gladiators | L   | 0.173      | -            | -                | -                | -         |    -2.95 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           11 |     3846 | 2024-03-02 | 3DMAX             | L   | 0.169      | -            | -                | -                | -         |    -0.12 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3889 | 2024-02-29 | PARIVISION        | W   | 0.154      | 0.500        | -                | 0.534 (0.041)    | -         |     3.13 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     4057 | 2024-02-21 | Astralis          | L   | 0.100      | -            | -                | -                | -         |    -0.07 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            8 |     4087 | 2024-02-20 | Apeks             | L   | 0.094      | -            | -                | -                | -         |    -1.85 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4102 | 2024-02-19 | Nexus             | W   | 0.089      | -            | -                | -                | 1 (0.089) |     0.81 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            6 |     4111 | 2024-02-19 | Gaimin Gladiators | L   | 0.087      | -            | -                | -                | -         |    -1.51 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4121 | 2024-02-18 | Aurora            | W   | 0.083      | 0.143        | 0.424 (0.005)    | -                | -         |     2.55 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            4 |     4127 | 2024-02-18 | SINNERS           | W   | 0.082      | -            | -                | -                | -         |     1.61 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4152 | 2024-02-17 | Aurora            | W   | 0.075      | 0.143        | 0.424 (0.005)    | -                | -         |     2.31 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4157 | 2024-02-17 | The Chosen Few    | W   | 0.074      | -            | -                | -                | -         |     0.33 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4357 | 2024-02-06 | G2                | L   | 0.001      | -            | -                | -                | -         |     0.00 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,248.11)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $4,000.00      | $3,313.06       |
| 2024-05-12 |      0.641 | $17,500.00     | $11,224.31      |
| 2024-04-20 |      0.496 | $5,000.00      | $2,481.48       |
| 2024-03-10 |      0.223 | $7,500.00      | $1,669.27       |
| 2024-02-11 |      0.035 | $16,000.00     | $560.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
