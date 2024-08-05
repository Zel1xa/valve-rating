### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, volt, ztr<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1157.6<br />
<br />
Final Rank Value (1157.6) = Starting Rank Value (1153.2) + Head To Head Adjustments (4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.569[<sup>1</sup>](#table2)
- Bounty Collected: 0.456[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1153.2
- 400 + ( ( 0.365 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1153.2


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
|           24 |       53 | 2024-07-30 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -4.96 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           23 |       91 | 2024-07-29 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -0.68 | aNdu, FL4MUS, sl3nd, volt, ztr  |
|           22 |      881 | 2024-06-15 | 5W                | L   | 0.892      | -            | -                | -                | -         |   -20.46 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           21 |      923 | 2024-06-14 | Endpoint          | W   | 0.885      | 0.450        | -                | 0.523 (0.208)    | 0 (0.000) |     4.28 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           20 |      953 | 2024-06-13 | Illuminar         | L   | 0.879      | -            | -                | -                | -         |   -23.03 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           19 |     1128 | 2024-06-08 | 5W                | W   | 0.846      | 0.450        | 0.082 (0.031)    | -                | 0 (0.000) |     5.55 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           18 |     1185 | 2024-06-07 | MOUZ NXT          | W   | 0.839      | 0.450        | 0.140 (0.053)    | 1.000 (0.378)    | 0 (0.000) |    10.41 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           17 |     1248 | 2024-06-06 | ECLOT             | W   | 0.833      | 0.450        | 0.064 (0.024)    | 0.502 (0.188)    | 0 (0.000) |     9.57 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           16 |     1482 | 2024-05-31 | GUN5              | L   | 0.792      | -            | -                | -                | -         |   -20.22 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           15 |     1689 | 2024-05-22 | Eternal Fire      | L   | 0.732      | -            | -                | -                | -         |    -1.28 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |     1722 | 2024-05-21 | AMKAL             | W   | 0.726      | 0.769        | 0.131 (0.073)    | 0.484 (0.270)    | 0 (0.000) |    12.15 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |     1831 | 2024-05-18 | fnatic            | W   | 0.704      | 0.769        | 0.371 (0.201)    | 0.633 (0.342)    | 0 (0.000) |    19.19 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |     1852 | 2024-05-17 | Gaimin Gladiators | W   | 0.699      | 0.769        | 0.040 (0.021)    | 0.363 (0.195)    | 0 (0.000) |     6.75 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     2155 | 2024-05-07 | Virtus.pro        | L   | 0.633      | -            | -                | -                | -         |    -0.91 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     2229 | 2024-05-03 | ENCE              | W   | 0.605      | 0.889        | 0.173 (0.093)    | 0.404 (0.217)    | 1 (0.605) |    15.51 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     2247 | 2024-05-02 | FORZE             | W   | 0.599      | 0.889        | 0.060 (0.032)    | 0.188 (0.100)    | 1 (0.599) |     5.02 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2278 | 2024-05-01 | MOUZ              | L   | 0.592      | -            | -                | -                | -         |    -0.29 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2308 | 2024-04-30 | ENCE              | W   | 0.584      | 0.889        | 0.173 (0.090)    | 0.404 (0.210)    | 1 (0.584) |    15.47 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2523 | 2024-04-20 | BIG               | L   | 0.518      | -            | -                | -                | -         |    -5.75 | aNdu, Goody, sl3nd, Snax, volt  |
|            5 |     2611 | 2024-04-18 | Sashi             | L   | 0.505      | -            | -                | -                | -         |    -8.36 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2691 | 2024-04-16 | MOUZ NXT          | W   | 0.491      | 0.384        | 0.140 (0.026)    | 1.000 (0.189)    | -         |     6.03 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3084 | 2024-04-02 | Monte             | L   | 0.399      | -            | -                | -                | -         |    -8.62 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3092 | 2024-04-02 | FAVBET            | L   | 0.398      | -            | -                | -                | -         |   -11.10 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3112 | 2024-04-01 | GUN5              | W   | 0.391      | -            | -                | -                | -         |     0.18 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58,065.20)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-17 |      0.904 | $5,000.00      | $4,520.30       |
| 2024-05-23 |      0.738 | $50,000.00     | $36,904.40      |
| 2024-05-12 |      0.665 | $17,500.00     | $11,640.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
