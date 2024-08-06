### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
<br />
Final Rank Value:  931.2<br />
<br />
Final Rank Value (931.2) = Starting Rank Value (884.4) + Head To Head Adjustments (46.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.052[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.235<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 884.4
- 400 + ( ( 0.235 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 884.4


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
|           30 |     2407 | 2024-05-04 | Monte           | L   | 0.573      | -            | -                | -                | -         |    -7.49 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2435 | 2024-05-02 | GamerLegion     | L   | 0.562      | -            | -                | -                | -         |    -4.66 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2461 | 2024-05-01 | FURIA           | W   | 0.555      | 0.889        | 0.284 (0.140)    | 0.469 (0.231)    | 1 (0.555) |    17.16 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2484 | 2024-04-30 | Monte           | L   | 0.548      | -            | -                | -                | -         |    -7.17 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2939 | 2024-04-12 | BIG             | L   | 0.428      | -            | -                | -                | -         |    -1.53 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2972 | 2024-04-11 | Aurora          | L   | 0.420      | -            | -                | -                | -         |    -0.25 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     3004 | 2024-04-10 | TSM             | W   | 0.415      | -            | -                | -                | 0 (0.000) |     2.56 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3059 | 2024-04-09 | brazylijski luz | W   | 0.408      | 0.500        | 0.008 (0.002)    | 0.250 (0.051)    | 0 (0.000) |     4.22 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3100 | 2024-04-08 | ENCE            | W   | 0.400      | 0.684        | 0.173 (0.047)    | 0.422 (0.115)    | 0 (0.000) |    12.02 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3373 | 2024-03-27 | 500             | L   | 0.322      | -            | -                | -                | -         |    -7.71 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3404 | 2024-03-26 | Apeks           | W   | 0.314      | 0.500        | 0.026 (0.004)    | 0.154 (0.024)    | 0 (0.000) |     4.73 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3410 | 2024-03-25 | B8              | L   | 0.308      | -            | -                | -                | -         |    -2.72 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3415 | 2024-03-24 | BetBoom         | W   | 0.300      | 0.143        | 0.248 (0.011)    | 0.514 (0.022)    | 0 (0.000) |     8.88 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3426 | 2024-03-23 | VP.Prodigy      | W   | 0.294      | 0.143        | -                | 0.383 (0.016)    | 0 (0.000) |     4.13 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3440 | 2024-03-22 | ex-Preasy       | W   | 0.287      | -            | -                | -                | 0 (0.000) |     3.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3463 | 2024-03-21 | PARIVISION      | L   | 0.281      | -            | -                | -                | -         |    -2.09 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3487 | 2024-03-20 | NAVI Junior     | W   | 0.274      | -            | -                | -                | 0 (0.000) |     2.19 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3844 | 2024-03-05 | KOI             | L   | 0.175      | -            | -                | -                | -         |    -1.51 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3849 | 2024-03-05 | AMKAL           | W   | 0.175      | 0.143        | 0.130 (0.003)    | 0.453 (0.011)    | 0 (0.000) |     4.38 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3856 | 2024-03-05 | 3DMAX           | W   | 0.175      | 0.143        | 0.510 (0.013)    | 1.000 (0.025)    | -         |     5.43 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3945 | 2024-03-01 | Aurora          | L   | 0.148      | -            | -                | -                | -         |    -0.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3954 | 2024-02-29 | 9 Pandas        | W   | 0.142      | 0.143        | 0.081 (0.002)    | 0.700 (0.014)    | -         |     2.87 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3966 | 2024-02-28 | KOI             | W   | 0.135      | 0.143        | 0.058 (0.001)    | -                | -         |     3.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3971 | 2024-02-28 | Aurora          | W   | 0.134      | 0.143        | 0.420 (0.008)    | 0.759 (0.015)    | -         |     4.17 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3984 | 2024-02-27 | V1dar           | W   | 0.128      | -            | -                | -                | -         |     0.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3992 | 2024-02-27 | ARCRED          | W   | 0.128      | -            | -                | -                | -         |     2.17 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4391 | 2024-02-09 | Sashi           | L   | 0.008      | -            | -                | -                | -         |    -0.05 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4396 | 2024-02-09 | RUBY            | W   | 0.007      | -            | -                | -                | -         |     0.13 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4404 | 2024-02-08 | BetBoom         | W   | 0.002      | -            | -                | -                | -         |     0.05 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4409 | 2024-02-08 | Sashi           | L   | 0.001      | -            | -                | -                | -         |    -0.00 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,400.50)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $3,000.00      | $2,442.85       |
| 2024-05-12 |      0.627 | $7,000.00      | $4,391.85       |
| 2024-04-14 |      0.441 | $26,250.00     | $11,565.80      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
