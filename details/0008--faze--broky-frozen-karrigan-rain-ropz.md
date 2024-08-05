### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1683.5<br />
<br />
Final Rank Value (1683.5) = Starting Rank Value (1680.1) + Head To Head Adjustments (3.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.833[<sup>1</sup>](#table2)
- Bounty Collected: 0.624[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.813[<sup>2</sup>](#table1)

The average of these factors is 0.624<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1680.1
- 400 + ( ( 0.624 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1680.1


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
|           41 |      100 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.71 | broky, frozen, karrigan, rain, ropz |
|           40 |      152 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.22 | broky, frozen, karrigan, rain, ropz |
|           39 |      200 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      569 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.38 | broky, frozen, karrigan, rain, ropz |
|           37 |      717 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | -                | 0.286 (0.286)    | 1 (1.000) |     1.50 | broky, frozen, karrigan, rain, ropz |
|           36 |     1097 | 2024-06-14 | Vitality          | L   | 0.852      | -            | -                | -                | -         |    -8.39 | broky, frozen, karrigan, rain, ropz |
|           35 |     1137 | 2024-06-13 | Natus Vincere     | L   | 0.845      | -            | -                | -                | -         |    -6.73 | broky, frozen, karrigan, rain, ropz |
|           34 |     1169 | 2024-06-12 | SAW               | W   | 0.838      | 0.729        | -                | 0.530 (0.324)    | 1 (0.838) |     1.08 | broky, frozen, karrigan, rain, ropz |
|           33 |     1645 | 2024-05-31 | G2                | L   | 0.761      | -            | -                | -                | -         |    -5.73 | broky, frozen, karrigan, rain, ropz |
|           32 |     1699 | 2024-05-29 | Spirit            | L   | 0.747      | -            | -                | -                | -         |    -6.45 | broky, frozen, karrigan, rain, ropz |
|           31 |     1722 | 2024-05-28 | Virtus.pro        | W   | 0.740      | 0.624        | 0.498 (0.230)    | 0.317 (0.146)    | 1 (0.740) |     9.46 | broky, frozen, karrigan, rain, ropz |
|           30 |     1746 | 2024-05-27 | M80               | W   | 0.734      | 0.624        | -                | 0.577 (0.264)    | 1 (0.734) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2271 | 2024-05-10 | Vitality          | L   | 0.620      | -            | -                | -                | -         |    -6.54 | broky, frozen, karrigan, rain, ropz |
|           28 |     2313 | 2024-05-08 | Natus Vincere     | W   | 0.607      | 0.889        | 1.000 (0.539)    | 0.365 (0.197)    | 1 (0.607) |    14.95 | broky, frozen, karrigan, rain, ropz |
|           27 |     2331 | 2024-05-07 | Monte             | W   | 0.600      | -            | -                | -                | 1 (0.600) |     0.36 | broky, frozen, karrigan, rain, ropz |
|           26 |     2563 | 2024-04-26 | Eternal Fire      | W   | 0.526      | 0.889        | 0.740 (0.346)    | 0.449 (0.210)    | 1 (0.526) |     7.74 | broky, frozen, karrigan, rain, ropz |
|           25 |     2592 | 2024-04-25 | Virtus.pro        | W   | 0.520      | 0.889        | 0.498 (0.230)    | -                | 1 (0.520) |     7.42 | broky, frozen, karrigan, rain, ropz |
|           24 |     2611 | 2024-04-24 | Astralis          | L   | 0.513      | -            | -                | -                | -         |    -7.58 | broky, frozen, karrigan, rain, ropz |
|           23 |     2629 | 2024-04-23 | Imperial          | W   | 0.506      | 0.889        | 0.234 (0.106)    | 0.674 (0.304)    | 1 (0.506) |     1.39 | broky, frozen, karrigan, rain, ropz |
|           22 |     2904 | 2024-04-14 | MOUZ              | W   | 0.444      | 0.624        | 1.000 (0.277)    | -                | -         |     9.85 | broky, frozen, karrigan, rain, ropz |
|           21 |     2918 | 2024-04-13 | Astralis          | W   | 0.438      | 0.624        | 0.389 (0.106)    | -                | -         |     7.55 | broky, frozen, karrigan, rain, ropz |
|           20 |     2932 | 2024-04-12 | Liquid            | W   | 0.431      | -            | -                | -                | -         |     5.01 | broky, frozen, karrigan, rain, ropz |
|           19 |     3005 | 2024-04-10 | FlyQuest          | W   | 0.418      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3021 | 2024-04-09 | Cloud9            | W   | 0.416      | -            | -                | -                | -         |     0.39 | broky, frozen, karrigan, rain, ropz |
|           17 |     3066 | 2024-04-09 | Astralis          | L   | 0.411      | -            | -                | -                | -         |    -5.96 | broky, frozen, karrigan, rain, ropz |
|           16 |     3097 | 2024-04-08 | Nemiga            | W   | 0.404      | 0.624        | -                | 0.722 (0.182)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3291 | 2024-03-31 | Natus Vincere     | L   | 0.353      | -            | -                | -                | -         |    -1.95 | broky, frozen, karrigan, rain, ropz |
|           14 |     3297 | 2024-03-30 | Vitality          | W   | 0.346      | 1.000        | 0.648 (0.224)    | -                | -         |     7.74 | broky, frozen, karrigan, rain, ropz |
|           13 |     3317 | 2024-03-28 | Spirit            | W   | 0.333      | 1.000        | 1.000 (0.333)    | 0.452 (0.151)    | -         |     8.19 | broky, frozen, karrigan, rain, ropz |
|           12 |     3401 | 2024-03-24 | Complexity        | W   | 0.305      | 1.000        | 0.342 (0.104)    | -                | -         |     4.38 | broky, frozen, karrigan, rain, ropz |
|           11 |     3415 | 2024-03-23 | Imperial          | W   | 0.298      | 1.000        | -                | 0.674 (0.201)    | -         |     0.86 | broky, frozen, karrigan, rain, ropz |
|           10 |     3429 | 2024-03-22 | Eternal Fire      | L   | 0.292      | -            | -                | -                | -         |    -4.32 | broky, frozen, karrigan, rain, ropz |
|            9 |     3439 | 2024-03-21 | FURIA             | W   | 0.287      | -            | -                | -                | -         |     4.92 | broky, frozen, karrigan, rain, ropz |
|            8 |     3451 | 2024-03-21 | HEROIC            | L   | 0.286      | -            | -                | -                | -         |    -5.89 | broky, frozen, karrigan, rain, ropz |
|            7 |     4243 | 2024-02-16 | Eternal Fire      | W   | 0.059      | -            | -                | -                | -         |     0.96 | broky, frozen, karrigan, rain, ropz |
|            6 |     4269 | 2024-02-15 | G2                | L   | 0.052      | -            | -                | -                | -         |    -0.23 | broky, frozen, karrigan, rain, ropz |
|            5 |     4302 | 2024-02-14 | Falcons           | W   | 0.046      | -            | -                | -                | -         |     0.28 | broky, frozen, karrigan, rain, ropz |
|            4 |     4318 | 2024-02-14 | 9 Pandas          | W   | 0.045      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4356 | 2024-02-11 | Spirit            | L   | 0.026      | -            | -                | -                | -         |    -0.18 | broky, frozen, karrigan, rain, ropz |
|            2 |     4367 | 2024-02-10 | MOUZ              | W   | 0.019      | -            | -                | -                | -         |     0.43 | broky, frozen, karrigan, rain, ropz |
|            1 |     4381 | 2024-02-09 | G2                | W   | 0.012      | -            | -                | -                | -         |     0.34 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($202,940.65)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.63) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.865 | $20,000.00     | $17,308.33      |
| 2024-06-02 |      0.773 | $10,000.00     | $7,731.94       |
| 2024-05-12 |      0.632 | $32,000.00     | $20,235.56      |
| 2024-04-14 |      0.444 | $100,000.00    | $44,446.76      |
| 2024-03-31 |      0.353 | $170,000.00    | $60,043.06      |
| 2024-02-11 |      0.026 | $180,000.00    | $4,675.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
