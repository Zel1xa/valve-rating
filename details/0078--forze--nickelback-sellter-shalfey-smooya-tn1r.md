### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  935.2<br />
<br />
Final Rank Value (935.2) = Starting Rank Value (885.8) + Head To Head Adjustments (49.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.382[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 885.8
- 400 + ( ( 0.238 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 885.8


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
|           30 |     2332 | 2024-05-04 | Monte           | L   | 0.590      | -            | -                | -                | -         |    -7.67 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2360 | 2024-05-02 | GamerLegion     | L   | 0.579      | -            | -                | -                | -         |    -4.81 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2386 | 2024-05-01 | FURIA           | W   | 0.572      | 0.889        | 0.284 (0.144)    | 0.491 (0.250)    | 1 (0.572) |    17.67 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2409 | 2024-04-30 | Monte           | L   | 0.565      | -            | -                | -                | -         |    -7.33 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2863 | 2024-04-12 | BIG             | L   | 0.445      | -            | -                | -                | -         |    -1.61 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2896 | 2024-04-11 | Aurora          | L   | 0.437      | -            | -                | -                | -         |    -0.28 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2928 | 2024-04-10 | TSM             | W   | 0.432      | -            | -                | -                | 0 (0.000) |     2.63 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2983 | 2024-04-09 | brazylijski luz | W   | 0.425      | 0.500        | 0.008 (0.002)    | 0.262 (0.056)    | 0 (0.000) |     4.32 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3024 | 2024-04-08 | ENCE            | W   | 0.417      | 0.684        | 0.170 (0.048)    | 0.401 (0.114)    | 0 (0.000) |    12.48 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3297 | 2024-03-27 | 500             | L   | 0.339      | -            | -                | -                | -         |    -8.14 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3328 | 2024-03-26 | Apeks           | W   | 0.331      | 0.500        | 0.027 (0.004)    | 0.168 (0.028)    | 0 (0.000) |     5.03 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3334 | 2024-03-25 | B8              | L   | 0.325      | -            | -                | -                | -         |    -2.93 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3339 | 2024-03-24 | BetBoom         | W   | 0.317      | 0.143        | 0.252 (0.011)    | 0.543 (0.025)    | 0 (0.000) |     9.40 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3350 | 2024-03-23 | VP.Prodigy      | W   | 0.311      | 0.143        | -                | 0.402 (0.018)    | 0 (0.000) |     4.32 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3364 | 2024-03-22 | ex-Preasy       | W   | 0.304      | -            | -                | -                | 0 (0.000) |     3.55 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3387 | 2024-03-21 | PARIVISION      | L   | 0.298      | -            | -                | -                | -         |    -2.33 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3411 | 2024-03-20 | NAVI Junior     | W   | 0.291      | -            | -                | -                | 0 (0.000) |     1.03 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3767 | 2024-03-05 | KOI             | L   | 0.192      | -            | -                | -                | -         |    -1.65 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3772 | 2024-03-05 | AMKAL           | W   | 0.192      | 0.143        | 0.130 (0.004)    | 0.477 (0.013)    | 0 (0.000) |     4.79 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3779 | 2024-03-05 | 3DMAX           | W   | 0.192      | 0.143        | 0.505 (0.014)    | 1.000 (0.027)    | -         |     5.96 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3868 | 2024-03-01 | Aurora          | L   | 0.165      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3877 | 2024-02-29 | 9 Pandas        | W   | 0.159      | 0.143        | 0.082 (0.002)    | 0.691 (0.016)    | -         |     3.23 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3889 | 2024-02-28 | KOI             | W   | 0.152      | 0.143        | 0.059 (0.001)    | -                | -         |     3.60 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3894 | 2024-02-28 | Aurora          | W   | 0.151      | 0.143        | 0.424 (0.009)    | 0.794 (0.017)    | -         |     4.70 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3907 | 2024-02-27 | V1dar           | W   | 0.145      | -            | -                | -                | -         |     0.53 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3915 | 2024-02-27 | ARCRED          | W   | 0.145      | -            | -                | -                | -         |     2.15 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4313 | 2024-02-09 | Sashi           | L   | 0.025      | -            | -                | -                | -         |    -0.14 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4318 | 2024-02-09 | RUBY            | W   | 0.024      | -            | -                | -                | -         |     0.43 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4326 | 2024-02-08 | BetBoom         | W   | 0.019      | -            | -                | -                | -         |     0.56 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4331 | 2024-02-08 | Sashi           | L   | 0.018      | -            | -                | -                | -         |    -0.10 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,018.09)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $3,000.00      | $2,493.96       |
| 2024-05-12 |      0.644 | $7,000.00      | $4,511.11       |
| 2024-04-14 |      0.458 | $26,250.00     | $12,013.02      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
