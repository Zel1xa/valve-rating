### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1147.2<br />
<br />
Final Rank Value (1147.2) = Starting Rank Value (1137.9) + Head To Head Adjustments (9.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.195[<sup>2</sup>](#table1)

The average of these factors is 0.361<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1137.9
- 400 + ( ( 0.361 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1137.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      206 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.31 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      244 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.68 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1034 | 2024-06-15 | 5W                | L   | 0.864      | -            | -                | -                | -         |   -19.73 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1076 | 2024-06-14 | Endpoint          | W   | 0.857      | 0.450        | -                | 0.522 (0.201)    | 0 (0.000) |     4.32 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1106 | 2024-06-13 | Illuminar         | L   | 0.851      | -            | -                | -                | -         |   -22.15 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1281 | 2024-06-08 | 5W                | W   | 0.818      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.46 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1338 | 2024-06-07 | MOUZ NXT          | W   | 0.811      | 0.450        | 0.139 (0.051)    | 1.000 (0.365)    | 0 (0.000) |    10.32 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1401 | 2024-06-06 | ECLOT             | W   | 0.805      | 0.450        | 0.062 (0.023)    | 0.558 (0.202)    | 0 (0.000) |    12.12 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1635 | 2024-05-31 | GUN5              | L   | 0.764      | -            | -                | -                | -         |   -19.14 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1842 | 2024-05-22 | Eternal Fire      | L   | 0.704      | -            | -                | -                | -         |    -1.30 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1875 | 2024-05-21 | AMKAL             | W   | 0.698      | 0.769        | 0.130 (0.070)    | 0.474 (0.254)    | 0 (0.000) |    11.77 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1984 | 2024-05-18 | fnatic            | W   | 0.676      | 0.769        | 0.371 (0.192)    | 0.708 (0.368)    | 0 (0.000) |    18.39 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2005 | 2024-05-17 | Gaimin Gladiators | W   | 0.671      | 0.769        | 0.038 (0.019)    | 0.349 (0.180)    | 0 (0.000) |     6.43 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2308 | 2024-05-07 | Virtus.pro        | L   | 0.605      | -            | -                | -                | -         |    -0.93 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2382 | 2024-05-03 | ENCE              | W   | 0.577      | 0.889        | 0.168 (0.086)    | 0.439 (0.225)    | 1 (0.577) |    14.82 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2400 | 2024-05-02 | FORZE             | W   | 0.571      | 0.889        | 0.058 (0.029)    | 0.175 (0.089)    | 1 (0.571) |     4.70 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2431 | 2024-05-01 | MOUZ              | L   | 0.564      | -            | -                | -                | -         |    -0.30 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2461 | 2024-04-30 | ENCE              | W   | 0.556      | 0.889        | 0.168 (0.083)    | 0.439 (0.217)    | 1 (0.556) |    14.73 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2676 | 2024-04-20 | BIG               | L   | 0.490      | -            | -                | -                | -         |    -4.19 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2764 | 2024-04-18 | Sashi             | L   | 0.477      | -            | -                | -                | -         |    -7.68 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2844 | 2024-04-16 | MOUZ NXT          | W   | 0.464      | 0.384        | 0.139 (0.025)    | 1.000 (0.178)    | -         |     5.84 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3237 | 2024-04-02 | Monte             | L   | 0.371      | -            | -                | -                | -         |    -8.12 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3245 | 2024-04-02 | FAVBET            | L   | 0.370      | -            | -                | -                | -         |   -10.26 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3265 | 2024-04-01 | GUN5              | W   | 0.363      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,038.89)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.876 | $5,000.00      | $4,380.56       |
| 2024-05-23 |      0.710 | $50,000.00     | $35,506.94      |
| 2024-05-12 |      0.637 | $17,500.00     | $11,151.39      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
