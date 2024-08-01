### Roster Details<br />
Team Name: SAW<br />
Roster: arrozdoce, ewjerkz, MUTiRiS, roman, story<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1185.8<br />
<br />
Final Rank Value (1185.8) = Starting Rank Value (1179.5) + Head To Head Adjustments (6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.508[<sup>1</sup>](#table2)
- Bounty Collected: 0.506[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 0.224[<sup>2</sup>](#table1)

The average of these factors is 0.379<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1179.5
- 400 + ( ( 0.379 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1179.5


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
|           54 |       48 | 2024-07-31 | brazylijski luz   | W   | 1.000      | 0.500        | -                | 0.308 (0.154)    | 0 (0.000) |     4.57 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           53 |      166 | 2024-07-28 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -8.82 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           52 |      179 | 2024-07-27 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    12.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           51 |      253 | 2024-07-25 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.25 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           50 |      281 | 2024-07-24 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -23.33 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           49 |      442 | 2024-07-19 | RUSH B            | W   | 1.000      | 0.500        | -                | 0.308 (0.154)    | -         |     5.03 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           48 |      559 | 2024-07-17 | Sangal            | W   | 1.000      | 0.500        | 0.221 (0.110)    | 0.823 (0.412)    | -         |    16.49 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           47 |      675 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.768 (0.384)    | -         |     7.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           46 |     1007 | 2024-06-13 | Astralis          | L   | 0.872      | -            | -                | -                | -         |    -1.45 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           45 |     1033 | 2024-06-12 | FaZe              | L   | 0.865      | -            | -                | -                | -         |    -1.00 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           44 |     1075 | 2024-06-10 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -5.68 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           43 |     1084 | 2024-06-10 | RUSH B            | W   | 0.852      | -            | -                | -                | -         |     5.61 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           42 |     1087 | 2024-06-10 | Aurora            | W   | 0.851      | 0.143        | 0.431 (0.052)    | 0.798 (0.097)    | -         |    21.36 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           41 |     1120 | 2024-06-09 | SINNERS           | L   | 0.846      | -            | -                | -                | -         |   -17.98 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           40 |     1126 | 2024-06-09 | Monte             | W   | 0.846      | -            | -                | -                | -         |     7.33 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           39 |     1133 | 2024-06-09 | 9 Pandas          | L   | 0.845      | -            | -                | -                | -         |   -16.61 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           38 |     1139 | 2024-06-09 | PARIVISION        | W   | 0.845      | -            | -                | -                | -         |     9.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           37 |     1371 | 2024-06-05 | Sangal            | L   | 0.820      | -            | -                | -                | -         |   -15.18 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           36 |     1421 | 2024-06-04 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -22.31 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           35 |     1471 | 2024-06-02 | Zero Tenacity     | L   | 0.799      | -            | -                | -                | -         |   -16.42 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           34 |     1536 | 2024-05-31 | Sangal            | W   | 0.787      | 0.143        | 0.221 (0.025)    | -                | -         |     8.51 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           33 |     1542 | 2024-05-31 | fnatic            | L   | 0.786      | -            | -                | -                | -         |    -8.92 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           32 |     1547 | 2024-05-31 | FAVBET            | W   | 0.785      | -            | -                | -                | -         |     2.06 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           31 |     1948 | 2024-05-17 | Aurora            | L   | 0.691      | -            | -                | -                | -         |    -2.99 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           30 |     1970 | 2024-05-16 | Eternal Fire      | L   | 0.687      | -            | -                | -                | -         |    -1.51 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           29 |     1985 | 2024-05-16 | Aurora            | W   | 0.685      | 0.769        | 0.431 (0.227)    | 0.798 (0.420)    | -         |    19.06 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           28 |     2441 | 2024-04-28 | Virtus.pro        | L   | 0.566      | -            | -                | -                | -         |    -1.18 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           27 |     2457 | 2024-04-27 | Eternal Fire      | W   | 0.560      | 0.889        | 0.757 (0.377)    | 0.461 (0.229)    | 1 (0.560) |    16.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           26 |     2490 | 2024-04-26 | Imperial          | W   | 0.553      | 0.889        | 0.239 (0.118)    | 0.719 (0.353)    | 1 (0.553) |    11.32 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           25 |     2538 | 2024-04-24 | Virtus.pro        | L   | 0.539      | -            | -                | -                | -         |    -0.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           24 |     2564 | 2024-04-23 | 3DMAX             | L   | 0.532      | -            | -                | -                | -         |    -1.31 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           23 |     2804 | 2024-04-16 | Sampi             | L   | 0.485      | -            | -                | -                | -         |   -12.53 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           22 |     2923 | 2024-04-10 | 9 Pandas          | W   | 0.447      | 0.500        | 0.083 (0.019)    | 0.577 (0.129)    | -         |     3.54 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           21 |     2978 | 2024-04-09 | 3DMAX             | L   | 0.440      | -            | -                | -                | -         |    -0.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           20 |     3084 | 2024-04-05 | PGE Turow         | W   | 0.411      | -            | -                | -                | -         |     0.65 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           19 |     3119 | 2024-04-04 | Betera            | W   | 0.407      | -            | -                | -                | -         |     0.85 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           18 |     3168 | 2024-04-03 | PERA              | W   | 0.399      | -            | -                | -                | -         |     2.26 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           17 |     3420 | 2024-03-20 | FURIA             | L   | 0.307      | -            | -                | -                | -         |    -0.46 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           16 |     3437 | 2024-03-19 | paiN              | L   | 0.299      | -            | -                | -                | -         |    -2.58 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           15 |     3445 | 2024-03-18 | Cloud9            | L   | 0.293      | -            | -                | -                | -         |    -6.22 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           14 |     3458 | 2024-03-17 | GamerLegion       | W   | 0.288      | -            | -                | -                | 1 (0.288) |     0.93 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           13 |     3475 | 2024-03-17 | KOI               | W   | 0.286      | -            | -                | -                | 1 (0.286) |     1.80 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           12 |     3570 | 2024-03-13 | System5           | W   | 0.261      | -            | -                | -                | -         |     0.44 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           11 |     3654 | 2024-03-10 | OG                | W   | 0.240      | -            | -                | -                | -         |     1.99 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           10 |     3696 | 2024-03-08 | Cloud9            | W   | 0.227      | -            | -                | -                | -         |     2.33 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            9 |     3730 | 2024-03-07 | Liquid            | W   | 0.219      | 0.535        | 0.321 (0.038)    | -                | -         |     5.98 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            8 |     3787 | 2024-03-05 | Monte             | W   | 0.207      | -            | -                | -                | -         |     1.82 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            7 |     3957 | 2024-02-26 | RUSH B            | W   | 0.154      | -            | -                | -                | -         |     0.65 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            6 |     4179 | 2024-02-17 | fnatic            | W   | 0.093      | -            | -                | -                | 1 (0.093) |     2.18 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            5 |     4201 | 2024-02-16 | Enterprise        | W   | 0.087      | -            | -                | -                | 1 (0.087) |     0.54 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            4 |     4236 | 2024-02-15 | Ninjas in Pyjamas | W   | 0.079      | -            | -                | -                | 1 (0.079) |     0.03 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            3 |     4274 | 2024-02-14 | 9 Pandas          | L   | 0.073      | -            | -                | -                | -         |    -1.68 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            2 |     4285 | 2024-02-14 | Virtus.pro        | L   | 0.072      | -            | -                | -                | -         |    -0.11 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            1 |     4421 | 2024-02-04 | Rhyno             | W   | 0.006      | -            | -                | -                | -         |     0.05 | arrozdoce, ewjerkz, MUTiRiS, roman, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35,219.97)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.892 | $10,000.00     | $8,925.00       |
| 2024-06-09 |      0.846 | $6,500.00      | $5,501.08       |
| 2024-05-12 |      0.659 | $12,000.00     | $7,913.33       |
| 2024-03-20 |      0.307 | $10,000.00     | $3,068.06       |
| 2024-03-10 |      0.241 | $20,000.00     | $4,812.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
