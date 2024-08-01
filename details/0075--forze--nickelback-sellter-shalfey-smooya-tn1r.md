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
Final Rank Value (944.7) = Starting Rank Value (894.9) + Head To Head Adjustments (49.8)<br />

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
|           30 |     2316 | 2024-05-04 | Monte           | L   | 0.605      | -            | -                | -                | -         |    -7.77 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2344 | 2024-05-02 | GamerLegion     | L   | 0.593      | -            | -                | -                | -         |    -5.02 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2372 | 2024-05-01 | FURIA           | W   | 0.587      | 0.889        | 0.286 (0.149)    | 0.494 (0.258)    | 1 (0.587) |    18.13 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2396 | 2024-04-30 | Monte           | L   | 0.580      | -            | -                | -                | -         |    -7.43 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2861 | 2024-04-12 | BIG             | L   | 0.459      | -            | -                | -                | -         |    -2.48 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2895 | 2024-04-11 | Aurora          | L   | 0.452      | -            | -                | -                | -         |    -0.29 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2927 | 2024-04-10 | TSM             | W   | 0.447      | 0.500        | 0.006 (0.001)    | -                | 0 (0.000) |     2.64 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2982 | 2024-04-09 | brazylijski luz | W   | 0.440      | 0.500        | 0.008 (0.002)    | 0.308 (0.068)    | 0 (0.000) |     4.54 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3023 | 2024-04-08 | ENCE            | W   | 0.432      | 0.684        | 0.173 (0.051)    | 0.403 (0.119)    | 0 (0.000) |    12.92 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3305 | 2024-03-27 | 500             | L   | 0.353      | -            | -                | -                | -         |    -8.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3340 | 2024-03-26 | Apeks           | W   | 0.345      | 0.500        | 0.030 (0.005)    | 0.193 (0.033)    | 0 (0.000) |     5.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3346 | 2024-03-25 | B8              | L   | 0.339      | -            | -                | -                | -         |    -3.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3351 | 2024-03-24 | BetBoom         | W   | 0.331      | 0.143        | 0.257 (0.012)    | 0.551 (0.026)    | 0 (0.000) |     9.84 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3362 | 2024-03-23 | VP.Prodigy      | W   | 0.326      | 0.143        | -                | 0.405 (0.019)    | 0 (0.000) |     4.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3376 | 2024-03-22 | ex-Preasy       | W   | 0.319      | -            | -                | -                | 0 (0.000) |     3.73 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3399 | 2024-03-21 | PARIVISION      | L   | 0.313      | -            | -                | -                | -         |    -2.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3423 | 2024-03-20 | NAVI Junior     | W   | 0.306      | -            | -                | -                | 0 (0.000) |     1.05 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3786 | 2024-03-05 | KOI             | L   | 0.207      | -            | -                | -                | -         |    -3.09 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3791 | 2024-03-05 | AMKAL           | W   | 0.207      | 0.143        | 0.132 (0.004)    | 0.482 (0.014)    | 0 (0.000) |     5.11 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3803 | 2024-03-05 | 3DMAX           | W   | 0.206      | 0.143        | 0.505 (0.015)    | 1.000 (0.029)    | -         |     6.41 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3893 | 2024-03-01 | Aurora          | L   | 0.180      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3902 | 2024-02-29 | 9 Pandas        | W   | 0.173      | 0.143        | 0.083 (0.002)    | 0.577 (0.014)    | -         |     3.50 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3914 | 2024-02-28 | KOI             | W   | 0.167      | -            | -                | -                | -         |     2.90 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3920 | 2024-02-28 | Aurora          | W   | 0.166      | 0.143        | 0.431 (0.010)    | 0.798 (0.019)    | -         |     5.16 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3933 | 2024-02-27 | V1dar           | W   | 0.160      | -            | -                | -                | -         |     0.56 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3941 | 2024-02-27 | ARCRED          | W   | 0.160      | -            | -                | -                | -         |     2.25 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4357 | 2024-02-09 | Sashi           | L   | 0.040      | -            | -                | -                | -         |    -0.23 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4363 | 2024-02-09 | RUBY            | W   | 0.039      | -            | -                | -                | -         |     0.70 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4371 | 2024-02-08 | BetBoom         | W   | 0.033      | -            | -                | -                | -         |     1.01 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4376 | 2024-02-08 | Sashi           | L   | 0.032      | -            | -                | -                | -         |    -0.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,551.77)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $3,000.00      | $2,538.13       |
| 2024-05-12 |      0.659 | $7,000.00      | $4,614.17       |
| 2024-04-14 |      0.472 | $26,250.00     | $12,399.48      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
