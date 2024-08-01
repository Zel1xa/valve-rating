### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1150.1<br />
<br />
Final Rank Value (1150.1) = Starting Rank Value (1145.4) + Head To Head Adjustments (4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.570[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.204[<sup>2</sup>](#table1)

The average of these factors is 0.362<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.4
- 400 + ( ( 0.362 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1145.4


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
|           24 |       88 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.11 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      126 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.71 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |      929 | 2024-06-15 | 5W                | L   | 0.886      | -            | -                | -                | -         |   -20.14 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |      963 | 2024-06-14 | Endpoint          | W   | 0.879      | 0.450        | -                | 0.555 (0.220)    | 0 (0.000) |     4.98 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |      994 | 2024-06-13 | Illuminar         | L   | 0.873      | -            | -                | -                | -         |   -22.36 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1173 | 2024-06-08 | 5W                | W   | 0.840      | 0.450        | 0.082 (0.031)    | -                | 0 (0.000) |     5.71 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1237 | 2024-06-07 | MOUZ NXT          | W   | 0.833      | 0.450        | 0.141 (0.053)    | 1.000 (0.375)    | 0 (0.000) |    10.89 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1302 | 2024-06-06 | ECLOT             | W   | 0.827      | 0.450        | 0.064 (0.024)    | 0.501 (0.186)    | 0 (0.000) |     9.77 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1540 | 2024-05-31 | GUN5              | L   | 0.786      | -            | -                | -                | -         |   -19.22 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1749 | 2024-05-22 | Eternal Fire      | L   | 0.726      | -            | -                | -                | -         |    -1.28 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1796 | 2024-05-21 | AMKAL             | W   | 0.720      | 0.769        | 0.132 (0.073)    | 0.482 (0.267)    | 0 (0.000) |    12.06 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1917 | 2024-05-18 | fnatic            | W   | 0.698      | 0.769        | 0.292 (0.157)    | 0.568 (0.304)    | 0 (0.000) |    15.76 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1938 | 2024-05-17 | Gaimin Gladiators | W   | 0.693      | 0.769        | 0.040 (0.021)    | 0.360 (0.192)    | 0 (0.000) |     6.82 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2252 | 2024-05-07 | Virtus.pro        | L   | 0.627      | -            | -                | -                | -         |    -0.98 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2326 | 2024-05-03 | ENCE              | W   | 0.599      | 0.889        | 0.173 (0.092)    | 0.403 (0.215)    | 1 (0.599) |    15.30 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2344 | 2024-05-02 | FORZE             | W   | 0.593      | 0.889        | 0.060 (0.032)    | 0.186 (0.098)    | 1 (0.593) |     5.02 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2377 | 2024-05-01 | MOUZ              | L   | 0.586      | -            | -                | -                | -         |    -0.28 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2408 | 2024-04-30 | ENCE              | W   | 0.578      | 0.889        | 0.173 (0.089)    | 0.403 (0.207)    | 1 (0.578) |    15.26 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2629 | 2024-04-20 | BIG               | L   | 0.512      | -            | -                | -                | -         |    -5.86 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2719 | 2024-04-18 | Sashi             | L   | 0.499      | -            | -                | -                | -         |    -8.14 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2801 | 2024-04-16 | MOUZ NXT          | W   | 0.485      | 0.384        | 0.141 (0.026)    | 1.000 (0.187)    | -         |     6.29 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3203 | 2024-04-02 | Monte             | L   | 0.393      | -            | -                | -                | -         |    -8.43 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3211 | 2024-04-02 | FAVBET            | L   | 0.392      | -            | -                | -                | -         |   -10.88 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3231 | 2024-04-01 | GUN5              | W   | 0.385      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($57,629.86)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-01 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.898 | $5,000.00      | $4,490.28       |
| 2024-05-23 |      0.732 | $50,000.00     | $36,604.17      |
| 2024-05-12 |      0.659 | $17,500.00     | $11,535.42      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
