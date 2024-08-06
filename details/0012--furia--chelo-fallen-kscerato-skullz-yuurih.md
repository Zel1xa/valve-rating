### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1607.6<br />
<br />
Final Rank Value (1607.6) = Starting Rank Value (1720.4) + Head To Head Adjustments (-112.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.403[<sup>2</sup>](#table1)
- LAN Wins: 0.898[<sup>2</sup>](#table1)

The average of these factors is 0.642<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1720.4
- 400 + ( ( 0.642 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1720.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      595 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.75 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      641 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.694 (0.694)    | 1 (1.000) |    22.74 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      652 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.958 (0.958)    | 1 (1.000) |     2.85 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      663 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.278 (0.278)    | 1 (1.000) |     2.90 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      721 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.24 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1322 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.808      | -            | -                | -                | -         |   -12.60 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1441 | 2024-06-06 | Complexity         | W   | 0.795      | 0.715        | 0.341 (0.194)    | -                | 1 (0.795) |    13.57 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1458 | 2024-06-06 | fnatic             | W   | 0.794      | 0.715        | 0.371 (0.210)    | 0.680 (0.386)    | 1 (0.794) |     8.63 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1480 | 2024-06-06 | Eternal Fire       | W   | 0.792      | 0.715        | 0.739 (0.419)    | 0.438 (0.248)    | 1 (0.792) |    15.17 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1510 | 2024-06-05 | BetBoom            | W   | 0.788      | 0.715        | 0.248 (0.140)    | 0.514 (0.289)    | 1 (0.788) |     6.48 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1527 | 2024-06-05 | BIG                | L   | 0.786      | -            | -                | -                | -         |   -19.79 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1605 | 2024-06-02 | GUN5               | L   | 0.767      | -            | -                | -                | -         |   -23.41 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1610 | 2024-06-02 | MOUZ NXT           | W   | 0.767      | 0.435        | -                | 0.962 (0.320)    | -         |     1.41 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1649 | 2024-06-01 | Zero Tenacity      | W   | 0.759      | 0.435        | 0.143 (0.047)    | 1.000 (0.330)    | -         |     1.50 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1700 | 2024-05-30 | RUBY               | W   | 0.747      | -            | -                | -                | -         |     0.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1808 | 2024-05-25 | 1WIN               | L   | 0.713      | -            | -                | -                | -         |   -21.67 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1820 | 2024-05-24 | Passion UA         | W   | 0.707      | 0.435        | 0.173 (0.053)    | 1.000 (0.307)    | -         |     0.88 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2383 | 2024-05-05 | Monte              | L   | 0.581      | -            | -                | -                | -         |   -17.75 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2403 | 2024-05-04 | ENCE               | W   | 0.574      | 0.889        | 0.173 (0.088)    | 0.422 (0.215)    | 1 (0.574) |     3.79 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2418 | 2024-05-03 | Bad News Kangaroos | W   | 0.567      | -            | -                | -                | 1 (0.567) |     0.16 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2461 | 2024-05-01 | FORZE              | L   | 0.555      | -            | -                | -                | -         |   -17.16 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2483 | 2024-04-30 | Liquid             | L   | 0.548      | -            | -                | -                | -         |   -10.36 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2733 | 2024-04-19 | MIBR               | L   | 0.476      | -            | -                | -                | -         |   -11.76 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2758 | 2024-04-19 | Metizport          | W   | 0.474      | -            | -                | -                | 1 (0.474) |     0.24 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2784 | 2024-04-18 | 9z                 | L   | 0.469      | -            | -                | -                | -         |   -10.09 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     3075 | 2024-04-09 | HEROIC             | L   | 0.406      | -            | -                | -                | -         |    -8.64 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3104 | 2024-04-08 | MOUZ               | L   | 0.400      | -            | -                | -                | -         |    -3.75 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3116 | 2024-04-07 | Lynn Vision        | W   | 0.398      | -            | -                | -                | -         |     0.35 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3434 | 2024-03-22 | Gaimin Gladiators  | L   | 0.288      | -            | -                | -                | -         |    -8.92 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3452 | 2024-03-21 | FaZe               | L   | 0.282      | -            | -                | -                | -         |    -4.86 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3462 | 2024-03-21 | G2                 | L   | 0.281      | -            | -                | -                | -         |    -1.44 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3486 | 2024-03-20 | SAW                | W   | 0.275      | -            | -                | -                | -         |     0.40 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3502 | 2024-03-19 | ENCE               | W   | 0.268      | -            | -                | -                | -         |     1.71 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3510 | 2024-03-18 | KOI                | W   | 0.261      | -            | -                | -                | -         |     0.24 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3523 | 2024-03-17 | Lynn Vision        | L   | 0.256      | -            | -                | -                | -         |    -7.87 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3538 | 2024-03-17 | Legacy             | L   | 0.254      | -            | -                | -                | -         |    -7.86 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3887 | 2024-03-03 | Complexity         | W   | 0.162      | -            | -                | -                | -         |     2.06 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3921 | 2024-03-02 | Liquid             | W   | 0.155      | -            | -                | -                | -         |     1.61 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3943 | 2024-03-01 | Nouns              | W   | 0.149      | -            | -                | -                | -         |     0.05 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4076 | 2024-02-23 | 9z                 | L   | 0.103      | -            | -                | -                | -         |    -2.37 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4090 | 2024-02-22 | 9z                 | W   | 0.096      | -            | -                | -                | -         |     0.83 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4097 | 2024-02-22 | Imperial           | W   | 0.095      | -            | -                | -                | -         |     0.21 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4378 | 2024-02-10 | Metizport          | L   | 0.015      | -            | -                | -                | -         |    -0.46 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4379 | 2024-02-10 | ex-Anonymo         | W   | 0.014      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4383 | 2024-02-10 | Metizport          | L   | 0.014      | -            | -                | -                | -         |    -0.43 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($91,013.03)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.814 | $28,000.00     | $22,794.07      |
| 2024-06-02 |      0.767 | $10,000.00     | $7,674.07       |
| 2024-05-26 |      0.721 | $2,000.00      | $1,442.04       |
| 2024-05-12 |      0.627 | $12,000.00     | $7,528.89       |
| 2024-04-20 |      0.482 | $5,000.00      | $2,411.57       |
| 2024-04-14 |      0.440 | $5,000.00      | $2,197.57       |
| 2024-03-31 |      0.348 | $20,000.00     | $6,964.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
