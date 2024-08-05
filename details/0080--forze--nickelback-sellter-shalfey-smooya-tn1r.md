### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  931.6<br />
<br />
Final Rank Value (931.6) = Starting Rank Value (884.6) + Head To Head Adjustments (47.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.380[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 884.6
- 400 + ( ( 0.237 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 884.6


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
|           30 |     2385 | 2024-05-04 | Monte           | L   | 0.580      | -            | -                | -                | -         |    -7.57 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2413 | 2024-05-02 | GamerLegion     | L   | 0.568      | -            | -                | -                | -         |    -4.67 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2439 | 2024-05-01 | FURIA           | W   | 0.561      | 0.889        | 0.284 (0.142)    | 0.487 (0.243)    | 1 (0.561) |    17.36 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2462 | 2024-04-30 | Monte           | L   | 0.555      | -            | -                | -                | -         |    -7.24 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2917 | 2024-04-12 | BIG             | L   | 0.434      | -            | -                | -                | -         |    -1.55 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2950 | 2024-04-11 | Aurora          | L   | 0.427      | -            | -                | -                | -         |    -0.26 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2982 | 2024-04-10 | TSM             | W   | 0.421      | -            | -                | -                | 0 (0.000) |     2.60 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3037 | 2024-04-09 | brazylijski luz | W   | 0.415      | 0.500        | 0.008 (0.002)    | 0.260 (0.054)    | 0 (0.000) |     4.29 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3078 | 2024-04-08 | ENCE            | W   | 0.407      | 0.684        | 0.168 (0.047)    | 0.438 (0.122)    | 0 (0.000) |    12.20 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3351 | 2024-03-27 | 500             | L   | 0.328      | -            | -                | -                | -         |    -7.87 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3382 | 2024-03-26 | Apeks           | W   | 0.320      | 0.500        | 0.027 (0.004)    | 0.163 (0.026)    | 0 (0.000) |     4.84 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3388 | 2024-03-25 | B8              | L   | 0.314      | -            | -                | -                | -         |    -2.80 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3393 | 2024-03-24 | BetBoom         | W   | 0.306      | 0.143        | 0.249 (0.011)    | 0.536 (0.023)    | 0 (0.000) |     9.09 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3404 | 2024-03-23 | VP.Prodigy      | W   | 0.300      | 0.143        | -                | 0.398 (0.017)    | 0 (0.000) |     4.21 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3418 | 2024-03-22 | ex-Preasy       | W   | 0.293      | -            | -                | -                | 0 (0.000) |     3.39 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3441 | 2024-03-21 | PARIVISION      | L   | 0.287      | -            | -                | -                | -         |    -2.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3465 | 2024-03-20 | NAVI Junior     | W   | 0.280      | -            | -                | -                | 0 (0.000) |     1.01 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3822 | 2024-03-05 | KOI             | L   | 0.182      | -            | -                | -                | -         |    -1.55 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3827 | 2024-03-05 | AMKAL           | W   | 0.182      | 0.143        | 0.130 (0.003)    | 0.472 (0.012)    | 0 (0.000) |     4.53 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3834 | 2024-03-05 | 3DMAX           | W   | 0.181      | 0.143        | 0.508 (0.013)    | 1.000 (0.026)    | -         |     5.63 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3923 | 2024-03-01 | Aurora          | L   | 0.155      | -            | -                | -                | -         |    -0.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3932 | 2024-02-29 | 9 Pandas        | W   | 0.148      | 0.143        | 0.081 (0.002)    | 0.727 (0.015)    | -         |     3.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3944 | 2024-02-28 | KOI             | W   | 0.142      | 0.143        | 0.058 (0.001)    | -                | -         |     3.34 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3949 | 2024-02-28 | Aurora          | W   | 0.140      | 0.143        | 0.422 (0.008)    | 0.788 (0.016)    | -         |     4.37 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3962 | 2024-02-27 | V1dar           | W   | 0.135      | -            | -                | -                | -         |     0.49 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3970 | 2024-02-27 | ARCRED          | W   | 0.134      | -            | -                | -                | -         |     2.00 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4369 | 2024-02-09 | Sashi           | L   | 0.015      | -            | -                | -                | -         |    -0.08 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4374 | 2024-02-09 | RUBY            | W   | 0.014      | -            | -                | -                | -         |     0.24 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4382 | 2024-02-08 | BetBoom         | W   | 0.008      | -            | -                | -                | -         |     0.25 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4387 | 2024-02-08 | Sashi           | L   | 0.007      | -            | -                | -                | -         |    -0.04 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,635.45)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.821 | $3,000.00      | $2,462.29       |
| 2024-05-12 |      0.634 | $7,000.00      | $4,437.22       |
| 2024-04-14 |      0.447 | $26,250.00     | $11,735.94      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
