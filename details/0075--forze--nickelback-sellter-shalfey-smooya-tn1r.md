### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.7<br />
<br />
Final Rank Value (944.7) = Starting Rank Value (894.9) + Head To Head Adjustments (49.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 894.9
- 400 + ( ( 0.241 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 894.9


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
|           30 |     2314 | 2024-05-04 | Monte           | L   | 0.605      | -            | -                | -                | -         |    -7.77 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2342 | 2024-05-02 | GamerLegion     | L   | 0.594      | -            | -                | -                | -         |    -5.04 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2370 | 2024-05-01 | FURIA           | W   | 0.587      | 0.889        | 0.286 (0.149)    | 0.494 (0.258)    | 1 (0.587) |    18.13 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2394 | 2024-04-30 | Monte           | L   | 0.580      | -            | -                | -                | -         |    -7.43 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2859 | 2024-04-12 | BIG             | L   | 0.460      | -            | -                | -                | -         |    -2.49 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2893 | 2024-04-11 | Aurora          | L   | 0.452      | -            | -                | -                | -         |    -0.29 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2925 | 2024-04-10 | TSM             | W   | 0.447      | -            | -                | -                | 0 (0.000) |     2.65 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2980 | 2024-04-09 | brazylijski luz | W   | 0.440      | 0.500        | 0.008 (0.002)    | 0.308 (0.068)    | 0 (0.000) |     4.55 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3021 | 2024-04-08 | ENCE            | W   | 0.432      | 0.684        | 0.174 (0.051)    | 0.403 (0.119)    | 0 (0.000) |    12.93 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3303 | 2024-03-27 | 500             | L   | 0.354      | -            | -                | -                | -         |    -8.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3338 | 2024-03-26 | Apeks           | W   | 0.346      | 0.500        | 0.030 (0.005)    | 0.193 (0.033)    | 0 (0.000) |     5.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3344 | 2024-03-25 | B8              | L   | 0.340      | -            | -                | -                | -         |    -3.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3349 | 2024-03-24 | BetBoom         | W   | 0.332      | 0.143        | 0.257 (0.012)    | 0.551 (0.026)    | 0 (0.000) |     9.85 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3360 | 2024-03-23 | VP.Prodigy      | W   | 0.326      | 0.143        | -                | 0.405 (0.019)    | 0 (0.000) |     4.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3374 | 2024-03-22 | ex-Preasy       | W   | 0.319      | -            | -                | -                | 0 (0.000) |     3.73 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3397 | 2024-03-21 | PARIVISION      | L   | 0.313      | -            | -                | -                | -         |    -2.57 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3421 | 2024-03-20 | NAVI Junior     | W   | 0.306      | -            | -                | -                | 0 (0.000) |     1.05 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3784 | 2024-03-05 | KOI             | L   | 0.207      | -            | -                | -                | -         |    -3.10 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3789 | 2024-03-05 | AMKAL           | W   | 0.207      | 0.143        | 0.132 (0.004)    | 0.482 (0.014)    | 0 (0.000) |     5.12 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3801 | 2024-03-05 | 3DMAX           | W   | 0.207      | 0.143        | 0.505 (0.015)    | 1.000 (0.030)    | -         |     6.42 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3891 | 2024-03-01 | Aurora          | L   | 0.180      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3900 | 2024-02-29 | 9 Pandas        | W   | 0.174      | 0.143        | 0.083 (0.002)    | 0.577 (0.014)    | -         |     3.50 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3912 | 2024-02-28 | KOI             | W   | 0.167      | -            | -                | -                | -         |     2.90 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3918 | 2024-02-28 | Aurora          | W   | 0.166      | 0.143        | 0.431 (0.010)    | 0.798 (0.019)    | -         |     5.17 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3931 | 2024-02-27 | V1dar           | W   | 0.160      | -            | -                | -                | -         |     0.57 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3939 | 2024-02-27 | ARCRED          | W   | 0.160      | -            | -                | -                | -         |     2.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4355 | 2024-02-09 | Sashi           | L   | 0.040      | -            | -                | -                | -         |    -0.23 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4361 | 2024-02-09 | RUBY            | W   | 0.039      | -            | -                | -                | -         |     0.70 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4369 | 2024-02-08 | BetBoom         | W   | 0.034      | 0.143        | 0.257 (0.001)    | -                | -         |     1.01 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4374 | 2024-02-08 | Sashi           | L   | 0.033      | -            | -                | -                | -         |    -0.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,561.84)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $3,000.00      | $2,538.96       |
| 2024-05-12 |      0.659 | $7,000.00      | $4,616.11       |
| 2024-04-14 |      0.473 | $26,250.00     | $12,406.77      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
