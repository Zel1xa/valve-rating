### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1149.4<br />
<br />
Final Rank Value (1149.4) = Starting Rank Value (1144.4) + Head To Head Adjustments (5.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.570[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.223[<sup>2</sup>](#table1)
- LAN Wins: 0.204[<sup>2</sup>](#table1)

The average of these factors is 0.362<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1144.4
- 400 + ( ( 0.362 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1144.4


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
|           24 |       85 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -5.09 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |      124 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.71 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |      927 | 2024-06-15 | 5W                | L   | 0.886      | -            | -                | -                | -         |   -20.12 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |      961 | 2024-06-14 | Endpoint          | W   | 0.879      | 0.450        | -                | 0.555 (0.220)    | 0 (0.000) |     5.00 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |      992 | 2024-06-13 | Illuminar         | L   | 0.873      | -            | -                | -                | -         |   -22.35 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1171 | 2024-06-08 | 5W                | W   | 0.840      | 0.450        | 0.082 (0.031)    | -                | 0 (0.000) |     5.73 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1235 | 2024-06-07 | MOUZ NXT          | W   | 0.834      | 0.450        | 0.141 (0.053)    | 1.000 (0.375)    | 0 (0.000) |    10.92 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1300 | 2024-06-06 | ECLOT             | W   | 0.827      | 0.450        | 0.064 (0.024)    | 0.501 (0.187)    | 0 (0.000) |     9.81 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1538 | 2024-05-31 | GUN5              | L   | 0.786      | -            | -                | -                | -         |   -19.21 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1747 | 2024-05-22 | Eternal Fire      | L   | 0.726      | -            | -                | -                | -         |    -1.28 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1794 | 2024-05-21 | AMKAL             | W   | 0.720      | 0.769        | 0.132 (0.073)    | 0.482 (0.267)    | 0 (0.000) |    12.08 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1915 | 2024-05-18 | fnatic            | W   | 0.698      | 0.769        | 0.292 (0.157)    | 0.529 (0.284)    | 0 (0.000) |    15.79 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1936 | 2024-05-17 | Gaimin Gladiators | W   | 0.693      | 0.769        | 0.040 (0.021)    | 0.360 (0.192)    | 0 (0.000) |     6.85 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2250 | 2024-05-07 | Virtus.pro        | L   | 0.627      | -            | -                | -                | -         |    -0.98 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2324 | 2024-05-03 | ENCE              | W   | 0.599      | 0.889        | 0.174 (0.092)    | 0.403 (0.215)    | 1 (0.599) |    15.31 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2342 | 2024-05-02 | FORZE             | W   | 0.594      | 0.889        | 0.060 (0.032)    | 0.186 (0.098)    | 1 (0.594) |     5.04 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2375 | 2024-05-01 | MOUZ              | L   | 0.586      | -            | -                | -                | -         |    -0.28 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2406 | 2024-04-30 | ENCE              | W   | 0.579      | 0.889        | 0.174 (0.089)    | 0.403 (0.207)    | 1 (0.579) |    15.27 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2627 | 2024-04-20 | BIG               | L   | 0.512      | -            | -                | -                | -         |    -5.85 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2717 | 2024-04-18 | Sashi             | L   | 0.500      | -            | -                | -                | -         |    -8.13 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2799 | 2024-04-16 | MOUZ NXT          | W   | 0.486      | 0.384        | 0.141 (0.026)    | 1.000 (0.187)    | -         |     6.32 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3201 | 2024-04-02 | Monte             | L   | 0.394      | -            | -                | -                | -         |    -8.42 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3209 | 2024-04-02 | FAVBET            | L   | 0.392      | -            | -                | -                | -         |   -10.88 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3229 | 2024-04-01 | GUN5              | W   | 0.385      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($57,650.00)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-01 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.898 | $5,000.00      | $4,491.67       |
| 2024-05-23 |      0.732 | $50,000.00     | $36,618.06      |
| 2024-05-12 |      0.659 | $17,500.00     | $11,540.28      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
