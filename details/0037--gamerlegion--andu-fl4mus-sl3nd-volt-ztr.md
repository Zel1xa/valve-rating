### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.5<br />
<br />
Final Rank Value (1144.5) = Starting Rank Value (1133.5) + Head To Head Adjustments (11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.193[<sup>2</sup>](#table1)

The average of these factors is 0.357<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1133.5
- 400 + ( ( 0.357 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1133.5


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
|           24 |      236 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.32 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      274 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.67 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1064 | 2024-06-15 | 5W                | L   | 0.854      | -            | -                | -                | -         |   -19.43 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1106 | 2024-06-14 | Endpoint          | W   | 0.847      | 0.450        | -                | 0.502 (0.191)    | 0 (0.000) |     4.44 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1136 | 2024-06-13 | Illuminar         | L   | 0.841      | -            | -                | -                | -         |   -21.69 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1311 | 2024-06-08 | 5W                | W   | 0.808      | 0.450        | 0.081 (0.029)    | -                | 0 (0.000) |     5.48 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1368 | 2024-06-07 | MOUZ NXT          | W   | 0.801      | 0.450        | 0.139 (0.050)    | 0.962 (0.347)    | 0 (0.000) |    10.44 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1431 | 2024-06-06 | ECLOT             | W   | 0.795      | 0.450        | 0.061 (0.022)    | 0.537 (0.192)    | 0 (0.000) |    12.20 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1665 | 2024-05-31 | GUN5              | L   | 0.754      | -            | -                | -                | -         |   -18.80 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1872 | 2024-05-22 | Eternal Fire      | L   | 0.694      | -            | -                | -                | -         |    -1.26 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1905 | 2024-05-21 | AMKAL             | W   | 0.688      | 0.769        | 0.130 (0.069)    | 0.452 (0.239)    | 0 (0.000) |    11.71 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     2014 | 2024-05-18 | fnatic            | W   | 0.666      | 0.769        | 0.371 (0.190)    | 0.680 (0.348)    | 0 (0.000) |    18.16 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2035 | 2024-05-17 | Gaimin Gladiators | W   | 0.661      | 0.769        | 0.037 (0.019)    | 0.331 (0.168)    | 0 (0.000) |     6.32 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2338 | 2024-05-07 | Virtus.pro        | L   | 0.595      | -            | -                | -                | -         |    -0.91 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2412 | 2024-05-03 | ENCE              | W   | 0.567      | 0.889        | 0.173 (0.087)    | 0.422 (0.213)    | 1 (0.567) |    14.70 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2430 | 2024-05-02 | FORZE             | W   | 0.561      | 0.889        | 0.057 (0.029)    | 0.164 (0.082)    | 1 (0.561) |     4.65 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2461 | 2024-05-01 | MOUZ              | L   | 0.554      | -            | -                | -                | -         |    -0.29 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2491 | 2024-04-30 | ENCE              | W   | 0.546      | 0.889        | 0.173 (0.084)    | 0.422 (0.205)    | 1 (0.546) |    14.58 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2706 | 2024-04-20 | BIG               | L   | 0.480      | -            | -                | -                | -         |    -4.06 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2794 | 2024-04-18 | Sashi             | L   | 0.467      | -            | -                | -                | -         |    -7.41 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2874 | 2024-04-16 | MOUZ NXT          | W   | 0.453      | 0.384        | 0.139 (0.024)    | 0.962 (0.168)    | -         |     5.85 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3267 | 2024-04-02 | Monte             | L   | 0.361      | -            | -                | -                | -         |    -7.87 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3275 | 2024-04-02 | FAVBET            | L   | 0.360      | -            | -                | -                | -         |    -9.93 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3295 | 2024-04-01 | GUN5              | W   | 0.353      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,307.18)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.866 | $5,000.00      | $4,330.09       |
| 2024-05-23 |      0.700 | $50,000.00     | $35,002.31      |
| 2024-05-12 |      0.627 | $17,500.00     | $10,974.77      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
