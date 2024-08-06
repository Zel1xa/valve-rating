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
Final Rank Value (1607.6) = Starting Rank Value (1720.5) + Head To Head Adjustments (-112.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.403[<sup>2</sup>](#table1)
- LAN Wins: 0.899[<sup>2</sup>](#table1)

The average of these factors is 0.642<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1720.5
- 400 + ( ( 0.642 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1720.5


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
|           45 |      592 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.75 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      638 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.694 (0.694)    | 1 (1.000) |    22.74 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      649 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.958 (0.958)    | 1 (1.000) |     2.85 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      660 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.278 (0.278)    | 1 (1.000) |     2.91 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      718 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.24 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1319 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.808      | -            | -                | -                | -         |   -12.61 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1438 | 2024-06-06 | Complexity         | W   | 0.795      | 0.715        | 0.341 (0.194)    | -                | 1 (0.795) |    13.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1455 | 2024-06-06 | fnatic             | W   | 0.794      | 0.715        | 0.371 (0.211)    | 0.680 (0.386)    | 1 (0.794) |     8.64 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1477 | 2024-06-06 | Eternal Fire       | W   | 0.792      | 0.715        | 0.739 (0.419)    | 0.438 (0.248)    | 1 (0.792) |    15.18 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1507 | 2024-06-05 | BetBoom            | W   | 0.788      | 0.715        | 0.248 (0.140)    | 0.514 (0.290)    | 1 (0.788) |     6.49 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1524 | 2024-06-05 | BIG                | L   | 0.786      | -            | -                | -                | -         |   -19.80 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1602 | 2024-06-02 | GUN5               | L   | 0.768      | -            | -                | -                | -         |   -23.42 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1607 | 2024-06-02 | MOUZ NXT           | W   | 0.767      | 0.435        | -                | 0.962 (0.321)    | -         |     1.41 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1646 | 2024-06-01 | Zero Tenacity      | W   | 0.759      | 0.435        | 0.143 (0.047)    | 1.000 (0.330)    | -         |     1.50 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1697 | 2024-05-30 | RUBY               | W   | 0.747      | -            | -                | -                | -         |     0.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1805 | 2024-05-25 | 1WIN               | L   | 0.713      | -            | -                | -                | -         |   -21.68 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1817 | 2024-05-24 | Passion UA         | W   | 0.708      | 0.435        | 0.173 (0.053)    | 1.000 (0.307)    | -         |     0.88 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2380 | 2024-05-05 | Monte              | L   | 0.581      | -            | -                | -                | -         |   -17.76 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2400 | 2024-05-04 | ENCE               | W   | 0.574      | 0.889        | 0.173 (0.088)    | 0.422 (0.215)    | 1 (0.574) |     3.79 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2415 | 2024-05-03 | Bad News Kangaroos | W   | 0.568      | -            | -                | -                | 1 (0.568) |     0.16 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2458 | 2024-05-01 | FORZE              | L   | 0.555      | -            | -                | -                | -         |   -17.17 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2480 | 2024-04-30 | Liquid             | L   | 0.548      | -            | -                | -                | -         |   -10.37 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2730 | 2024-04-19 | MIBR               | L   | 0.477      | -            | -                | -                | -         |   -11.77 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2755 | 2024-04-19 | Metizport          | W   | 0.474      | -            | -                | -                | 1 (0.474) |     0.24 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2781 | 2024-04-18 | 9z                 | L   | 0.469      | -            | -                | -                | -         |   -10.10 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     3072 | 2024-04-09 | HEROIC             | L   | 0.407      | -            | -                | -                | -         |    -8.65 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3101 | 2024-04-08 | MOUZ               | L   | 0.400      | -            | -                | -                | -         |    -3.76 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3113 | 2024-04-07 | Lynn Vision        | W   | 0.399      | -            | -                | -                | -         |     0.35 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3431 | 2024-03-22 | Gaimin Gladiators  | L   | 0.289      | -            | -                | -                | -         |    -8.93 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3449 | 2024-03-21 | FaZe               | L   | 0.283      | -            | -                | -                | -         |    -4.86 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3459 | 2024-03-21 | G2                 | L   | 0.281      | -            | -                | -                | -         |    -1.44 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3483 | 2024-03-20 | SAW                | W   | 0.275      | -            | -                | -                | -         |     0.40 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3499 | 2024-03-19 | ENCE               | W   | 0.268      | -            | -                | -                | -         |     1.71 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3507 | 2024-03-18 | KOI                | W   | 0.262      | -            | -                | -                | -         |     0.24 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3520 | 2024-03-17 | Lynn Vision        | L   | 0.256      | -            | -                | -                | -         |    -7.88 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3535 | 2024-03-17 | Legacy             | L   | 0.255      | -            | -                | -                | -         |    -7.87 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3884 | 2024-03-03 | Complexity         | W   | 0.162      | -            | -                | -                | -         |     2.07 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3918 | 2024-03-02 | Liquid             | W   | 0.155      | -            | -                | -                | -         |     1.61 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3940 | 2024-03-01 | Nouns              | W   | 0.149      | -            | -                | -                | -         |     0.05 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4073 | 2024-02-23 | 9z                 | L   | 0.103      | -            | -                | -                | -         |    -2.38 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4087 | 2024-02-22 | 9z                 | W   | 0.097      | -            | -                | -                | -         |     0.83 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4094 | 2024-02-22 | Imperial           | W   | 0.096      | -            | -                | -                | -         |     0.21 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4375 | 2024-02-10 | Metizport          | L   | 0.015      | -            | -                | -                | -         |    -0.47 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4376 | 2024-02-10 | ex-Anonymo         | W   | 0.015      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4380 | 2024-02-10 | Metizport          | L   | 0.014      | -            | -                | -                | -         |    -0.44 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($91,043.40)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.814 | $28,000.00     | $22,804.44      |
| 2024-06-02 |      0.768 | $10,000.00     | $7,677.78       |
| 2024-05-26 |      0.721 | $2,000.00      | $1,442.78       |
| 2024-05-12 |      0.628 | $12,000.00     | $7,533.33       |
| 2024-04-20 |      0.483 | $5,000.00      | $2,413.43       |
| 2024-04-14 |      0.440 | $5,000.00      | $2,199.42       |
| 2024-03-31 |      0.349 | $20,000.00     | $6,972.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
