### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [110](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [80]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  809.5<br />
<br />
Final Rank Value (809.5) = Starting Rank Value (795.3) + Head To Head Adjustments (14.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.407[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 795.3
- 400 + ( ( 0.202 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 795.3


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
|           17 |     3503 | 2024-05-04 | Monte       | L   | 0.361      | -            | -                | -                | -         |    -3.54 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           16 |     3531 | 2024-05-02 | GamerLegion | L   | 0.349      | -            | -                | -                | -         |    -2.26 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           15 |     3557 | 2024-05-01 | FURIA       | W   | 0.343      | 0.889        | 0.319 (0.097)    | 0.530 (0.161)    | 1 (0.343) |    10.68 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           14 |     3580 | 2024-04-30 | Monte       | L   | 0.336      | -            | -                | -                | -         |    -3.24 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           13 |     4035 | 2024-04-12 | BIG         | L   | 0.215      | -            | -                | -                | -         |    -0.65 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           12 |     4068 | 2024-04-11 | Aurora      | L   | 0.208      | -            | -                | -                | -         |    -0.20 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           11 |     4100 | 2024-04-10 | TSM         | W   | 0.203      | 0.500        | 0.004 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     1.78 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           10 |     4155 | 2024-04-09 | Apogee      | W   | 0.196      | 0.500        | 0.006 (0.001)    | 0.206 (0.020)    | 0 (0.000) |     2.61 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|            9 |     4196 | 2024-04-08 | ENCE        | W   | 0.188      | 0.684        | 0.131 (0.017)    | 0.342 (0.044)    | 0 (0.000) |     5.50 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|            8 |     4469 | 2024-03-27 | 500         | L   | 0.109      | -            | -                | -                | -         |    -2.39 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     4500 | 2024-03-26 | Apeks       | W   | 0.101      | 0.500        | 0.013 (0.001)    | 0.071 (0.004)    | 0 (0.000) |     1.44 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     4506 | 2024-03-25 | B8          | L   | 0.095      | -            | -                | -                | -         |    -0.57 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     4511 | 2024-03-24 | BetBoom     | W   | 0.087      | 0.143        | 0.230 (0.003)    | 0.554 (0.007)    | 0 (0.000) |     2.54 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4522 | 2024-03-23 | VP.Prodigy  | W   | 0.082      | 0.143        | 0.020 (0.000)    | 0.255 (0.003)    | 0 (0.000) |     1.39 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4536 | 2024-03-22 | ex-Preasy   | W   | 0.075      | 0.143        | 0.003 (0.000)    | 0.018 (0.000)    | 0 (0.000) |     0.79 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4559 | 2024-03-21 | PARIVISION  | L   | 0.068      | -            | -                | -                | -         |    -0.34 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4583 | 2024-03-20 | NAVI Junior | W   | 0.062      | 0.143        | 0.001 (0.000)    | 0.110 (0.001)    | 0 (0.000) |     0.67 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,705.76)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.602 | $3,000.00      | $1,806.04       |
| 2024-05-12 |      0.415 | $7,000.00      | $2,905.97       |
| 2024-04-14 |      0.228 | $26,250.00     | $5,993.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
