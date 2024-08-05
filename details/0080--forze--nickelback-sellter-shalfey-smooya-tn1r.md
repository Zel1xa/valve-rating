### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  932.8<br />
<br />
Final Rank Value (932.8) = Starting Rank Value (885.1) + Head To Head Adjustments (47.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.380[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.1
- 400 + ( ( 0.237 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 885.1


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
|           30 |     2372 | 2024-05-04 | Monte           | L   | 0.583      | -            | -                | -                | -         |    -7.62 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2400 | 2024-05-02 | GamerLegion     | L   | 0.571      | -            | -                | -                | -         |    -4.70 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2426 | 2024-05-01 | FURIA           | W   | 0.565      | 0.889        | 0.284 (0.143)    | 0.490 (0.246)    | 1 (0.565) |    17.46 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2449 | 2024-04-30 | Monte           | L   | 0.558      | -            | -                | -                | -         |    -7.29 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2904 | 2024-04-12 | BIG             | L   | 0.438      | -            | -                | -                | -         |    -1.57 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2937 | 2024-04-11 | Aurora          | L   | 0.430      | -            | -                | -                | -         |    -0.27 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2969 | 2024-04-10 | TSM             | W   | 0.425      | -            | -                | -                | 0 (0.000) |     2.61 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3024 | 2024-04-09 | brazylijski luz | W   | 0.418      | 0.500        | 0.008 (0.002)    | 0.261 (0.055)    | 0 (0.000) |     4.32 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3065 | 2024-04-08 | ENCE            | W   | 0.410      | 0.684        | 0.168 (0.047)    | 0.439 (0.123)    | 0 (0.000) |    12.30 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3338 | 2024-03-27 | 500             | L   | 0.331      | -            | -                | -                | -         |    -7.96 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3369 | 2024-03-26 | Apeks           | W   | 0.323      | 0.500        | 0.027 (0.004)    | 0.165 (0.027)    | 0 (0.000) |     4.90 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3375 | 2024-03-25 | B8              | L   | 0.318      | -            | -                | -                | -         |    -2.85 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3380 | 2024-03-24 | BetBoom         | W   | 0.309      | 0.143        | 0.250 (0.011)    | 0.540 (0.024)    | 0 (0.000) |     9.19 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3391 | 2024-03-23 | VP.Prodigy      | W   | 0.304      | 0.143        | -                | 0.400 (0.017)    | 0 (0.000) |     4.25 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3405 | 2024-03-22 | ex-Preasy       | W   | 0.297      | -            | -                | -                | 0 (0.000) |     3.43 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3428 | 2024-03-21 | PARIVISION      | L   | 0.291      | -            | -                | -                | -         |    -2.24 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3452 | 2024-03-20 | NAVI Junior     | W   | 0.284      | -            | -                | -                | 0 (0.000) |     1.01 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3809 | 2024-03-05 | KOI             | L   | 0.185      | -            | -                | -                | -         |    -1.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3814 | 2024-03-05 | AMKAL           | W   | 0.185      | 0.143        | 0.130 (0.003)    | 0.474 (0.013)    | 0 (0.000) |     4.61 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3821 | 2024-03-05 | 3DMAX           | W   | 0.184      | 0.143        | 0.507 (0.013)    | 1.000 (0.026)    | -         |     5.74 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3910 | 2024-03-01 | Aurora          | L   | 0.158      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3919 | 2024-02-29 | 9 Pandas        | W   | 0.152      | 0.143        | 0.081 (0.002)    | 0.690 (0.015)    | -         |     3.08 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3931 | 2024-02-28 | KOI             | W   | 0.145      | 0.143        | 0.058 (0.001)    | -                | -         |     3.42 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3936 | 2024-02-28 | Aurora          | W   | 0.144      | 0.143        | 0.423 (0.009)    | 0.792 (0.016)    | -         |     4.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3949 | 2024-02-27 | V1dar           | W   | 0.138      | -            | -                | -                | -         |     0.51 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3957 | 2024-02-27 | ARCRED          | W   | 0.138      | -            | -                | -                | -         |     2.04 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4356 | 2024-02-09 | Sashi           | L   | 0.018      | -            | -                | -                | -         |    -0.10 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4361 | 2024-02-09 | RUBY            | W   | 0.017      | -            | -                | -                | -         |     0.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4369 | 2024-02-08 | BetBoom         | W   | 0.012      | -            | -                | -                | -         |     0.35 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4374 | 2024-02-08 | Sashi           | L   | 0.010      | -            | -                | -                | -         |    -0.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,756.28)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.824 | $3,000.00      | $2,472.29       |
| 2024-05-12 |      0.637 | $7,000.00      | $4,460.56       |
| 2024-04-14 |      0.450 | $26,250.00     | $11,823.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
