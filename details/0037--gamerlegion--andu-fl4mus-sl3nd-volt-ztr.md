### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1150.7<br />
<br />
Final Rank Value (1150.7) = Starting Rank Value (1145.8) + Head To Head Adjustments (4.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.570[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.362<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.8
- 400 + ( ( 0.362 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1145.8


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
|           24 |       81 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.12 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      120 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.71 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |      923 | 2024-06-15 | 5W                | L   | 0.887      | -            | -                | -                | -         |   -20.16 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |      957 | 2024-06-14 | Endpoint          | W   | 0.881      | 0.450        | -                | 0.555 (0.220)    | 0 (0.000) |     4.99 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |      988 | 2024-06-13 | Illuminar         | L   | 0.875      | -            | -                | -                | -         |   -22.40 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1167 | 2024-06-08 | 5W                | W   | 0.842      | 0.450        | 0.082 (0.031)    | -                | 0 (0.000) |     5.72 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1231 | 2024-06-07 | MOUZ NXT          | W   | 0.835      | 0.450        | 0.141 (0.053)    | 1.000 (0.376)    | 0 (0.000) |    10.92 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1296 | 2024-06-06 | ECLOT             | W   | 0.828      | 0.450        | 0.064 (0.024)    | 0.501 (0.187)    | 0 (0.000) |     9.82 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1534 | 2024-05-31 | GUN5              | L   | 0.788      | -            | -                | -                | -         |   -19.26 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1743 | 2024-05-22 | Eternal Fire      | L   | 0.727      | -            | -                | -                | -         |    -1.28 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1790 | 2024-05-21 | AMKAL             | W   | 0.722      | 0.769        | 0.132 (0.073)    | 0.482 (0.268)    | 0 (0.000) |    12.07 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1911 | 2024-05-18 | fnatic            | W   | 0.699      | 0.769        | 0.292 (0.157)    | 0.529 (0.285)    | 0 (0.000) |    15.81 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1932 | 2024-05-17 | Gaimin Gladiators | W   | 0.694      | 0.769        | 0.040 (0.021)    | 0.361 (0.193)    | 0 (0.000) |     6.86 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2246 | 2024-05-07 | Virtus.pro        | L   | 0.628      | -            | -                | -                | -         |    -0.98 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2320 | 2024-05-03 | ENCE              | W   | 0.601      | 0.889        | 0.174 (0.093)    | 0.403 (0.215)    | 1 (0.601) |    15.35 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2338 | 2024-05-02 | FORZE             | W   | 0.595      | 0.889        | 0.060 (0.032)    | 0.186 (0.099)    | 1 (0.595) |     5.05 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2371 | 2024-05-01 | MOUZ              | L   | 0.587      | -            | -                | -                | -         |    -0.28 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2402 | 2024-04-30 | ENCE              | W   | 0.580      | 0.889        | 0.174 (0.090)    | 0.403 (0.208)    | 1 (0.580) |    15.31 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2623 | 2024-04-20 | BIG               | L   | 0.514      | -            | -                | -                | -         |    -5.86 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2713 | 2024-04-18 | Sashi             | L   | 0.501      | -            | -                | -                | -         |    -8.16 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2795 | 2024-04-16 | MOUZ NXT          | W   | 0.487      | 0.384        | 0.141 (0.026)    | 1.000 (0.187)    | -         |     6.33 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3197 | 2024-04-02 | Monte             | L   | 0.395      | -            | -                | -                | -         |    -8.45 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3205 | 2024-04-02 | FAVBET            | L   | 0.394      | -            | -                | -                | -         |   -10.93 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3225 | 2024-04-01 | GUN5              | W   | 0.387      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($57,750.69)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-01 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.900 | $5,000.00      | $4,498.61       |
| 2024-05-23 |      0.734 | $50,000.00     | $36,687.50      |
| 2024-05-12 |      0.661 | $17,500.00     | $11,564.58      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
