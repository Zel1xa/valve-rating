### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../../standings_global_2024_08_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_08_06.md)<br />
Regional Rank: [28]( ../../standings_europe_2024_08_06.md)<br />
<br />
Final Rank Value:  1145.4<br />
<br />
Final Rank Value (1145.4) = Starting Rank Value (1133.9) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.216[<sup>2</sup>](#table1)
- LAN Wins: 0.193[<sup>2</sup>](#table1)

The average of these factors is 0.357<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1133.9
- 400 + ( ( 0.357 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1133.9


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
|           24 |      253 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.34 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      291 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.68 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1081 | 2024-06-15 | 5W                | L   | 0.853      | -            | -                | -                | -         |   -19.41 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1123 | 2024-06-14 | Endpoint          | W   | 0.846      | 0.450        | -                | 0.540 (0.206)    | 0 (0.000) |     4.49 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1153 | 2024-06-13 | Illuminar         | L   | 0.840      | -            | -                | -                | -         |   -21.66 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1328 | 2024-06-08 | 5W                | W   | 0.807      | 0.450        | 0.081 (0.029)    | -                | 0 (0.000) |     5.47 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1385 | 2024-06-07 | MOUZ NXT          | W   | 0.800      | 0.450        | 0.139 (0.050)    | 0.961 (0.346)    | 0 (0.000) |    10.60 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1448 | 2024-06-06 | ECLOT             | W   | 0.794      | 0.450        | 0.061 (0.022)    | 0.537 (0.192)    | 0 (0.000) |    12.20 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1682 | 2024-05-31 | GUN5              | L   | 0.753      | -            | -                | -                | -         |   -18.69 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1889 | 2024-05-22 | Eternal Fire      | L   | 0.693      | -            | -                | -                | -         |    -1.26 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1922 | 2024-05-21 | AMKAL             | W   | 0.687      | 0.769        | 0.130 (0.068)    | 0.452 (0.239)    | 0 (0.000) |    11.72 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     2031 | 2024-05-18 | fnatic            | W   | 0.665      | 0.769        | 0.371 (0.189)    | 0.680 (0.347)    | 0 (0.000) |    18.16 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2052 | 2024-05-17 | Gaimin Gladiators | W   | 0.660      | 0.769        | 0.037 (0.019)    | 0.331 (0.168)    | 0 (0.000) |     6.33 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2355 | 2024-05-07 | Virtus.pro        | L   | 0.594      | -            | -                | -                | -         |    -0.91 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2429 | 2024-05-03 | ENCE              | W   | 0.566      | 0.889        | 0.173 (0.087)    | 0.422 (0.212)    | 1 (0.566) |    14.69 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2447 | 2024-05-02 | FORZE             | W   | 0.560      | 0.889        | 0.057 (0.029)    | 0.163 (0.081)    | 1 (0.560) |     4.64 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2478 | 2024-05-01 | MOUZ              | L   | 0.553      | -            | -                | -                | -         |    -0.29 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2508 | 2024-04-30 | ENCE              | W   | 0.545      | 0.889        | 0.173 (0.084)    | 0.422 (0.204)    | 1 (0.545) |    14.57 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2723 | 2024-04-20 | BIG               | L   | 0.479      | -            | -                | -                | -         |    -4.06 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2811 | 2024-04-18 | Sashi             | L   | 0.467      | -            | -                | -                | -         |    -7.38 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2891 | 2024-04-16 | MOUZ NXT          | W   | 0.453      | 0.384        | 0.139 (0.024)    | 0.961 (0.167)    | -         |     5.88 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3284 | 2024-04-02 | Monte             | L   | 0.360      | -            | -                | -                | -         |    -7.84 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3292 | 2024-04-02 | FAVBET            | L   | 0.359      | -            | -                | -                | -         |    -9.91 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3312 | 2024-04-01 | GUN5              | W   | 0.352      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,243.40)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.865 | $5,000.00      | $4,325.69       |
| 2024-05-23 |      0.699 | $50,000.00     | $34,958.33      |
| 2024-05-12 |      0.626 | $17,500.00     | $10,959.38      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
