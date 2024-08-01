### Roster Details<br />
Team Name: SAW<br />
Roster: arrozdoce, ewjerkz, MUTiRiS, roman, story<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1186.5<br />
<br />
Final Rank Value (1186.5) = Starting Rank Value (1181.2) + Head To Head Adjustments (5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.508[<sup>1</sup>](#table2)
- Bounty Collected: 0.507[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 0.225[<sup>2</sup>](#table1)

The average of these factors is 0.379<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1181.2
- 400 + ( ( 0.379 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1181.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       44 | 2024-07-31 | brazylijski luz   | W   | 1.000      | 0.500        | -                | 0.309 (0.154)    | 0 (0.000) |     4.56 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           54 |      162 | 2024-07-28 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -8.85 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           53 |      175 | 2024-07-27 | Passion UA        | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    12.61 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           52 |      249 | 2024-07-25 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           51 |      277 | 2024-07-24 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -23.34 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           50 |      438 | 2024-07-19 | RUSH B            | W   | 1.000      | 0.500        | -                | 0.308 (0.154)    | -         |     5.02 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           49 |      555 | 2024-07-17 | Sangal            | W   | 1.000      | 0.500        | 0.221 (0.111)    | 0.823 (0.412)    | -         |    16.45 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           48 |      671 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.768 (0.384)    | -         |     7.63 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           47 |     1003 | 2024-06-13 | Astralis          | L   | 0.873      | -            | -                | -                | -         |    -1.47 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           46 |     1029 | 2024-06-12 | FaZe              | L   | 0.866      | -            | -                | -                | -         |    -1.00 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           45 |     1071 | 2024-06-10 | 3DMAX             | L   | 0.854      | -            | -                | -                | -         |    -5.71 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           44 |     1080 | 2024-06-10 | RUSH B            | W   | 0.853      | -            | -                | -                | -         |     5.61 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           43 |     1083 | 2024-06-10 | Aurora            | W   | 0.853      | 0.143        | 0.432 (0.053)    | 0.798 (0.097)    | -         |    21.36 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           42 |     1116 | 2024-06-09 | SINNERS           | L   | 0.847      | -            | -                | -                | -         |   -18.01 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           41 |     1122 | 2024-06-09 | Monte             | W   | 0.847      | -            | -                | -                | -         |     7.33 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           40 |     1129 | 2024-06-09 | 9 Pandas          | L   | 0.847      | -            | -                | -                | -         |   -16.63 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           39 |     1135 | 2024-06-09 | PARIVISION        | W   | 0.846      | -            | -                | -                | -         |     9.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           38 |     1367 | 2024-06-05 | Sangal            | L   | 0.821      | -            | -                | -                | -         |   -15.25 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           37 |     1417 | 2024-06-04 | RUSH B            | L   | 0.815      | -            | -                | -                | -         |   -22.36 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           36 |     1467 | 2024-06-02 | Zero Tenacity     | L   | 0.801      | -            | -                | -                | -         |   -16.46 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           35 |     1532 | 2024-05-31 | Sangal            | W   | 0.788      | 0.143        | 0.221 (0.025)    | -                | -         |     8.48 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           34 |     1538 | 2024-05-31 | fnatic            | L   | 0.787      | -            | -                | -                | -         |    -8.94 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           33 |     1543 | 2024-05-31 | FAVBET            | W   | 0.787      | -            | -                | -                | -         |     2.05 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           32 |     1944 | 2024-05-17 | Aurora            | L   | 0.693      | -            | -                | -                | -         |    -3.02 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           31 |     1966 | 2024-05-16 | Eternal Fire      | L   | 0.688      | -            | -                | -                | -         |    -1.52 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           30 |     1981 | 2024-05-16 | Aurora            | W   | 0.686      | 0.769        | 0.432 (0.228)    | 0.798 (0.421)    | -         |    19.08 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           29 |     2437 | 2024-04-28 | Virtus.pro        | L   | 0.567      | -            | -                | -                | -         |    -1.18 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           28 |     2453 | 2024-04-27 | Eternal Fire      | W   | 0.562      | 0.889        | 0.757 (0.378)    | 0.461 (0.230)    | 1 (0.562) |    16.68 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           27 |     2486 | 2024-04-26 | Imperial          | W   | 0.554      | 0.889        | 0.240 (0.118)    | 0.719 (0.354)    | 1 (0.554) |    11.36 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           26 |     2534 | 2024-04-24 | Virtus.pro        | L   | 0.541      | -            | -                | -                | -         |    -0.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           25 |     2560 | 2024-04-23 | 3DMAX             | L   | 0.533      | -            | -                | -                | -         |    -1.32 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           24 |     2800 | 2024-04-16 | Sampi             | L   | 0.486      | -            | -                | -                | -         |   -12.57 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           23 |     2919 | 2024-04-10 | 9 Pandas          | W   | 0.448      | 0.500        | 0.083 (0.019)    | 0.578 (0.130)    | -         |     3.55 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           22 |     2974 | 2024-04-09 | 3DMAX             | L   | 0.442      | -            | -                | -                | -         |    -0.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           21 |     3080 | 2024-04-05 | PGE Turow         | W   | 0.413      | -            | -                | -                | -         |     0.65 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           20 |     3115 | 2024-04-04 | Betera            | W   | 0.408      | -            | -                | -                | -         |     0.85 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           19 |     3164 | 2024-04-03 | PERA              | W   | 0.401      | -            | -                | -                | -         |     2.25 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           18 |     3416 | 2024-03-20 | FURIA             | L   | 0.308      | -            | -                | -                | -         |    -0.46 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           17 |     3433 | 2024-03-19 | paiN              | L   | 0.301      | -            | -                | -                | -         |    -2.59 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           16 |     3441 | 2024-03-18 | Cloud9            | L   | 0.295      | -            | -                | -                | -         |    -6.24 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           15 |     3454 | 2024-03-17 | GamerLegion       | W   | 0.289      | -            | -                | -                | 1 (0.289) |     0.93 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           14 |     3471 | 2024-03-17 | KOI               | W   | 0.287      | -            | -                | -                | 1 (0.287) |     1.81 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           13 |     3566 | 2024-03-13 | System5           | W   | 0.262      | -            | -                | -                | -         |     0.44 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           12 |     3650 | 2024-03-10 | OG                | W   | 0.241      | -            | -                | -                | -         |     1.99 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           11 |     3692 | 2024-03-08 | Cloud9            | W   | 0.229      | -            | -                | -                | -         |     2.35 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           10 |     3726 | 2024-03-07 | Liquid            | W   | 0.221      | 0.535        | 0.322 (0.038)    | -                | -         |     5.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            9 |     3783 | 2024-03-05 | Monte             | W   | 0.209      | -            | -                | -                | -         |     1.83 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            8 |     3953 | 2024-02-26 | RUSH B            | W   | 0.155      | -            | -                | -                | -         |     0.65 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            7 |     4175 | 2024-02-17 | fnatic            | W   | 0.094      | -            | -                | -                | 1 (0.094) |     2.21 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            6 |     4197 | 2024-02-16 | Enterprise        | W   | 0.088      | -            | -                | -                | 1 (0.088) |     0.54 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            5 |     4232 | 2024-02-15 | Ninjas in Pyjamas | W   | 0.080      | -            | -                | -                | 1 (0.080) |     0.03 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            4 |     4270 | 2024-02-14 | 9 Pandas          | L   | 0.074      | -            | -                | -                | -         |    -1.71 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            3 |     4281 | 2024-02-14 | Virtus.pro        | L   | 0.073      | -            | -                | -                | -         |    -0.11 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            2 |     4417 | 2024-02-04 | Rhyno             | W   | 0.007      | -            | -                | -                | -         |     0.06 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            1 |     4448 | 2024-02-03 | KOI               | W   | 0.001      | -            | -                | -                | -         |     0.00 | arrozdoce, ewjerkz, MUTiRiS, roman, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35,301.22)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.894 | $10,000.00     | $8,938.89       |
| 2024-06-09 |      0.848 | $6,500.00      | $5,510.10       |
| 2024-05-12 |      0.661 | $12,000.00     | $7,930.00       |
| 2024-03-20 |      0.308 | $10,000.00     | $3,081.94       |
| 2024-03-10 |      0.242 | $20,000.00     | $4,840.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
