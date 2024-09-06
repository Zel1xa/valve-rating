### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [110](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [80]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  810.6<br />
<br />
Final Rank Value (810.6) = Starting Rank Value (796.1) + Head To Head Adjustments (14.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.407[<sup>1</sup>](#table2)
- Bounty Collected: 0.343[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 796.1
- 400 + ( ( 0.203 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 796.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     3498 | 2024-05-04 | Monte       | L   | 0.365      | -            | -                | -                | -         |    -3.57 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           16 |     3526 | 2024-05-02 | GamerLegion | L   | 0.353      | -            | -                | -                | -         |    -2.37 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           15 |     3552 | 2024-05-01 | FURIA       | W   | 0.347      | 0.889        | 0.318 (0.098)    | 0.530 (0.163)    | 1 (0.347) |    10.80 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           14 |     3575 | 2024-04-30 | Monte       | L   | 0.340      | -            | -                | -                | -         |    -3.28 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           13 |     4030 | 2024-04-12 | BIG         | L   | 0.219      | -            | -                | -                | -         |    -0.66 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           12 |     4063 | 2024-04-11 | Aurora      | L   | 0.212      | -            | -                | -                | -         |    -0.21 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           11 |     4095 | 2024-04-10 | TSM         | W   | 0.207      | 0.500        | 0.004 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     1.81 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           10 |     4150 | 2024-04-09 | Apogee      | W   | 0.200      | 0.500        | 0.006 (0.001)    | 0.207 (0.021)    | 0 (0.000) |     2.66 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|            9 |     4191 | 2024-04-08 | ENCE        | W   | 0.192      | 0.684        | 0.131 (0.017)    | 0.342 (0.045)    | 0 (0.000) |     5.62 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|            8 |     4464 | 2024-03-27 | 500         | L   | 0.113      | -            | -                | -                | -         |    -2.48 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     4495 | 2024-03-26 | Apeks       | W   | 0.105      | 0.500        | 0.014 (0.001)    | 0.072 (0.004)    | 0 (0.000) |     1.50 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     4501 | 2024-03-25 | B8          | L   | 0.099      | -            | -                | -                | -         |    -0.59 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     4506 | 2024-03-24 | BetBoom     | W   | 0.091      | 0.143        | 0.230 (0.003)    | 0.555 (0.007)    | 0 (0.000) |     2.66 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4517 | 2024-03-23 | VP.Prodigy  | W   | 0.086      | 0.143        | 0.020 (0.000)    | 0.257 (0.003)    | 0 (0.000) |     1.46 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4531 | 2024-03-22 | ex-Preasy   | W   | 0.079      | 0.143        | 0.003 (0.000)    | 0.019 (0.000)    | 0 (0.000) |     0.83 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4554 | 2024-03-21 | PARIVISION  | L   | 0.072      | -            | -                | -                | -         |    -0.36 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4578 | 2024-03-20 | NAVI Junior | W   | 0.066      | 0.143        | 0.001 (0.000)    | 0.111 (0.001)    | 0 (0.000) |     0.71 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,850.93)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.606 | $3,000.00      | $1,818.06       |
| 2024-05-12 |      0.419 | $7,000.00      | $2,934.00       |
| 2024-04-14 |      0.232 | $26,250.00     | $6,098.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
