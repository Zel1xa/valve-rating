### Roster Details<br />
Team Name: SAW<br />
Roster: arrozdoce, ewjerkz, MUTiRiS, roman, story<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1196.8<br />
<br />
Final Rank Value (1196.8) = Starting Rank Value (1181.2) + Head To Head Adjustments (15.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.508[<sup>1</sup>](#table2)
- Bounty Collected: 0.508[<sup>2</sup>](#table1)
- Opponent Network: 0.272[<sup>2</sup>](#table1)
- LAN Wins: 0.228[<sup>2</sup>](#table1)

The average of these factors is 0.379<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1181.2
- 400 + ( ( 0.379 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1181.2


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
|           55 |       15 | 2024-07-31 | brazylijski luz   | W   | 1.000      | 0.500        | -                | 0.264 (0.132)    | 0 (0.000) |     4.04 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           54 |      133 | 2024-07-28 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.65 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           53 |      146 | 2024-07-27 | Passion UA        | W   | 1.000      | 0.435        | 0.171 (0.074)    | 1.000 (0.435)    | 0 (0.000) |    12.25 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           52 |      219 | 2024-07-25 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.88 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           51 |      249 | 2024-07-24 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -22.71 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           50 |      406 | 2024-07-19 | RUSH B            | W   | 1.000      | 0.500        | -                | 0.308 (0.154)    | -         |     4.87 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           49 |      517 | 2024-07-17 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.110)    | 0.824 (0.412)    | -         |    16.97 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           48 |      627 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.721 (0.360)    | -         |     7.14 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           47 |      968 | 2024-06-13 | Astralis          | L   | 0.877      | -            | -                | -                | -         |    -1.40 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           46 |      994 | 2024-06-12 | FaZe              | L   | 0.871      | -            | -                | -                | -         |    -0.99 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           45 |     1034 | 2024-06-10 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |    -5.75 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           44 |     1043 | 2024-06-10 | RUSH B            | W   | 0.858      | -            | -                | -                | -         |     5.48 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           43 |     1046 | 2024-06-10 | Aurora            | W   | 0.857      | 0.143        | 0.429 (0.053)    | 0.800 (0.098)    | -         |    21.41 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           42 |     1079 | 2024-06-09 | SINNERS           | L   | 0.852      | -            | -                | -                | -         |   -18.70 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           41 |     1085 | 2024-06-09 | Monte             | W   | 0.851      | -            | -                | -                | -         |     7.41 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           40 |     1092 | 2024-06-09 | 9 Pandas          | L   | 0.851      | -            | -                | -                | -         |   -16.98 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           39 |     1097 | 2024-06-09 | PARIVISION        | W   | 0.851      | -            | -                | -                | -         |     9.47 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           38 |     1316 | 2024-06-05 | Sangal            | L   | 0.826      | -            | -                | -                | -         |   -15.00 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           37 |     1366 | 2024-06-04 | RUSH B            | L   | 0.819      | -            | -                | -                | -         |   -22.59 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           36 |     1416 | 2024-06-02 | Zero Tenacity     | L   | 0.805      | -            | -                | -                | -         |   -16.23 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           35 |     1480 | 2024-05-31 | Sangal            | W   | 0.792      | 0.143        | 0.219 (0.025)    | -                | -         |     8.85 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           34 |     1486 | 2024-05-31 | fnatic            | L   | 0.792      | -            | -                | -                | -         |    -4.74 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           33 |     1491 | 2024-05-31 | FAVBET            | W   | 0.791      | -            | -                | -                | -         |     2.01 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           32 |     1864 | 2024-05-17 | Aurora            | L   | 0.697      | -            | -                | -                | -         |    -3.01 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           31 |     1886 | 2024-05-16 | Eternal Fire      | L   | 0.693      | -            | -                | -                | -         |    -1.47 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           30 |     1901 | 2024-05-16 | Aurora            | W   | 0.690      | 0.769        | 0.429 (0.228)    | 0.800 (0.424)    | -         |    19.23 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           29 |     2343 | 2024-04-28 | Virtus.pro        | L   | 0.572      | -            | -                | -                | -         |    -1.08 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           28 |     2359 | 2024-04-27 | Eternal Fire      | W   | 0.566      | 0.889        | 0.752 (0.378)    | 0.462 (0.232)    | 1 (0.566) |    16.85 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           27 |     2392 | 2024-04-26 | Imperial          | W   | 0.558      | 0.889        | 0.243 (0.120)    | 0.685 (0.340)    | 1 (0.558) |    11.87 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           26 |     2440 | 2024-04-24 | Virtus.pro        | L   | 0.545      | -            | -                | -                | -         |    -0.88 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           25 |     2464 | 2024-04-23 | 3DMAX             | L   | 0.538      | -            | -                | -                | -         |    -1.32 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           24 |     2696 | 2024-04-16 | Sampi             | L   | 0.491      | -            | -                | -                | -         |   -12.73 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           23 |     2814 | 2024-04-10 | 9 Pandas          | W   | 0.453      | 0.500        | -                | 0.579 (0.131)    | -         |     3.62 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           22 |     2869 | 2024-04-09 | 3DMAX             | L   | 0.446      | -            | -                | -                | -         |    -0.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           21 |     2975 | 2024-04-05 | PGE Turow         | W   | 0.417      | -            | -                | -                | -         |     0.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           20 |     3010 | 2024-04-04 | Betera            | W   | 0.412      | -            | -                | -                | -         |     0.84 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           19 |     3053 | 2024-04-03 | PERA              | W   | 0.405      | -            | -                | -                | -         |     2.29 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           18 |     3298 | 2024-03-20 | FURIA             | L   | 0.313      | -            | -                | -                | -         |    -0.46 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           17 |     3315 | 2024-03-19 | paiN              | L   | 0.305      | -            | -                | -                | -         |    -2.01 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           16 |     3323 | 2024-03-18 | Cloud9            | L   | 0.299      | -            | -                | -                | -         |    -6.32 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           15 |     3336 | 2024-03-17 | GamerLegion       | W   | 0.294      | -            | -                | -                | 1 (0.294) |     0.96 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           14 |     3353 | 2024-03-17 | KOI               | W   | 0.292      | -            | -                | -                | 1 (0.292) |     3.41 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           13 |     3443 | 2024-03-13 | System5           | W   | 0.266      | -            | -                | -                | -         |     0.45 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           12 |     3527 | 2024-03-10 | OG                | W   | 0.246      | 0.535        | 0.143 (0.019)    | -                | -         |     2.15 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           11 |     3568 | 2024-03-08 | Cloud9            | W   | 0.233      | -            | -                | -                | -         |     2.43 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           10 |     3602 | 2024-03-07 | Liquid            | W   | 0.225      | 0.535        | 0.387 (0.047)    | -                | -         |     5.89 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            9 |     3659 | 2024-03-05 | Monte             | W   | 0.213      | -            | -                | -                | -         |     1.88 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            8 |     3822 | 2024-02-26 | RUSH B            | W   | 0.160      | -            | -                | -                | -         |     0.66 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            7 |     4037 | 2024-02-17 | fnatic            | W   | 0.098      | -            | -                | -                | 1 (0.098) |     2.80 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            6 |     4058 | 2024-02-16 | Enterprise        | W   | 0.093      | -            | -                | -                | 1 (0.093) |     0.57 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            5 |     4093 | 2024-02-15 | Ninjas in Pyjamas | W   | 0.085      | -            | -                | -                | 1 (0.085) |     0.03 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            4 |     4131 | 2024-02-14 | 9 Pandas          | L   | 0.079      | -            | -                | -                | -         |    -1.80 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            3 |     4142 | 2024-02-14 | Virtus.pro        | L   | 0.077      | -            | -                | -                | -         |    -0.11 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            2 |     4268 | 2024-02-04 | Rhyno             | W   | 0.012      | -            | -                | -                | -         |     0.09 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            1 |     4299 | 2024-02-03 | KOI               | W   | 0.005      | -            | -                | -                | -         |     0.06 | arrozdoce, ewjerkz, MUTiRiS, roman, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35,554.99)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.898 | $10,000.00     | $8,982.27       |
| 2024-06-09 |      0.852 | $6,500.00      | $5,538.30       |
| 2024-05-12 |      0.665 | $12,000.00     | $7,982.06       |
| 2024-03-20 |      0.313 | $10,000.00     | $3,125.32       |
| 2024-03-10 |      0.246 | $20,000.00     | $4,927.04       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
