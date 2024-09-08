### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  900.1<br />
<br />
Final Rank Value (900.1) = Starting Rank Value (894.6) + Head To Head Adjustments (5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.351[<sup>2</sup>](#table1)
- Opponent Network: 0.169[<sup>2</sup>](#table1)
- LAN Wins: 0.114[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 894.6
- 400 + ( ( 0.255 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 894.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |       16 | 2024-09-07 | PeeP            | L   | 1.000      | -            | -                | -                | -         |   -28.21 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           41 |       78 | 2024-09-05 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -21.19 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           40 |      558 | 2024-08-23 | KOI             | W   | 1.000      | 0.143        | 0.053 (0.008)    | -                | 0 (0.000) |    16.01 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           39 |      597 | 2024-08-22 | Rhyno           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.63 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           38 |      618 | 2024-08-21 | ENCE            | W   | 1.000      | 0.143        | 0.130 (0.019)    | -                | 0 (0.000) |    24.56 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           37 |      649 | 2024-08-21 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -11.32 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           36 |      901 | 2024-08-13 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -15.36 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           35 |      961 | 2024-08-11 | Revenant        | W   | 1.000      | 0.333        | 0.042 (0.014)    | 0.666 (0.222)    | 0 (0.000) |    15.55 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           34 |     1014 | 2024-08-09 | kONO            | W   | 0.999      | 0.333        | 0.025 (0.008)    | 0.532 (0.177)    | 0 (0.000) |    12.78 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           33 |     1125 | 2024-08-06 | NAVI Junior     | W   | 0.980      | -            | -                | -                | 0 (0.000) |     7.34 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           32 |     1698 | 2024-07-20 | Insilio         | L   | 0.866      | -            | -                | -                | -         |   -12.75 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |     1730 | 2024-07-19 | Enterprise      | L   | 0.860      | -            | -                | -                | -         |   -14.56 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |     1961 | 2024-07-15 | kONO            | W   | 0.832      | 0.371        | 0.025 (0.008)    | 0.532 (0.164)    | 0 (0.000) |    10.91 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |     2020 | 2024-07-11 | ALTERNATE aTTaX | W   | 0.805      | 0.371        | 0.102 (0.030)    | 0.837 (0.250)    | -         |    14.20 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     2146 | 2024-06-18 | kONO            | L   | 0.652      | -            | -                | -                | -         |   -11.95 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     2149 | 2024-06-17 | K10             | W   | 0.646      | -            | -                | -                | -         |     4.28 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     2178 | 2024-06-16 | Verdant         | W   | 0.639      | 0.333        | -                | 0.353 (0.075)    | -         |     8.45 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     2721 | 2024-06-03 | Enterprise      | L   | 0.552      | -            | -                | -                | -         |    -9.20 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     2730 | 2024-06-02 | ECLOT           | L   | 0.547      | -            | -                | -                | -         |    -5.21 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     2736 | 2024-06-02 | SINNERS         | W   | 0.547      | 0.346        | 0.081 (0.015)    | 1.000 (0.189)    | 1 (0.547) |    12.64 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     2745 | 2024-06-02 | Passion UA      | L   | 0.545      | -            | -                | -                | -         |    -5.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     2762 | 2024-06-01 | ECLOT           | L   | 0.541      | -            | -                | -                | -         |    -5.21 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     2805 | 2024-05-31 | SINNERS         | W   | 0.533      | 0.346        | 0.081 (0.015)    | 1.000 (0.184)    | 1 (0.533) |    12.72 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     2809 | 2024-05-31 | Johnny Speeds   | W   | 0.532      | 0.371        | 0.102 (0.020)    | 0.956 (0.188)    | -         |    13.34 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     2854 | 2024-05-29 | Rebels          | W   | 0.520      | 0.371        | 0.028 (0.005)    | 0.656 (0.126)    | -         |     9.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     2867 | 2024-05-28 | GL Academy      | L   | 0.515      | -            | -                | -                | -         |   -12.19 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     2937 | 2024-05-25 | Partizan        | L   | 0.493      | -            | -                | -                | -         |   -10.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     2962 | 2024-05-23 | SINNERS         | L   | 0.481      | -            | -                | -                | -         |    -3.84 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     3055 | 2024-05-21 | Rebels          | W   | 0.465      | 0.371        | -                | 0.656 (0.113)    | -         |     8.14 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     3342 | 2024-05-13 | Johnny Speeds   | L   | 0.413      | -            | -                | -                | -         |    -2.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     3945 | 2024-04-18 | Johnny Speeds   | L   | 0.246      | -            | -                | -                | -         |    -1.61 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     3992 | 2024-04-17 | Viperio         | W   | 0.239      | -            | -                | -                | -         |     1.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     4015 | 2024-04-16 | Lilmix          | W   | 0.232      | -            | -                | -                | -         |     0.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     4046 | 2024-04-14 | Sashi           | L   | 0.219      | -            | -                | -                | -         |    -1.92 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     4160 | 2024-04-10 | SINNERS         | L   | 0.192      | -            | -                | -                | -         |    -1.18 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     4280 | 2024-04-06 | Sashi           | L   | 0.165      | -            | -                | -                | -         |    -1.46 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     4292 | 2024-04-05 | ECLOT           | W   | 0.159      | -            | -                | -                | -         |     3.66 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     4337 | 2024-04-04 | Sashi           | L   | 0.153      | -            | -                | -                | -         |    -1.35 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     4416 | 2024-04-02 | Illuminar       | W   | 0.139      | -            | -                | -                | -         |     0.44 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     4671 | 2024-03-17 | SINNERS         | L   | 0.034      | -            | -                | -                | -         |    -0.21 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     4683 | 2024-03-16 | ECLOT           | L   | 0.028      | -            | -                | -                | -         |    -0.24 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     4698 | 2024-03-15 | SINNERS         | W   | 0.021      | -            | -                | -                | 1 (0.021) |     0.54 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,902.04)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-13 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-18 |      0.652 | $3,000.00      | $1,955.83       |
| 2024-06-02 |      0.547 | $3,048.00      | $1,668.64       |
| 2024-04-18 |      0.246 | $3,000.00      | $737.50         |
| 2024-04-06 |      0.165 | $3,000.00      | $495.83         |
| 2024-03-17 |      0.035 | $1,279.00      | $44.23          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
