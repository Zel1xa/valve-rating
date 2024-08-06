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
Final Rank Value (1154.2) = Starting Rank Value (1169.2) + Head To Head Adjustments (-15.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.374<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1169.2
- 400 + ( ( 0.374 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1169.2


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
|           57 |       43 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.421 (0.210)    | 0.759 (0.379)    | 0 (0.000) |    26.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       76 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.81 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |      119 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.94 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      123 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.99 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      190 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.72 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      250 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      601 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -20.95 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      635 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      701 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.37 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      763 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.28 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      808 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | 0 (0.000) |     9.51 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1063 | 2024-06-15 | Zero Tenacity     | W   | 0.855      | -            | -                | -                | 0 (0.000) |    10.53 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1101 | 2024-06-14 | System5           | W   | 0.848      | -            | -                | -                | 0 (0.000) |     1.65 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1135 | 2024-06-13 | Verdant           | W   | 0.842      | -            | -                | -                | 0 (0.000) |     5.26 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1168 | 2024-06-12 | FAVBET            | L   | 0.835      | -            | -                | -                | -         |   -22.81 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1183 | 2024-06-11 | Permitta          | W   | 0.829      | -            | -                | -                | -         |     5.54 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1193 | 2024-06-11 | Rhyno             | W   | 0.828      | -            | -                | -                | -         |     7.39 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1223 | 2024-06-10 | BLEED             | W   | 0.820      | 0.500        | 0.126 (0.052)    | -                | -         |    19.76 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1290 | 2024-06-09 | Zero Tenacity     | W   | 0.813      | 0.500        | 0.143 (0.058)    | 1.000 (0.406)    | -         |    11.00 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1451 | 2024-06-06 | Sampi             | W   | 0.794      | 0.500        | -                | 1.000 (0.397)    | -         |     6.17 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1555 | 2024-06-04 | CYBERSHOKE        | W   | 0.781      | -            | -                | -                | -         |     4.80 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1603 | 2024-06-02 | Grannys Knockers  | L   | 0.767      | -            | -                | -                | -         |   -21.30 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1695 | 2024-05-30 | DMS               | L   | 0.748      | -            | -                | -                | -         |   -18.47 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2287 | 2024-05-10 | RUBY              | L   | 0.613      | -            | -                | -                | -         |   -15.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2333 | 2024-05-08 | 1WIN              | L   | 0.600      | -            | -                | -                | -         |   -14.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2351 | 2024-05-07 | SINNERS           | W   | 0.593      | -            | -                | -                | -         |     6.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2377 | 2024-05-05 | VP.Prodigy        | W   | 0.581      | -            | -                | -                | -         |     2.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2413 | 2024-05-03 | MOUZ NXT          | W   | 0.568      | 0.500        | 0.139 (0.039)    | 0.962 (0.273)    | -         |     5.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2438 | 2024-05-02 | Passion UA        | W   | 0.561      | 0.500        | 0.173 (0.049)    | 1.000 (0.281)    | -         |     5.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2456 | 2024-05-01 | B8                | W   | 0.555      | 0.500        | 0.170 (0.047)    | 0.912 (0.253)    | -         |     5.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2502 | 2024-04-29 | MOUZ NXT          | W   | 0.542      | 0.500        | 0.139 (0.038)    | 0.962 (0.261)    | -         |     5.84 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2534 | 2024-04-28 | Grannys Knockers  | L   | 0.533      | -            | -                | -                | -         |   -15.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2556 | 2024-04-27 | 1WIN              | W   | 0.527      | -            | -                | -                | -         |     3.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2582 | 2024-04-26 | Sangal            | L   | 0.520      | -            | -                | -                | -         |    -9.36 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2623 | 2024-04-24 | BLEED             | W   | 0.508      | -            | -                | -                | -         |     5.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2647 | 2024-04-23 | Zero Tenacity     | W   | 0.500      | 0.500        | 0.143 (0.036)    | 1.000 (0.250)    | -         |     5.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2668 | 2024-04-22 | MOUZ NXT          | W   | 0.493      | 0.500        | -                | 0.962 (0.237)    | -         |     5.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2683 | 2024-04-21 | 1WIN              | W   | 0.487      | -            | -                | -                | -         |     3.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2716 | 2024-04-20 | Gaimin Gladiators | L   | 0.480      | -            | -                | -                | -         |   -10.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2751 | 2024-04-19 | Sangal            | W   | 0.474      | 0.500        | 0.219 (0.052)    | -                | -         |     7.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2801 | 2024-04-18 | Secret            | W   | 0.468      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2838 | 2024-04-17 | Alliance          | W   | 0.461      | -            | -                | -                | -         |     2.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     3030 | 2024-04-09 | FlyQuest          | L   | 0.412      | -            | -                | -                | -         |    -6.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3078 | 2024-04-09 | Steel Helmet      | W   | 0.406      | -            | -                | -                | 1 (0.406) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3107 | 2024-04-08 | FaZe              | L   | 0.399      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3300 | 2024-04-01 | Zero Tenacity     | W   | 0.353      | -            | -                | -                | -         |     4.59 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3432 | 2024-03-22 | Sashi             | L   | 0.289      | -            | -                | -                | -         |    -4.92 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3669 | 2024-03-12 | Nexus             | L   | 0.222      | -            | -                | -                | -         |    -6.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3698 | 2024-03-11 | Sashi             | W   | 0.214      | -            | -                | -                | -         |     3.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3713 | 2024-03-10 | Endpoint          | W   | 0.208      | -            | -                | -                | -         |     1.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3785 | 2024-03-07 | Zero Tenacity     | W   | 0.188      | -            | -                | -                | -         |     2.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3847 | 2024-03-05 | KOI               | L   | 0.175      | -            | -                | -                | -         |    -3.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3854 | 2024-03-05 | GUN5              | W   | 0.175      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4371 | 2024-02-10 | Sashi             | W   | 0.016      | -            | -                | -                | -         |     0.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4387 | 2024-02-09 | AMKAL             | W   | 0.009      | -            | -                | -                | -         |     0.13 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4402 | 2024-02-08 | Sashi             | W   | 0.002      | -            | -                | -                | -         |     0.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4408 | 2024-02-08 | BetBoom           | W   | 0.001      | -            | -                | -                | -         |     0.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100,810.45)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.828 | $50,000.00     | $41,388.89      |
| 2024-05-09 |      0.607 | $4,000.00      | $2,427.78       |
| 2024-05-03 |      0.568 | $50,000.00     | $28,388.89      |
| 2024-04-24 |      0.508 | $50,000.00     | $25,388.89      |
| 2024-04-14 |      0.440 | $5,000.00      | $2,199.42       |
| 2024-03-25 |      0.308 | $3,300.00      | $1,016.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
