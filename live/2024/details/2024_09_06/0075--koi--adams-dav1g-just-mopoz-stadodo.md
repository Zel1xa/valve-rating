### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [75](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [55]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  927.3<br />
<br />
Final Rank Value (927.3) = Starting Rank Value (960.3) + Head To Head Adjustments (-33.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.440[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.176[<sup>2</sup>](#table1)
- LAN Wins: 0.133[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 960.3
- 400 + ( ( 0.287 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 960.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |        0 | 2024-09-06 | Wildcard          | L   | 1.000      | -            | -                | -                | -         |    -6.96 | adamS, dav1g, JUST, mopoz, stadodo |
|           45 |       55 | 2024-09-05 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -0.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      105 | 2024-09-03 | G2                | L   | 1.000      | -            | -                | -                | -         |    -0.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      510 | 2024-08-23 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -10.36 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      521 | 2024-08-23 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -15.93 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      552 | 2024-08-22 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |    -9.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |      589 | 2024-08-21 | Monte             | W   | 1.000      | 0.143        | -                | 0.714 (0.102)    | 0 (0.000) |    17.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |      631 | 2024-08-21 | ENCE              | W   | 1.000      | 0.143        | 0.131 (0.019)    | 0.342 (0.049)    | 0 (0.000) |    24.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |      675 | 2024-08-19 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -12.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |      684 | 2024-08-19 | Gaimin Gladiators | W   | 1.000      | 0.143        | 0.019 (0.003)    | 0.511 (0.073)    | 0 (0.000) |    13.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |      784 | 2024-08-15 | HOTU              | L   | 1.000      | -            | -                | -                | -         |   -23.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |      832 | 2024-08-13 | B8                | L   | 1.000      | -            | -                | -                | -         |   -10.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |      884 | 2024-08-12 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -9.62 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     1074 | 2024-08-06 | Sashi             | L   | 0.993      | -            | -                | -                | -         |   -11.37 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     1288 | 2024-07-31 | Zero Tenacity     | L   | 0.953      | -            | -                | -                | -         |    -9.77 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     1450 | 2024-07-26 | EYEBALLERS        | W   | 0.919      | 0.500        | -                | 0.417 (0.192)    | 0 (0.000) |     4.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     1725 | 2024-07-18 | Monte             | L   | 0.867      | -            | -                | -                | -         |   -16.48 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     1861 | 2024-07-16 | Insilio           | W   | 0.853      | 0.500        | 0.023 (0.010)    | 0.636 (0.271)    | 0 (0.000) |    11.02 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2128 | 2024-06-16 | 9z                | L   | 0.653      | -            | -                | -                | -         |    -1.56 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     2178 | 2024-06-14 | RED Canids        | W   | 0.642      | 0.548        | 0.050 (0.018)    | 0.633 (0.223)    | 1 (0.642) |    12.54 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     2183 | 2024-06-14 | Imperial          | W   | 0.641      | 0.548        | 0.152 (0.054)    | 0.613 (0.215)    | 1 (0.641) |    14.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     2349 | 2024-06-09 | Sangal            | L   | 0.606      | -            | -                | -                | -         |    -2.96 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     2537 | 2024-06-06 | SINNERS           | W   | 0.586      | 0.500        | 0.081 (0.024)    | 1.000 (0.293)    | 0 (0.000) |    11.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     2598 | 2024-06-05 | 3DMAX             | W   | 0.580      | 0.500        | 0.470 (0.136)    | 0.946 (0.274)    | 0 (0.000) |    17.77 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     2727 | 2024-06-01 | ENCE              | L   | 0.553      | -            | -                | -                | -         |    -3.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     2733 | 2024-06-01 | Zero Tenacity     | L   | 0.552      | -            | -                | -                | -         |    -5.75 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3403 | 2024-05-09 | B8                | L   | 0.397      | -            | -                | -                | -         |    -4.78 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3566 | 2024-05-01 | Zero Tenacity     | L   | 0.345      | -            | -                | -                | -         |    -4.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3882 | 2024-04-18 | ex-Guild Eagles   | L   | 0.260      | -            | -                | -                | -         |    -6.32 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3893 | 2024-04-18 | fnatic            | W   | 0.259      | 0.143        | 0.293 (0.011)    | -                | 0 (0.000) |     7.30 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3967 | 2024-04-16 | BLEED             | L   | 0.246      | -            | -                | -                | -         |    -4.93 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     4098 | 2024-04-10 | RUSH B            | W   | 0.207      | 0.500        | 0.025 (0.003)    | -                | -         |     2.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     4153 | 2024-04-09 | Aurora            | W   | 0.200      | 0.500        | 0.294 (0.029)    | 0.629 (0.063)    | -         |     5.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     4159 | 2024-04-09 | Apeks             | L   | 0.199      | -            | -                | -                | -         |    -4.66 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     4186 | 2024-04-08 | GUN5              | W   | 0.193      | -            | -                | -                | -         |     0.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     4187 | 2024-04-08 | fnatic            | L   | 0.192      | -            | -                | -                | -         |    -0.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     4290 | 2024-04-04 | NOM               | W   | 0.166      | -            | -                | -                | -         |     0.46 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     4324 | 2024-04-03 | 9INE              | W   | 0.160      | -            | -                | -                | -         |     0.39 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     4362 | 2024-04-02 | TSM               | W   | 0.153      | -            | -                | -                | -         |     0.69 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     4429 | 2024-03-28 | EYEBALLERS        | L   | 0.119      | -            | -                | -                | -         |    -2.62 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     4601 | 2024-03-18 | FURIA             | L   | 0.053      | -            | -                | -                | -         |    -0.03 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     4616 | 2024-03-17 | ENCE              | L   | 0.047      | -            | -                | -                | -         |    -0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4632 | 2024-03-17 | SAW               | L   | 0.046      | -            | -                | -                | -         |    -0.05 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4724 | 2024-03-13 | Sangal            | W   | 0.020      | -            | -                | -                | -         |     0.55 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4778 | 2024-03-11 | B8                | L   | 0.007      | -            | -                | -                | -         |    -0.08 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4787 | 2024-03-11 | Apeks             | L   | 0.006      | -            | -                | -                | -         |    -0.13 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,521.46)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-06 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-09-06 |      1.000 | $500.00        | $500.00         |
| 2024-06-16 |      0.655 | $7,000.00      | $4,584.19       |
| 2024-06-09 |      0.606 | $12,000.00     | $7,272.22       |
| 2024-03-20 |      0.067 | $10,000.00     | $665.05         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
