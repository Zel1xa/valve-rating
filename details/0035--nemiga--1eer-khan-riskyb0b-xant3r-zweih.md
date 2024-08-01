### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1157.0<br />
<br />
Final Rank Value (1157.0) = Starting Rank Value (1161.9) + Head To Head Adjustments (-4.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.671[<sup>1</sup>](#table2)
- Bounty Collected: 0.437[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.050[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1161.9
- 400 + ( ( 0.370 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1161.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |       36 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.00 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |       98 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.46 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      454 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.90 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      489 | 2024-07-18 | PERA              | W   | 1.000      | 0.500        | -                | 0.452 (0.226)    | 0 (0.000) |     8.72 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      558 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -8.83 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      621 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.76 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      671 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.50 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      925 | 2024-06-15 | Zero Tenacity     | W   | 0.887      | -            | -                | -                | 0 (0.000) |     9.38 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           46 |      956 | 2024-06-14 | System5           | W   | 0.880      | -            | -                | -                | 0 (0.000) |     1.86 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |      989 | 2024-06-13 | Verdant           | W   | 0.874      | -            | -                | -                | 0 (0.000) |     5.84 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1022 | 2024-06-12 | FAVBET            | L   | 0.867      | -            | -                | -                | -         |   -23.37 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1038 | 2024-06-11 | Permitta          | W   | 0.860      | -            | -                | -                | 0 (0.000) |     5.89 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1048 | 2024-06-11 | Rhyno             | W   | 0.859      | -            | -                | -                | -         |     8.48 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           41 |     1079 | 2024-06-10 | BLEED             | W   | 0.852      | 0.500        | 0.128 (0.055)    | -                | -         |    21.00 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1147 | 2024-06-09 | Zero Tenacity     | W   | 0.844      | 0.500        | 0.139 (0.059)    | 1.000 (0.422)    | -         |    10.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1318 | 2024-06-06 | Sampi             | W   | 0.826      | 0.500        | -                | 1.000 (0.413)    | -         |     6.55 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1425 | 2024-06-04 | CYBERSHOKE        | W   | 0.813      | -            | -                | -                | -         |     5.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1474 | 2024-06-02 | Grannys Knockers  | L   | 0.799      | -            | -                | -                | -         |   -21.86 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           36 |     1566 | 2024-05-30 | DMS               | L   | 0.779      | -            | -                | -                | -         |   -18.86 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     2195 | 2024-05-10 | RUBY              | L   | 0.644      | -            | -                | -                | -         |   -15.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           34 |     2243 | 2024-05-08 | 1WIN              | L   | 0.631      | -            | -                | -                | -         |   -15.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2261 | 2024-05-07 | SINNERS           | W   | 0.625      | -            | -                | -                | -         |     5.88 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2287 | 2024-05-05 | VP.Prodigy        | W   | 0.613      | -            | -                | -                | -         |     3.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2323 | 2024-05-03 | MOUZ NXT          | W   | 0.599      | 0.500        | 0.141 (0.042)    | 1.000 (0.300)    | -         |     5.83 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2349 | 2024-05-02 | Passion UA        | W   | 0.593      | 0.500        | 0.173 (0.051)    | 1.000 (0.296)    | -         |     6.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2368 | 2024-05-01 | B8                | W   | 0.587      | 0.500        | 0.168 (0.049)    | 0.878 (0.258)    | -         |     6.38 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2415 | 2024-04-29 | MOUZ NXT          | W   | 0.574      | 0.500        | 0.141 (0.040)    | 1.000 (0.287)    | -         |     6.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2447 | 2024-04-28 | Grannys Knockers  | L   | 0.565      | -            | -                | -                | -         |   -15.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2470 | 2024-04-27 | 1WIN              | W   | 0.559      | -            | -                | -                | -         |     3.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2494 | 2024-04-26 | Sangal            | L   | 0.552      | -            | -                | -                | -         |    -9.86 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2536 | 2024-04-24 | BLEED             | W   | 0.539      | -            | -                | -                | -         |     6.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2555 | 2024-04-23 | SINNERS           | L   | 0.533      | -            | -                | -                | -         |   -10.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2562 | 2024-04-23 | Zero Tenacity     | W   | 0.532      | 0.500        | 0.139 (0.037)    | 1.000 (0.266)    | -         |     6.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2584 | 2024-04-22 | MOUZ NXT          | W   | 0.524      | 0.500        | 0.141 (0.037)    | 1.000 (0.262)    | -         |     5.96 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2600 | 2024-04-21 | 1WIN              | W   | 0.518      | -            | -                | -                | -         |     3.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2635 | 2024-04-20 | Gaimin Gladiators | L   | 0.512      | -            | -                | -                | -         |   -10.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2671 | 2024-04-19 | Sangal            | W   | 0.506      | 0.500        | 0.221 (0.056)    | -                | -         |     7.31 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2722 | 2024-04-18 | Secret            | W   | 0.500      | -            | -                | -                | -         |     0.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2760 | 2024-04-17 | Alliance          | W   | 0.493      | -            | -                | -                | -         |     2.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2954 | 2024-04-09 | FlyQuest          | L   | 0.443      | -            | -                | -                | -         |    -6.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3002 | 2024-04-09 | Steel Helmet      | W   | 0.438      | -            | -                | -                | 1 (0.438) |     0.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3031 | 2024-04-08 | FaZe              | L   | 0.431      | -            | -                | -                | -         |    -0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3232 | 2024-04-01 | Zero Tenacity     | W   | 0.385      | -            | -                | -                | -         |     5.00 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3369 | 2024-03-22 | Sashi             | L   | 0.320      | -            | -                | -                | -         |    -5.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3611 | 2024-03-12 | Nexus             | L   | 0.254      | -            | -                | -                | -         |    -6.86 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3640 | 2024-03-11 | Sashi             | W   | 0.246      | -            | -                | -                | -         |     3.59 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3655 | 2024-03-10 | Endpoint          | W   | 0.240      | -            | -                | -                | -         |     1.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3728 | 2024-03-07 | Zero Tenacity     | W   | 0.220      | -            | -                | -                | -         |     2.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3790 | 2024-03-05 | KOI               | L   | 0.207      | -            | -                | -                | -         |    -5.10 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3802 | 2024-03-05 | GUN5              | W   | 0.207      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4338 | 2024-02-10 | Sashi             | W   | 0.048      | -            | -                | -                | -         |     0.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4354 | 2024-02-09 | AMKAL             | W   | 0.040      | -            | -                | -                | -         |     0.62 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4370 | 2024-02-08 | Sashi             | W   | 0.034      | -            | -                | -                | -         |     0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4376 | 2024-02-08 | BetBoom           | W   | 0.033      | -            | -                | -                | -         |     0.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105,949.95)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.859 | $50,000.00     | $42,972.22      |
| 2024-05-09 |      0.639 | $4,000.00      | $2,554.44       |
| 2024-05-03 |      0.599 | $50,000.00     | $29,972.22      |
| 2024-04-24 |      0.539 | $50,000.00     | $26,972.22      |
| 2024-04-14 |      0.472 | $5,000.00      | $2,357.75       |
| 2024-03-25 |      0.340 | $3,300.00      | $1,121.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
