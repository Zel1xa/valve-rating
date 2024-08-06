### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.6<br />
<br />
Final Rank Value (1144.6) = Starting Rank Value (1133.7) + Head To Head Adjustments (10.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.193[<sup>2</sup>](#table1)

The average of these factors is 0.357<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1133.7
- 400 + ( ( 0.357 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1133.7


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
|           24 |      238 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.31 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      276 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.67 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1066 | 2024-06-15 | 5W                | L   | 0.854      | -            | -                | -                | -         |   -19.44 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1108 | 2024-06-14 | Endpoint          | W   | 0.848      | 0.450        | -                | 0.502 (0.191)    | 0 (0.000) |     4.37 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1138 | 2024-06-13 | Illuminar         | L   | 0.842      | -            | -                | -                | -         |   -21.78 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1313 | 2024-06-08 | 5W                | W   | 0.809      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.48 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1370 | 2024-06-07 | MOUZ NXT          | W   | 0.802      | 0.450        | 0.139 (0.050)    | 0.962 (0.347)    | 0 (0.000) |    10.45 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1433 | 2024-06-06 | ECLOT             | W   | 0.795      | 0.450        | 0.061 (0.022)    | 0.537 (0.192)    | 0 (0.000) |    12.19 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1667 | 2024-05-31 | GUN5              | L   | 0.755      | -            | -                | -                | -         |   -18.82 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1874 | 2024-05-22 | Eternal Fire      | L   | 0.694      | -            | -                | -                | -         |    -1.26 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1907 | 2024-05-21 | AMKAL             | W   | 0.689      | 0.769        | 0.130 (0.069)    | 0.453 (0.240)    | 0 (0.000) |    11.72 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     2016 | 2024-05-18 | fnatic            | W   | 0.666      | 0.769        | 0.371 (0.190)    | 0.680 (0.348)    | 0 (0.000) |    18.18 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2037 | 2024-05-17 | Gaimin Gladiators | W   | 0.661      | 0.769        | 0.037 (0.019)    | 0.331 (0.169)    | 0 (0.000) |     6.35 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2340 | 2024-05-07 | Virtus.pro        | L   | 0.595      | -            | -                | -                | -         |    -0.91 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2414 | 2024-05-03 | ENCE              | W   | 0.568      | 0.889        | 0.173 (0.087)    | 0.422 (0.213)    | 1 (0.568) |    14.72 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2432 | 2024-05-02 | FORZE             | W   | 0.562      | 0.889        | 0.057 (0.029)    | 0.164 (0.082)    | 1 (0.562) |     4.64 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2463 | 2024-05-01 | MOUZ              | L   | 0.554      | -            | -                | -                | -         |    -0.29 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2493 | 2024-04-30 | ENCE              | W   | 0.547      | 0.889        | 0.173 (0.084)    | 0.422 (0.205)    | 1 (0.547) |    14.60 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2708 | 2024-04-20 | BIG               | L   | 0.481      | -            | -                | -                | -         |    -4.07 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2796 | 2024-04-18 | Sashi             | L   | 0.468      | -            | -                | -                | -         |    -7.42 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2876 | 2024-04-16 | MOUZ NXT          | W   | 0.454      | 0.384        | 0.139 (0.024)    | 0.962 (0.168)    | -         |     5.86 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3269 | 2024-04-02 | Monte             | L   | 0.362      | -            | -                | -                | -         |    -7.89 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3277 | 2024-04-02 | FAVBET            | L   | 0.361      | -            | -                | -                | -         |    -9.96 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3297 | 2024-04-01 | GUN5              | W   | 0.354      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,354.17)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.867 | $5,000.00      | $4,333.33       |
| 2024-05-23 |      0.701 | $50,000.00     | $35,034.72      |
| 2024-05-12 |      0.628 | $17,500.00     | $10,986.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
