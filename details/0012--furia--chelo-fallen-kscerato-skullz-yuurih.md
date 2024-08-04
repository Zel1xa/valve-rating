### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1605.7<br />
<br />
Final Rank Value (1605.7) = Starting Rank Value (1721.5) + Head To Head Adjustments (-115.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.416[<sup>2</sup>](#table1)
- LAN Wins: 0.901[<sup>2</sup>](#table1)

The average of these factors is 0.646<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1721.5
- 400 + ( ( 0.646 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1721.5


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
|           45 |      556 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.63 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      602 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.721 (0.721)    | 1 (1.000) |    22.73 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      613 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.962 (0.962)    | 1 (1.000) |     2.87 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      624 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.294 (0.294)    | 1 (1.000) |     3.03 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      682 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.18 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1283 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.820      | -            | -                | -                | -         |   -12.73 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1402 | 2024-06-06 | Complexity         | W   | 0.807      | 0.715        | 0.342 (0.198)    | 0.380 (0.219)    | 1 (0.807) |    13.95 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1419 | 2024-06-06 | fnatic             | W   | 0.806      | 0.715        | 0.371 (0.214)    | 0.708 (0.408)    | 1 (0.806) |     8.83 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1441 | 2024-06-06 | Eternal Fire       | W   | 0.804      | 0.715        | 0.742 (0.427)    | 0.458 (0.263)    | 1 (0.804) |    15.52 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1471 | 2024-06-05 | BetBoom            | W   | 0.800      | 0.715        | 0.251 (0.143)    | 0.541 (0.309)    | 1 (0.800) |     6.72 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1488 | 2024-06-05 | BIG                | L   | 0.798      | -            | -                | -                | -         |   -19.97 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1566 | 2024-06-02 | GUN5               | L   | 0.780      | -            | -                | -                | -         |   -23.77 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1571 | 2024-06-02 | MOUZ NXT           | W   | 0.779      | 0.435        | 0.139 (0.047)    | 1.000 (0.338)    | -         |     1.43 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1610 | 2024-06-01 | Zero Tenacity      | W   | 0.771      | 0.435        | -                | 1.000 (0.335)    | -         |     1.52 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1661 | 2024-05-30 | RUBY               | W   | 0.759      | -            | -                | -                | -         |     0.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1769 | 2024-05-25 | 1WIN               | L   | 0.725      | -            | -                | -                | -         |   -22.06 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1781 | 2024-05-24 | Passion UA         | W   | 0.719      | 0.435        | 0.172 (0.054)    | 1.000 (0.313)    | -         |     0.88 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2344 | 2024-05-05 | Monte              | L   | 0.593      | -            | -                | -                | -         |   -18.10 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2364 | 2024-05-04 | ENCE               | W   | 0.586      | 0.889        | 0.169 (0.088)    | -                | 1 (0.586) |     3.71 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2379 | 2024-05-03 | Bad News Kangaroos | W   | 0.579      | -            | -                | -                | 1 (0.579) |     0.17 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2422 | 2024-05-01 | FORZE              | L   | 0.567      | -            | -                | -                | -         |   -17.53 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2444 | 2024-04-30 | Liquid             | L   | 0.560      | -            | -                | -                | -         |   -10.56 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2694 | 2024-04-19 | MIBR               | L   | 0.488      | -            | -                | -                | -         |   -11.94 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2719 | 2024-04-19 | Metizport          | W   | 0.486      | -            | -                | -                | 1 (0.486) |     0.19 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2745 | 2024-04-18 | 9z                 | L   | 0.481      | -            | -                | -                | -         |   -10.27 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     3036 | 2024-04-09 | HEROIC             | L   | 0.419      | -            | -                | -                | -         |    -8.81 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3065 | 2024-04-08 | MOUZ               | L   | 0.412      | -            | -                | -                | -         |    -3.82 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3077 | 2024-04-07 | Lynn Vision        | W   | 0.410      | -            | -                | -                | -         |     0.35 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3395 | 2024-03-22 | Gaimin Gladiators  | L   | 0.301      | -            | -                | -                | -         |    -9.29 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3413 | 2024-03-21 | FaZe               | L   | 0.294      | -            | -                | -                | -         |    -4.96 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3423 | 2024-03-21 | G2                 | L   | 0.293      | -            | -                | -                | -         |    -1.50 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3447 | 2024-03-20 | SAW                | W   | 0.287      | -            | -                | -                | -         |     0.43 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3463 | 2024-03-19 | ENCE               | W   | 0.280      | -            | -                | -                | -         |     1.70 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3471 | 2024-03-18 | KOI                | W   | 0.273      | -            | -                | -                | -         |     0.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3484 | 2024-03-17 | Lynn Vision        | L   | 0.268      | -            | -                | -                | -         |    -8.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3499 | 2024-03-17 | Legacy             | L   | 0.267      | -            | -                | -                | -         |    -8.23 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3848 | 2024-03-03 | Complexity         | W   | 0.174      | -            | -                | -                | -         |     2.24 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3882 | 2024-03-02 | Liquid             | W   | 0.167      | -            | -                | -                | -         |     1.73 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3904 | 2024-03-01 | Nouns              | W   | 0.161      | -            | -                | -                | -         |     0.06 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4037 | 2024-02-23 | 9z                 | L   | 0.115      | -            | -                | -                | -         |    -2.63 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4051 | 2024-02-22 | 9z                 | W   | 0.109      | -            | -                | -                | -         |     0.94 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4058 | 2024-02-22 | Imperial           | W   | 0.108      | -            | -                | -                | -         |     0.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4339 | 2024-02-10 | Metizport          | L   | 0.027      | -            | -                | -                | -         |    -0.84 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4340 | 2024-02-10 | ex-Anonymo         | W   | 0.027      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4344 | 2024-02-10 | Metizport          | L   | 0.026      | -            | -                | -                | -         |    -0.81 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92,013.36)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.826 | $28,000.00     | $23,135.65      |
| 2024-06-02 |      0.780 | $10,000.00     | $7,796.06       |
| 2024-05-26 |      0.733 | $2,000.00      | $1,466.44       |
| 2024-05-12 |      0.640 | $12,000.00     | $7,675.28       |
| 2024-04-20 |      0.495 | $5,000.00      | $2,472.57       |
| 2024-04-14 |      0.452 | $5,000.00      | $2,258.56       |
| 2024-03-31 |      0.360 | $20,000.00     | $7,208.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
