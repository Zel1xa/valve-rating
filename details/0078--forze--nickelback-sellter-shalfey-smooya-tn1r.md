### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  933.9<br />
<br />
Final Rank Value (933.9) = Starting Rank Value (885.3) + Head To Head Adjustments (48.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.381[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.3
- 400 + ( ( 0.237 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 885.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     2336 | 2024-05-04 | Monte           | L   | 0.587      | -            | -                | -                | -         |    -7.63 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2364 | 2024-05-02 | GamerLegion     | L   | 0.576      | -            | -                | -                | -         |    -4.78 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2390 | 2024-05-01 | FURIA           | W   | 0.569      | 0.889        | 0.284 (0.144)    | 0.491 (0.248)    | 1 (0.569) |    17.58 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2413 | 2024-04-30 | Monte           | L   | 0.562      | -            | -                | -                | -         |    -7.29 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2868 | 2024-04-12 | BIG             | L   | 0.442      | -            | -                | -                | -         |    -1.59 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2901 | 2024-04-11 | Aurora          | L   | 0.434      | -            | -                | -                | -         |    -0.28 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2933 | 2024-04-10 | TSM             | W   | 0.429      | -            | -                | -                | 0 (0.000) |     2.63 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2988 | 2024-04-09 | brazylijski luz | W   | 0.422      | 0.500        | 0.008 (0.002)    | 0.262 (0.055)    | 0 (0.000) |     4.31 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3029 | 2024-04-08 | ENCE            | W   | 0.414      | 0.684        | 0.169 (0.048)    | 0.400 (0.113)    | 0 (0.000) |    12.39 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3302 | 2024-03-27 | 500             | L   | 0.336      | -            | -                | -                | -         |    -8.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3333 | 2024-03-26 | Apeks           | W   | 0.328      | 0.500        | 0.027 (0.004)    | 0.166 (0.027)    | 0 (0.000) |     4.98 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3339 | 2024-03-25 | B8              | L   | 0.322      | -            | -                | -                | -         |    -2.89 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3344 | 2024-03-24 | BetBoom         | W   | 0.314      | 0.143        | 0.251 (0.011)    | 0.542 (0.024)    | 0 (0.000) |     9.31 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3355 | 2024-03-23 | VP.Prodigy      | W   | 0.308      | 0.143        | -                | 0.401 (0.018)    | 0 (0.000) |     4.29 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3369 | 2024-03-22 | ex-Preasy       | W   | 0.301      | -            | -                | -                | 0 (0.000) |     3.50 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3392 | 2024-03-21 | PARIVISION      | L   | 0.295      | -            | -                | -                | -         |    -2.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3416 | 2024-03-20 | NAVI Junior     | W   | 0.288      | -            | -                | -                | 0 (0.000) |     1.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3773 | 2024-03-05 | KOI             | L   | 0.189      | -            | -                | -                | -         |    -1.62 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3778 | 2024-03-05 | AMKAL           | W   | 0.189      | 0.143        | 0.130 (0.004)    | 0.476 (0.013)    | 0 (0.000) |     4.71 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3785 | 2024-03-05 | 3DMAX           | W   | 0.189      | 0.143        | 0.506 (0.014)    | 1.000 (0.027)    | -         |     5.86 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3874 | 2024-03-01 | Aurora          | L   | 0.162      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3883 | 2024-02-29 | 9 Pandas        | W   | 0.156      | 0.143        | 0.082 (0.002)    | 0.690 (0.015)    | -         |     3.16 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3895 | 2024-02-28 | KOI             | W   | 0.149      | 0.143        | 0.058 (0.001)    | -                | -         |     3.52 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3900 | 2024-02-28 | Aurora          | W   | 0.148      | 0.143        | 0.424 (0.009)    | 0.793 (0.017)    | -         |     4.60 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3913 | 2024-02-27 | V1dar           | W   | 0.142      | -            | -                | -                | -         |     0.52 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3921 | 2024-02-27 | ARCRED          | W   | 0.142      | -            | -                | -                | -         |     2.10 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4320 | 2024-02-09 | Sashi           | L   | 0.022      | -            | -                | -                | -         |    -0.13 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4325 | 2024-02-09 | RUBY            | W   | 0.021      | -            | -                | -                | -         |     0.38 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4333 | 2024-02-08 | BetBoom         | W   | 0.016      | -            | -                | -                | -         |     0.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4338 | 2024-02-08 | Sashi           | L   | 0.015      | -            | -                | -                | -         |    -0.08 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,907.33)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $3,000.00      | $2,484.79       |
| 2024-05-12 |      0.641 | $7,000.00      | $4,489.72       |
| 2024-04-14 |      0.455 | $26,250.00     | $11,932.81      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
