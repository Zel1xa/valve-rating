### Roster Details<br />
Team Name: UNiTY<br />
Roster: Blogg1s, K1-FiDa, Levi, M1key, Pechyn<br />
Global Rank: [72](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [54]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  935.8<br />
<br />
Final Rank Value (935.8) = Starting Rank Value (904.0) + Head To Head Adjustments (31.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.175[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.0
- 400 + ( ( 0.258 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 904.0


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
|           41 |       46 | 2024-09-05 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -21.33 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           40 |      526 | 2024-08-23 | KOI             | W   | 1.000      | 0.143        | 0.053 (0.008)    | -                | 0 (0.000) |    15.94 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           39 |      565 | 2024-08-22 | Rhyno           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.53 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           38 |      586 | 2024-08-21 | ENCE            | W   | 1.000      | 0.143        | 0.131 (0.019)    | -                | 0 (0.000) |    24.67 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           37 |      617 | 2024-08-21 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -11.39 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           36 |      869 | 2024-08-13 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -15.40 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           35 |      929 | 2024-08-11 | Revenant        | W   | 1.000      | 0.333        | 0.042 (0.014)    | 0.683 (0.228)    | 0 (0.000) |    15.51 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           34 |      982 | 2024-08-09 | kONO            | W   | 1.000      | 0.333        | 0.025 (0.008)    | 0.550 (0.183)    | 0 (0.000) |    12.65 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           33 |     1093 | 2024-08-06 | NAVI Junior     | W   | 0.988      | -            | -                | -                | 0 (0.000) |     7.21 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           32 |     1666 | 2024-07-20 | Insilio         | L   | 0.874      | -            | -                | -                | -         |   -13.21 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           31 |     1698 | 2024-07-19 | Enterprise      | L   | 0.868      | -            | -                | -                | -         |   -14.75 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           30 |     1929 | 2024-07-15 | kONO            | W   | 0.840      | 0.371        | 0.025 (0.008)    | 0.550 (0.171)    | 0 (0.000) |    10.94 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           29 |     1988 | 2024-07-11 | ALTERNATE aTTaX | W   | 0.813      | 0.371        | 0.101 (0.030)    | 0.862 (0.260)    | -         |    14.20 | Blogg1s, K1-FiDa, Levi, M1key, Pechyn |
|           28 |     2114 | 2024-06-18 | kONO            | L   | 0.660      | -            | -                | -                | -         |   -12.14 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           27 |     2117 | 2024-06-17 | K10             | W   | 0.654      | -            | -                | -                | -         |     4.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           26 |     2146 | 2024-06-16 | Verdant         | W   | 0.647      | 0.333        | -                | 0.365 (0.079)    | -         |     8.48 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           25 |     2689 | 2024-06-03 | Enterprise      | L   | 0.560      | -            | -                | -                | -         |    -9.37 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           24 |     2698 | 2024-06-02 | ECLOT           | L   | 0.555      | -            | -                | -                | -         |    -5.23 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           23 |     2704 | 2024-06-02 | SINNERS         | W   | 0.555      | 0.346        | 0.081 (0.016)    | 1.000 (0.192)    | 1 (0.555) |    12.75 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           22 |     2713 | 2024-06-02 | Passion UA      | L   | 0.553      | -            | -                | -                | -         |    -5.71 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           21 |     2730 | 2024-06-01 | ECLOT           | L   | 0.549      | -            | -                | -                | -         |    -5.24 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           20 |     2773 | 2024-05-31 | SINNERS         | W   | 0.541      | 0.346        | 0.081 (0.015)    | 1.000 (0.187)    | 1 (0.541) |    12.85 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           19 |     2777 | 2024-05-31 | Johnny Speeds   | W   | 0.540      | 0.371        | 0.103 (0.021)    | 0.989 (0.198)    | -         |    13.58 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           18 |     2822 | 2024-05-29 | Rebels          | W   | 0.527      | 0.371        | 0.028 (0.006)    | 0.677 (0.132)    | -         |     9.58 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           17 |     2835 | 2024-05-28 | GL Academy      | L   | 0.523      | -            | -                | -                | -         |   -12.45 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           16 |     2905 | 2024-05-25 | Partizan        | L   | 0.501      | -            | -                | -                | -         |   -11.07 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           15 |     2930 | 2024-05-23 | SINNERS         | L   | 0.488      | -            | -                | -                | -         |    -3.96 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           14 |     3023 | 2024-05-21 | Rebels          | W   | 0.473      | 0.371        | -                | 0.677 (0.119)    | -         |     8.27 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           13 |     3310 | 2024-05-13 | Johnny Speeds   | L   | 0.421      | -            | -                | -                | -         |    -2.67 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           12 |     3913 | 2024-04-18 | Johnny Speeds   | L   | 0.254      | -            | -                | -                | -         |    -1.63 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           11 |     3960 | 2024-04-17 | Viperio         | W   | 0.247      | -            | -                | -                | -         |     1.22 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|           10 |     3983 | 2024-04-16 | Lilmix          | W   | 0.240      | -            | -                | -                | -         |     0.43 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            9 |     4014 | 2024-04-14 | Sashi           | L   | 0.227      | -            | -                | -                | -         |    -1.97 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            8 |     4128 | 2024-04-10 | SINNERS         | L   | 0.200      | -            | -                | -                | -         |    -1.23 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            7 |     4248 | 2024-04-06 | Sashi           | L   | 0.173      | -            | -                | -                | -         |    -1.52 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            6 |     4260 | 2024-04-05 | ECLOT           | W   | 0.167      | -            | -                | -                | -         |     3.86 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            5 |     4305 | 2024-04-04 | Sashi           | L   | 0.161      | -            | -                | -                | -         |    -1.41 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            4 |     4384 | 2024-04-02 | Illuminar       | W   | 0.147      | -            | -                | -                | -         |     0.45 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            3 |     4639 | 2024-03-17 | SINNERS         | L   | 0.042      | -            | -                | -                | -         |    -0.27 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            2 |     4651 | 2024-03-16 | ECLOT           | L   | 0.036      | -            | -                | -                | -         |    -0.30 | K1-FiDa, Levi, M1key, NIO, Pechyn     |
|            1 |     4666 | 2024-03-15 | SINNERS         | W   | 0.029      | -            | -                | -                | 1 (0.029) |     0.74 | K1-FiDa, Levi, M1key, NIO, Pechyn     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,007.54)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-13 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-18 |      0.660 | $3,000.00      | $1,979.58       |
| 2024-06-02 |      0.555 | $3,048.00      | $1,692.77       |
| 2024-04-18 |      0.254 | $3,000.00      | $761.25         |
| 2024-04-06 |      0.173 | $3,000.00      | $519.58         |
| 2024-03-17 |      0.043 | $1,279.00      | $54.36          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
