### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1147.1<br />
<br />
Final Rank Value (1147.1) = Starting Rank Value (1138.2) + Head To Head Adjustments (8.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.453[<sup>2</sup>](#table1)
- Opponent Network: 0.227[<sup>2</sup>](#table1)
- LAN Wins: 0.197[<sup>2</sup>](#table1)

The average of these factors is 0.361<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1138.2
- 400 + ( ( 0.361 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1138.2


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
|           24 |      167 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.35 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      205 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.69 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |      994 | 2024-06-15 | 5W                | L   | 0.871      | -            | -                | -                | -         |   -19.87 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1036 | 2024-06-14 | Endpoint          | W   | 0.864      | 0.450        | -                | 0.522 (0.203)    | 0 (0.000) |     4.33 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1066 | 2024-06-13 | Illuminar         | L   | 0.858      | -            | -                | -                | -         |   -22.37 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1241 | 2024-06-08 | 5W                | W   | 0.825      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.51 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1298 | 2024-06-07 | MOUZ NXT          | W   | 0.819      | 0.450        | 0.139 (0.051)    | 1.000 (0.368)    | 0 (0.000) |    10.38 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1361 | 2024-06-06 | ECLOT             | W   | 0.812      | 0.450        | 0.063 (0.023)    | 0.559 (0.204)    | 0 (0.000) |    12.11 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1595 | 2024-05-31 | GUN5              | L   | 0.771      | -            | -                | -                | -         |   -19.35 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1802 | 2024-05-22 | Eternal Fire      | L   | 0.711      | -            | -                | -                | -         |    -1.32 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1835 | 2024-05-21 | AMKAL             | W   | 0.705      | 0.769        | 0.130 (0.071)    | 0.477 (0.259)    | 0 (0.000) |    11.91 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1944 | 2024-05-18 | fnatic            | W   | 0.683      | 0.769        | 0.371 (0.195)    | 0.709 (0.372)    | 0 (0.000) |    18.55 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1965 | 2024-05-17 | Gaimin Gladiators | W   | 0.678      | 0.769        | 0.038 (0.020)    | 0.353 (0.184)    | 0 (0.000) |     6.50 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2268 | 2024-05-07 | Virtus.pro        | L   | 0.612      | -            | -                | -                | -         |    -0.95 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2342 | 2024-05-03 | ENCE              | W   | 0.584      | 0.889        | 0.170 (0.088)    | 0.401 (0.208)    | 1 (0.584) |    14.88 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2360 | 2024-05-02 | FORZE             | W   | 0.579      | 0.889        | 0.058 (0.030)    | 0.179 (0.092)    | 1 (0.579) |     4.81 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2391 | 2024-05-01 | MOUZ              | L   | 0.571      | -            | -                | -                | -         |    -0.31 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2421 | 2024-04-30 | ENCE              | W   | 0.564      | 0.889        | 0.170 (0.085)    | 0.401 (0.201)    | 1 (0.564) |    14.82 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2635 | 2024-04-20 | BIG               | L   | 0.497      | -            | -                | -                | -         |    -4.23 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2723 | 2024-04-18 | Sashi             | L   | 0.485      | -            | -                | -                | -         |    -7.87 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2803 | 2024-04-16 | MOUZ NXT          | W   | 0.471      | 0.384        | 0.139 (0.025)    | 1.000 (0.181)    | -         |     5.92 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3196 | 2024-04-02 | Monte             | L   | 0.379      | -            | -                | -                | -         |    -8.22 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3204 | 2024-04-02 | FAVBET            | L   | 0.377      | -            | -                | -                | -         |   -10.47 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3224 | 2024-04-01 | GUN5              | W   | 0.370      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,562.50)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.883 | $5,000.00      | $4,416.67       |
| 2024-05-23 |      0.717 | $50,000.00     | $35,868.06      |
| 2024-05-12 |      0.644 | $17,500.00     | $11,277.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
