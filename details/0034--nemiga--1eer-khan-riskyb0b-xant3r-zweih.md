### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1154.2<br />
<br />
Final Rank Value (1154.2) = Starting Rank Value (1169.1) + Head To Head Adjustments (-14.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.327[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.375<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1169.1
- 400 + ( ( 0.375 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1169.1


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
|           57 |       39 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.421 (0.210)    | 0.776 (0.388)    | 0 (0.000) |    26.41 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       72 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.81 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |      115 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.93 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      119 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.00 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      186 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.73 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      246 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      597 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.95 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      631 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      697 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.36 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      759 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.29 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      804 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | 0 (0.000) |     9.51 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1059 | 2024-06-15 | Zero Tenacity     | W   | 0.855      | -            | -                | -                | 0 (0.000) |    10.54 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1097 | 2024-06-14 | System5           | W   | 0.849      | -            | -                | -                | 0 (0.000) |     1.64 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1131 | 2024-06-13 | Verdant           | W   | 0.842      | -            | -                | -                | 0 (0.000) |     5.25 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1164 | 2024-06-12 | FAVBET            | L   | 0.835      | -            | -                | -                | -         |   -22.83 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1179 | 2024-06-11 | Permitta          | W   | 0.829      | -            | -                | -                | -         |     5.54 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1189 | 2024-06-11 | Rhyno             | W   | 0.828      | -            | -                | -                | -         |     7.40 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1219 | 2024-06-10 | BLEED             | W   | 0.821      | 0.500        | 0.126 (0.052)    | -                | -         |    19.77 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1286 | 2024-06-09 | Zero Tenacity     | W   | 0.813      | 0.500        | 0.143 (0.058)    | 1.000 (0.407)    | -         |    11.01 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1447 | 2024-06-06 | Sampi             | W   | 0.795      | 0.500        | -                | 1.000 (0.397)    | -         |     6.18 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1551 | 2024-06-04 | CYBERSHOKE        | W   | 0.781      | -            | -                | -                | -         |     4.81 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1599 | 2024-06-02 | Grannys Knockers  | L   | 0.768      | -            | -                | -                | -         |   -21.32 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1691 | 2024-05-30 | DMS               | L   | 0.748      | -            | -                | -                | -         |   -18.47 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2283 | 2024-05-10 | RUBY              | L   | 0.613      | -            | -                | -                | -         |   -15.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2329 | 2024-05-08 | 1WIN              | L   | 0.600      | -            | -                | -                | -         |   -14.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2347 | 2024-05-07 | SINNERS           | W   | 0.594      | -            | -                | -                | -         |     6.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2373 | 2024-05-05 | VP.Prodigy        | W   | 0.582      | -            | -                | -                | -         |     2.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2409 | 2024-05-03 | MOUZ NXT          | W   | 0.568      | 0.500        | 0.139 (0.039)    | 0.984 (0.279)    | -         |     5.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2434 | 2024-05-02 | Passion UA        | W   | 0.561      | 0.500        | 0.173 (0.049)    | 1.000 (0.281)    | -         |     5.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2452 | 2024-05-01 | B8                | W   | 0.556      | 0.500        | 0.164 (0.046)    | 0.933 (0.259)    | -         |     5.83 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2498 | 2024-04-29 | MOUZ NXT          | W   | 0.542      | 0.500        | 0.139 (0.038)    | 0.984 (0.267)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2530 | 2024-04-28 | Grannys Knockers  | L   | 0.533      | -            | -                | -                | -         |   -15.26 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2552 | 2024-04-27 | 1WIN              | W   | 0.527      | -            | -                | -                | -         |     3.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2578 | 2024-04-26 | Sangal            | L   | 0.520      | -            | -                | -                | -         |    -9.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2619 | 2024-04-24 | BLEED             | W   | 0.508      | -            | -                | -                | -         |     5.43 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2643 | 2024-04-23 | Zero Tenacity     | W   | 0.501      | 0.500        | 0.143 (0.036)    | 1.000 (0.250)    | -         |     5.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2664 | 2024-04-22 | MOUZ NXT          | W   | 0.493      | 0.500        | -                | 0.984 (0.243)    | -         |     5.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2679 | 2024-04-21 | 1WIN              | W   | 0.487      | -            | -                | -                | -         |     3.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2712 | 2024-04-20 | Gaimin Gladiators | L   | 0.480      | -            | -                | -                | -         |   -10.62 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2747 | 2024-04-19 | Sangal            | W   | 0.475      | 0.500        | 0.219 (0.052)    | -                | -         |     7.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2797 | 2024-04-18 | Secret            | W   | 0.468      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2834 | 2024-04-17 | Alliance          | W   | 0.461      | -            | -                | -                | -         |     2.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     3026 | 2024-04-09 | FlyQuest          | L   | 0.412      | -            | -                | -                | -         |    -6.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3074 | 2024-04-09 | Steel Helmet      | W   | 0.406      | -            | -                | -                | 1 (0.406) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3103 | 2024-04-08 | FaZe              | L   | 0.400      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3296 | 2024-04-01 | Zero Tenacity     | W   | 0.353      | -            | -                | -                | -         |     4.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3428 | 2024-03-22 | Sashi             | L   | 0.289      | -            | -                | -                | -         |    -4.92 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3665 | 2024-03-12 | Nexus             | L   | 0.222      | -            | -                | -                | -         |    -6.05 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3694 | 2024-03-11 | Sashi             | W   | 0.214      | -            | -                | -                | -         |     3.05 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3709 | 2024-03-10 | Endpoint          | W   | 0.208      | -            | -                | -                | -         |     1.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3781 | 2024-03-07 | Zero Tenacity     | W   | 0.188      | -            | -                | -                | -         |     2.43 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3843 | 2024-03-05 | KOI               | L   | 0.176      | -            | -                | -                | -         |    -3.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3850 | 2024-03-05 | GUN5              | W   | 0.175      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4367 | 2024-02-10 | Sashi             | W   | 0.016      | -            | -                | -                | -         |     0.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4383 | 2024-02-09 | AMKAL             | W   | 0.009      | -            | -                | -                | -         |     0.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4398 | 2024-02-08 | Sashi             | W   | 0.002      | -            | -                | -                | -         |     0.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4404 | 2024-02-08 | BetBoom           | W   | 0.001      | -            | -                | -                | -         |     0.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100,855.53)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.828 | $50,000.00     | $41,402.78      |
| 2024-05-09 |      0.607 | $4,000.00      | $2,428.89       |
| 2024-05-03 |      0.568 | $50,000.00     | $28,402.78      |
| 2024-04-24 |      0.508 | $50,000.00     | $25,402.78      |
| 2024-04-14 |      0.440 | $5,000.00      | $2,200.81       |
| 2024-03-25 |      0.308 | $3,300.00      | $1,017.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
