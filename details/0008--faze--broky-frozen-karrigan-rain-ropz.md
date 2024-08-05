### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1683.7<br />
<br />
Final Rank Value (1683.7) = Starting Rank Value (1680.3) + Head To Head Adjustments (3.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.833[<sup>1</sup>](#table2)
- Bounty Collected: 0.624[<sup>2</sup>](#table1)
- Opponent Network: 0.227[<sup>2</sup>](#table1)
- LAN Wins: 0.814[<sup>2</sup>](#table1)

The average of these factors is 0.624<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1680.3
- 400 + ( ( 0.624 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1680.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       99 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.71 | broky, frozen, karrigan, rain, ropz |
|           40 |      151 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.22 | broky, frozen, karrigan, rain, ropz |
|           39 |      199 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      568 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.39 | broky, frozen, karrigan, rain, ropz |
|           37 |      716 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | -                | 0.286 (0.286)    | 1 (1.000) |     1.50 | broky, frozen, karrigan, rain, ropz |
|           36 |     1096 | 2024-06-14 | Vitality          | L   | 0.853      | -            | -                | -                | -         |    -8.40 | broky, frozen, karrigan, rain, ropz |
|           35 |     1136 | 2024-06-13 | Natus Vincere     | L   | 0.846      | -            | -                | -                | -         |    -6.74 | broky, frozen, karrigan, rain, ropz |
|           34 |     1168 | 2024-06-12 | SAW               | W   | 0.838      | 0.729        | -                | 0.530 (0.324)    | 1 (0.838) |     1.08 | broky, frozen, karrigan, rain, ropz |
|           33 |     1644 | 2024-05-31 | G2                | L   | 0.761      | -            | -                | -                | -         |    -5.74 | broky, frozen, karrigan, rain, ropz |
|           32 |     1698 | 2024-05-29 | Spirit            | L   | 0.748      | -            | -                | -                | -         |    -6.46 | broky, frozen, karrigan, rain, ropz |
|           31 |     1721 | 2024-05-28 | Virtus.pro        | W   | 0.741      | 0.624        | 0.498 (0.230)    | 0.317 (0.147)    | 1 (0.741) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           30 |     1745 | 2024-05-27 | M80               | W   | 0.734      | 0.624        | -                | 0.577 (0.264)    | 1 (0.734) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2270 | 2024-05-10 | Vitality          | L   | 0.620      | -            | -                | -                | -         |    -6.55 | broky, frozen, karrigan, rain, ropz |
|           28 |     2312 | 2024-05-08 | Natus Vincere     | W   | 0.607      | 0.889        | 1.000 (0.540)    | 0.365 (0.197)    | 1 (0.607) |    14.96 | broky, frozen, karrigan, rain, ropz |
|           27 |     2330 | 2024-05-07 | Monte             | W   | 0.600      | -            | -                | -                | 1 (0.600) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           26 |     2562 | 2024-04-26 | Eternal Fire      | W   | 0.526      | 0.889        | 0.740 (0.346)    | 0.449 (0.210)    | 1 (0.526) |     7.74 | broky, frozen, karrigan, rain, ropz |
|           25 |     2591 | 2024-04-25 | Virtus.pro        | W   | 0.520      | 0.889        | 0.498 (0.230)    | -                | 1 (0.520) |     7.42 | broky, frozen, karrigan, rain, ropz |
|           24 |     2610 | 2024-04-24 | Astralis          | L   | 0.513      | -            | -                | -                | -         |    -7.59 | broky, frozen, karrigan, rain, ropz |
|           23 |     2628 | 2024-04-23 | Imperial          | W   | 0.507      | 0.889        | 0.235 (0.106)    | 0.674 (0.304)    | 1 (0.507) |     1.39 | broky, frozen, karrigan, rain, ropz |
|           22 |     2903 | 2024-04-14 | MOUZ              | W   | 0.445      | 0.624        | 1.000 (0.278)    | -                | -         |     9.86 | broky, frozen, karrigan, rain, ropz |
|           21 |     2917 | 2024-04-13 | Astralis          | W   | 0.438      | 0.624        | 0.389 (0.107)    | -                | -         |     7.55 | broky, frozen, karrigan, rain, ropz |
|           20 |     2931 | 2024-04-12 | Liquid            | W   | 0.431      | -            | -                | -                | -         |     5.01 | broky, frozen, karrigan, rain, ropz |
|           19 |     3004 | 2024-04-10 | FlyQuest          | W   | 0.418      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3020 | 2024-04-09 | Cloud9            | W   | 0.417      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           17 |     3065 | 2024-04-09 | Astralis          | L   | 0.411      | -            | -                | -                | -         |    -5.97 | broky, frozen, karrigan, rain, ropz |
|           16 |     3096 | 2024-04-08 | Nemiga            | W   | 0.404      | 0.624        | -                | 0.722 (0.182)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3290 | 2024-03-31 | Natus Vincere     | L   | 0.354      | -            | -                | -                | -         |    -1.95 | broky, frozen, karrigan, rain, ropz |
|           14 |     3296 | 2024-03-30 | Vitality          | W   | 0.346      | 1.000        | 0.648 (0.224)    | -                | -         |     7.75 | broky, frozen, karrigan, rain, ropz |
|           13 |     3316 | 2024-03-28 | Spirit            | W   | 0.334      | 1.000        | 1.000 (0.334)    | 0.452 (0.151)    | -         |     8.20 | broky, frozen, karrigan, rain, ropz |
|           12 |     3400 | 2024-03-24 | Complexity        | W   | 0.305      | 1.000        | 0.342 (0.104)    | -                | -         |     4.38 | broky, frozen, karrigan, rain, ropz |
|           11 |     3414 | 2024-03-23 | Imperial          | W   | 0.299      | 1.000        | -                | 0.674 (0.201)    | -         |     0.86 | broky, frozen, karrigan, rain, ropz |
|           10 |     3428 | 2024-03-22 | Eternal Fire      | L   | 0.292      | -            | -                | -                | -         |    -4.32 | broky, frozen, karrigan, rain, ropz |
|            9 |     3438 | 2024-03-21 | FURIA             | W   | 0.288      | -            | -                | -                | -         |     4.92 | broky, frozen, karrigan, rain, ropz |
|            8 |     3450 | 2024-03-21 | HEROIC            | L   | 0.286      | -            | -                | -                | -         |    -5.90 | broky, frozen, karrigan, rain, ropz |
|            7 |     4242 | 2024-02-16 | Eternal Fire      | W   | 0.059      | -            | -                | -                | -         |     0.97 | broky, frozen, karrigan, rain, ropz |
|            6 |     4268 | 2024-02-15 | G2                | L   | 0.052      | -            | -                | -                | -         |    -0.24 | broky, frozen, karrigan, rain, ropz |
|            5 |     4301 | 2024-02-14 | Falcons           | W   | 0.047      | -            | -                | -                | -         |     0.28 | broky, frozen, karrigan, rain, ropz |
|            4 |     4317 | 2024-02-14 | 9 Pandas          | W   | 0.045      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4355 | 2024-02-11 | Spirit            | L   | 0.026      | -            | -                | -                | -         |    -0.18 | broky, frozen, karrigan, rain, ropz |
|            2 |     4366 | 2024-02-10 | MOUZ              | W   | 0.020      | -            | -                | -                | -         |     0.44 | broky, frozen, karrigan, rain, ropz |
|            1 |     4380 | 2024-02-09 | G2                | W   | 0.013      | -            | -                | -                | -         |     0.35 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($203,153.98)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.63) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.866 | $20,000.00     | $17,316.67      |
| 2024-06-02 |      0.774 | $10,000.00     | $7,736.11       |
| 2024-05-12 |      0.633 | $32,000.00     | $20,248.89      |
| 2024-04-14 |      0.445 | $100,000.00    | $44,488.43      |
| 2024-03-31 |      0.354 | $170,000.00    | $60,113.89      |
| 2024-02-11 |      0.026 | $180,000.00    | $4,750.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
