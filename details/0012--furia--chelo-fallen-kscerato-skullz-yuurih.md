### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1604.7<br />
<br />
Final Rank Value (1604.7) = Starting Rank Value (1721.1) + Head To Head Adjustments (-116.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.417[<sup>2</sup>](#table1)
- LAN Wins: 0.901[<sup>2</sup>](#table1)

The average of these factors is 0.646<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1721.1
- 400 + ( ( 0.646 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1721.1


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
|           45 |      532 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.62 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      578 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.721 (0.721)    | 1 (1.000) |    22.76 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      589 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.962 (0.962)    | 1 (1.000) |     2.87 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      600 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.294 (0.294)    | 1 (1.000) |     3.04 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      658 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.20 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1259 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.821      | -            | -                | -                | -         |   -12.71 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1378 | 2024-06-06 | Complexity         | W   | 0.808      | 0.715        | 0.310 (0.179)    | 0.380 (0.220)    | 1 (0.808) |    13.72 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1395 | 2024-06-06 | fnatic             | W   | 0.807      | 0.715        | 0.371 (0.214)    | 0.708 (0.409)    | 1 (0.807) |     8.83 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1417 | 2024-06-06 | Eternal Fire       | W   | 0.805      | 0.715        | 0.742 (0.428)    | 0.458 (0.264)    | 1 (0.805) |    15.56 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1447 | 2024-06-05 | BetBoom            | W   | 0.801      | 0.715        | 0.251 (0.144)    | 0.541 (0.310)    | 1 (0.801) |     6.76 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1464 | 2024-06-05 | BIG                | L   | 0.799      | -            | -                | -                | -         |   -19.98 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1542 | 2024-06-02 | GUN5               | L   | 0.781      | -            | -                | -                | -         |   -23.81 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1547 | 2024-06-02 | MOUZ NXT           | W   | 0.780      | 0.435        | 0.139 (0.047)    | 1.000 (0.339)    | -         |     1.43 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1586 | 2024-06-01 | Zero Tenacity      | W   | 0.772      | 0.435        | -                | 1.000 (0.336)    | -         |     1.53 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1637 | 2024-05-30 | RUBY               | W   | 0.760      | -            | -                | -                | -         |     0.59 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1745 | 2024-05-25 | 1WIN               | L   | 0.726      | -            | -                | -                | -         |   -22.11 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1757 | 2024-05-24 | Passion UA         | W   | 0.720      | 0.435        | 0.172 (0.054)    | 1.000 (0.313)    | -         |     0.86 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2320 | 2024-05-05 | Monte              | L   | 0.594      | -            | -                | -                | -         |   -18.13 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2340 | 2024-05-04 | ENCE               | W   | 0.587      | 0.889        | 0.169 (0.088)    | -                | 1 (0.587) |     3.71 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2355 | 2024-05-03 | Bad News Kangaroos | W   | 0.581      | -            | -                | -                | 1 (0.581) |     0.17 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2398 | 2024-05-01 | FORZE              | L   | 0.568      | -            | -                | -                | -         |   -17.56 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2420 | 2024-04-30 | Liquid             | L   | 0.561      | -            | -                | -                | -         |   -10.62 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2670 | 2024-04-19 | MIBR               | L   | 0.489      | -            | -                | -                | -         |   -11.95 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2695 | 2024-04-19 | Metizport          | W   | 0.487      | -            | -                | -                | 1 (0.487) |     0.25 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2721 | 2024-04-18 | 9z                 | L   | 0.482      | -            | -                | -                | -         |   -10.28 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     3012 | 2024-04-09 | HEROIC             | L   | 0.420      | -            | -                | -                | -         |    -8.84 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3041 | 2024-04-08 | MOUZ               | L   | 0.413      | -            | -                | -                | -         |    -3.82 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3053 | 2024-04-07 | Lynn Vision        | W   | 0.411      | -            | -                | -                | -         |     0.36 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3371 | 2024-03-22 | Gaimin Gladiators  | L   | 0.302      | -            | -                | -                | -         |    -9.32 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3389 | 2024-03-21 | FaZe               | L   | 0.296      | -            | -                | -                | -         |    -4.98 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3399 | 2024-03-21 | G2                 | L   | 0.294      | -            | -                | -                | -         |    -1.51 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3423 | 2024-03-20 | SAW                | W   | 0.288      | -            | -                | -                | -         |     0.44 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3439 | 2024-03-19 | ENCE               | W   | 0.281      | -            | -                | -                | -         |     1.71 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3447 | 2024-03-18 | KOI                | W   | 0.275      | -            | -                | -                | -         |     0.26 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3460 | 2024-03-17 | Lynn Vision        | L   | 0.269      | -            | -                | -                | -         |    -8.28 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3475 | 2024-03-17 | Legacy             | L   | 0.268      | -            | -                | -                | -         |    -8.27 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3824 | 2024-03-03 | Complexity         | W   | 0.175      | -            | -                | -                | -         |     2.18 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3858 | 2024-03-02 | Liquid             | W   | 0.168      | -            | -                | -                | -         |     1.73 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3880 | 2024-03-01 | Nouns              | W   | 0.162      | -            | -                | -                | -         |     0.06 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4013 | 2024-02-23 | 9z                 | L   | 0.116      | -            | -                | -                | -         |    -2.66 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4027 | 2024-02-22 | 9z                 | W   | 0.110      | -            | -                | -                | -         |     0.96 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4034 | 2024-02-22 | Imperial           | W   | 0.109      | -            | -                | -                | -         |     0.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4315 | 2024-02-10 | Metizport          | L   | 0.028      | -            | -                | -                | -         |    -0.87 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4316 | 2024-02-10 | ex-Anonymo         | W   | 0.028      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4320 | 2024-02-10 | Metizport          | L   | 0.027      | -            | -                | -                | -         |    -0.84 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92,100.67)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.827 | $28,000.00     | $23,165.46      |
| 2024-06-02 |      0.781 | $10,000.00     | $7,806.71       |
| 2024-05-26 |      0.734 | $2,000.00      | $1,468.56       |
| 2024-05-12 |      0.641 | $12,000.00     | $7,688.06       |
| 2024-04-20 |      0.496 | $5,000.00      | $2,477.89       |
| 2024-04-14 |      0.453 | $5,000.00      | $2,263.89       |
| 2024-03-31 |      0.362 | $20,000.00     | $7,230.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
