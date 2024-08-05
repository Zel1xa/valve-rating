### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1153.7<br />
<br />
Final Rank Value (1153.7) = Starting Rank Value (1170.3) + Head To Head Adjustments (-16.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.376<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1170.3
- 400 + ( ( 0.376 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1170.3


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
|           57 |       32 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.422 (0.211)    | 0.779 (0.389)    | 0 (0.000) |    26.37 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       65 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -24.04 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |      108 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.93 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      112 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.04 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      179 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.61 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      239 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      590 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -21.03 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      624 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      690 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.39 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      752 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      797 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.42 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1052 | 2024-06-15 | Zero Tenacity     | W   | 0.860      | -            | -                | -                | 0 (0.000) |    10.49 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1090 | 2024-06-14 | System5           | W   | 0.853      | -            | -                | -                | 0 (0.000) |     1.65 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1124 | 2024-06-13 | Verdant           | W   | 0.847      | -            | -                | -                | 0 (0.000) |     5.25 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1157 | 2024-06-12 | FAVBET            | L   | 0.840      | -            | -                | -                | -         |   -22.96 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1172 | 2024-06-11 | Permitta          | W   | 0.834      | -            | -                | -                | -         |     5.43 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1182 | 2024-06-11 | Rhyno             | W   | 0.833      | -            | -                | -                | -         |     7.44 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1212 | 2024-06-10 | BLEED             | W   | 0.825      | 0.500        | 0.126 (0.052)    | -                | -         |    19.86 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1279 | 2024-06-09 | Zero Tenacity     | W   | 0.818      | 0.500        | 0.143 (0.058)    | 1.000 (0.409)    | -         |    10.95 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1440 | 2024-06-06 | Sampi             | W   | 0.799      | 0.500        | -                | 1.000 (0.400)    | -         |     6.18 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1544 | 2024-06-04 | CYBERSHOKE        | W   | 0.786      | -            | -                | -                | -         |     4.83 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1592 | 2024-06-02 | Grannys Knockers  | L   | 0.772      | -            | -                | -                | -         |   -21.45 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1684 | 2024-05-30 | DMS               | L   | 0.752      | -            | -                | -                | -         |   -18.60 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2276 | 2024-05-10 | RUBY              | L   | 0.618      | -            | -                | -                | -         |   -15.37 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2322 | 2024-05-08 | 1WIN              | L   | 0.605      | -            | -                | -                | -         |   -14.70 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2340 | 2024-05-07 | SINNERS           | W   | 0.598      | -            | -                | -                | -         |     6.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2366 | 2024-05-05 | VP.Prodigy        | W   | 0.586      | -            | -                | -                | -         |     2.72 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2402 | 2024-05-03 | MOUZ NXT          | W   | 0.573      | 0.500        | 0.139 (0.040)    | 0.987 (0.283)    | -         |     5.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2427 | 2024-05-02 | Passion UA        | W   | 0.566      | 0.500        | 0.173 (0.049)    | 1.000 (0.283)    | -         |     5.68 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2445 | 2024-05-01 | B8                | W   | 0.560      | 0.500        | 0.165 (0.046)    | 0.935 (0.262)    | -         |     5.83 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2491 | 2024-04-29 | MOUZ NXT          | W   | 0.547      | 0.500        | 0.139 (0.038)    | 0.987 (0.270)    | -         |     5.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2523 | 2024-04-28 | Grannys Knockers  | L   | 0.538      | -            | -                | -                | -         |   -15.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2545 | 2024-04-27 | 1WIN              | W   | 0.532      | -            | -                | -                | -         |     3.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2571 | 2024-04-26 | Sangal            | L   | 0.525      | -            | -                | -                | -         |    -9.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2612 | 2024-04-24 | BLEED             | W   | 0.513      | -            | -                | -                | -         |     5.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2636 | 2024-04-23 | Zero Tenacity     | W   | 0.505      | 0.500        | 0.143 (0.036)    | 1.000 (0.253)    | -         |     5.93 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2657 | 2024-04-22 | MOUZ NXT          | W   | 0.498      | 0.500        | -                | 0.987 (0.246)    | -         |     5.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2672 | 2024-04-21 | 1WIN              | W   | 0.492      | -            | -                | -                | -         |     3.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2705 | 2024-04-20 | Gaimin Gladiators | L   | 0.485      | -            | -                | -                | -         |   -10.71 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2740 | 2024-04-19 | Sangal            | W   | 0.479      | 0.500        | 0.219 (0.052)    | -                | -         |     7.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2790 | 2024-04-18 | Secret            | W   | 0.473      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2827 | 2024-04-17 | Alliance          | W   | 0.466      | -            | -                | -                | -         |     2.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     3019 | 2024-04-09 | FlyQuest          | L   | 0.417      | -            | -                | -                | -         |    -6.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3067 | 2024-04-09 | Steel Helmet      | W   | 0.411      | -            | -                | -                | 1 (0.411) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3096 | 2024-04-08 | FaZe              | L   | 0.404      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3289 | 2024-04-01 | Zero Tenacity     | W   | 0.358      | -            | -                | -                | -         |     4.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3421 | 2024-03-22 | Sashi             | L   | 0.294      | -            | -                | -                | -         |    -5.03 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3658 | 2024-03-12 | Nexus             | L   | 0.227      | -            | -                | -                | -         |    -6.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3687 | 2024-03-11 | Sashi             | W   | 0.219      | -            | -                | -                | -         |     3.10 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3702 | 2024-03-10 | Endpoint          | W   | 0.213      | -            | -                | -                | -         |     1.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3774 | 2024-03-07 | Zero Tenacity     | W   | 0.193      | -            | -                | -                | -         |     2.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3836 | 2024-03-05 | KOI               | L   | 0.180      | -            | -                | -                | -         |    -3.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3843 | 2024-03-05 | GUN5              | W   | 0.180      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4360 | 2024-02-10 | Sashi             | W   | 0.021      | -            | -                | -                | -         |     0.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4376 | 2024-02-09 | AMKAL             | W   | 0.014      | -            | -                | -                | -         |     0.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4391 | 2024-02-08 | Sashi             | W   | 0.007      | -            | -                | -                | -         |     0.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4397 | 2024-02-08 | BetBoom           | W   | 0.006      | -            | -                | -                | -         |     0.15 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($101,621.95)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.833 | $50,000.00     | $41,638.89      |
| 2024-05-09 |      0.612 | $4,000.00      | $2,447.78       |
| 2024-05-03 |      0.573 | $50,000.00     | $28,638.89      |
| 2024-04-24 |      0.513 | $50,000.00     | $25,638.89      |
| 2024-04-14 |      0.445 | $5,000.00      | $2,224.42       |
| 2024-03-25 |      0.313 | $3,300.00      | $1,033.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
