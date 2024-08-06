### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1145.8<br />
<br />
Final Rank Value (1145.8) = Starting Rank Value (1135.6) + Head To Head Adjustments (10.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.222[<sup>2</sup>](#table1)
- LAN Wins: 0.194[<sup>2</sup>](#table1)

The average of these factors is 0.359<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1135.6
- 400 + ( ( 0.359 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1135.6


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
|           24 |      230 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.33 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      268 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.68 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |     1058 | 2024-06-15 | 5W                | L   | 0.857      | -            | -                | -                | -         |   -19.55 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |     1100 | 2024-06-14 | Endpoint          | W   | 0.851      | 0.450        | -                | 0.514 (0.197)    | 0 (0.000) |     4.34 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |     1130 | 2024-06-13 | Illuminar         | L   | 0.844      | -            | -                | -                | -         |   -21.89 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1305 | 2024-06-08 | 5W                | W   | 0.811      | 0.450        | 0.081 (0.030)    | -                | 0 (0.000) |     5.46 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1362 | 2024-06-07 | MOUZ NXT          | W   | 0.805      | 0.450        | 0.139 (0.050)    | 0.986 (0.357)    | 0 (0.000) |    10.43 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1425 | 2024-06-06 | ECLOT             | W   | 0.798      | 0.450        | 0.062 (0.022)    | 0.549 (0.197)    | 0 (0.000) |    12.15 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1659 | 2024-05-31 | GUN5              | L   | 0.757      | -            | -                | -                | -         |   -18.92 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1866 | 2024-05-22 | Eternal Fire      | L   | 0.697      | -            | -                | -                | -         |    -1.28 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1899 | 2024-05-21 | AMKAL             | W   | 0.692      | 0.769        | 0.130 (0.069)    | 0.464 (0.247)    | 0 (0.000) |    11.69 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     2008 | 2024-05-18 | fnatic            | W   | 0.669      | 0.769        | 0.371 (0.191)    | 0.696 (0.358)    | 0 (0.000) |    18.24 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     2029 | 2024-05-17 | Gaimin Gladiators | W   | 0.664      | 0.769        | 0.037 (0.019)    | 0.340 (0.174)    | 0 (0.000) |     6.36 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2332 | 2024-05-07 | Virtus.pro        | L   | 0.598      | -            | -                | -                | -         |    -0.92 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2406 | 2024-05-03 | ENCE              | W   | 0.570      | 0.889        | 0.174 (0.088)    | 0.432 (0.219)    | 1 (0.570) |    14.73 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2424 | 2024-05-02 | FORZE             | W   | 0.565      | 0.889        | 0.058 (0.029)    | 0.169 (0.085)    | 1 (0.565) |     4.64 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2455 | 2024-05-01 | MOUZ              | L   | 0.557      | -            | -                | -                | -         |    -0.30 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2485 | 2024-04-30 | ENCE              | W   | 0.550      | 0.889        | 0.174 (0.085)    | 0.432 (0.211)    | 1 (0.550) |    14.63 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2700 | 2024-04-20 | BIG               | L   | 0.483      | -            | -                | -                | -         |    -4.11 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2788 | 2024-04-18 | Sashi             | L   | 0.471      | -            | -                | -                | -         |    -7.51 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2868 | 2024-04-16 | MOUZ NXT          | W   | 0.457      | 0.384        | 0.139 (0.024)    | 0.986 (0.173)    | -         |     5.85 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3261 | 2024-04-02 | Monte             | L   | 0.365      | -            | -                | -                | -         |    -7.97 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3269 | 2024-04-02 | FAVBET            | L   | 0.363      | -            | -                | -                | -         |   -10.05 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3289 | 2024-04-01 | GUN5              | W   | 0.357      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,555.56)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.869 | $5,000.00      | $4,347.22       |
| 2024-05-23 |      0.703 | $50,000.00     | $35,173.61      |
| 2024-05-12 |      0.631 | $17,500.00     | $11,034.72      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
