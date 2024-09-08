### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [109](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [78]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  802.5<br />
<br />
Final Rank Value (802.5) = Starting Rank Value (788.9) + Head To Head Adjustments (13.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.406[<sup>1</sup>](#table2)
- Bounty Collected: 0.340[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 788.9
- 400 + ( ( 0.201 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 788.9


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
|           17 |     3535 | 2024-05-04 | Monte       | L   | 0.353      | -            | -                | -                | -         |    -3.48 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           16 |     3563 | 2024-05-02 | GamerLegion | L   | 0.341      | -            | -                | -                | -         |    -2.08 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           15 |     3589 | 2024-05-01 | FURIA       | W   | 0.335      | 0.889        | 0.319 (0.095)    | 0.513 (0.152)    | 1 (0.335) |    10.43 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           14 |     3612 | 2024-04-30 | Monte       | L   | 0.328      | -            | -                | -                | -         |    -3.18 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           13 |     4067 | 2024-04-12 | BIG         | L   | 0.208      | -            | -                | -                | -         |    -0.64 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           12 |     4100 | 2024-04-11 | Aurora      | L   | 0.200      | -            | -                | -                | -         |    -0.21 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           11 |     4132 | 2024-04-10 | TSM         | W   | 0.195      | 0.500        | 0.004 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     1.74 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           10 |     4187 | 2024-04-09 | Apogee      | W   | 0.188      | 0.500        | 0.006 (0.001)    | 0.198 (0.019)    | 0 (0.000) |     2.51 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|            9 |     4228 | 2024-04-08 | ENCE        | W   | 0.180      | 0.684        | 0.130 (0.016)    | 0.330 (0.041)    | 0 (0.000) |     5.25 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|            8 |     4501 | 2024-03-27 | 500         | L   | 0.101      | -            | -                | -                | -         |    -2.20 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     4532 | 2024-03-26 | Apeks       | W   | 0.093      | 0.500        | 0.013 (0.001)    | 0.067 (0.003)    | 0 (0.000) |     1.33 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     4538 | 2024-03-25 | B8          | L   | 0.087      | -            | -                | -                | -         |    -0.49 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     4543 | 2024-03-24 | BetBoom     | W   | 0.079      | 0.143        | 0.229 (0.003)    | 0.535 (0.006)    | 0 (0.000) |     2.30 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4554 | 2024-03-23 | VP.Prodigy  | W   | 0.074      | 0.143        | 0.020 (0.000)    | 0.245 (0.003)    | 0 (0.000) |     1.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4568 | 2024-03-22 | ex-Preasy   | W   | 0.067      | 0.143        | 0.003 (0.000)    | 0.016 (0.000)    | 0 (0.000) |     0.71 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4591 | 2024-03-21 | PARIVISION  | L   | 0.061      | -            | -                | -                | -         |    -0.31 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4615 | 2024-03-20 | NAVI Junior | W   | 0.054      | 0.143        | 0.001 (0.000)    | 0.144 (0.001)    | 0 (0.000) |     0.59 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,418.78)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.594 | $3,000.00      | $1,782.29       |
| 2024-05-12 |      0.407 | $7,000.00      | $2,850.56       |
| 2024-04-14 |      0.220 | $26,250.00     | $5,785.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
