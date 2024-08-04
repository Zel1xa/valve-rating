### Roster Details<br />
Team Name: dream catchers fe<br />
Roster: Elizabeth, f6tal, k175un4, sosya, wieenN<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
<br />
Final Rank Value:  743.2<br />
<br />
Final Rank Value (743.2) = Starting Rank Value (716.4) + Head To Head Adjustments (26.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.357[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 716.4
- 400 + ( ( 0.155 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 716.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      455 | 2024-07-21 | France fe   | W   | 1.000      | 0.294        | 0.006 (0.002)    | 0.118 (0.035)    | 0 (0.000) |    13.44 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|           10 |      460 | 2024-07-21 | Spirit fe   | W   | 1.000      | 0.294        | 0.005 (0.001)    | 0.140 (0.041)    | 0 (0.000) |    11.63 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|            9 |      494 | 2024-07-20 | BIG EQUIPA  | W   | 1.000      | 0.294        | 0.017 (0.005)    | 0.152 (0.045)    | 0 (0.000) |    18.23 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|            8 |      770 | 2024-07-14 | CENSORED fe | L   | 1.000      | -            | -                | -                | -         |   -15.96 | Elizabeth, f6tal, k175un4, t4tty, wieenN |
|            7 |      899 | 2024-06-30 | YeYO        | W   | 0.972      | 0.250        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.79 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|            6 |      960 | 2024-06-16 | NIP Impact  | L   | 0.878      | -            | -                | -                | -         |   -13.61 | k175un4, sosya, Stormy, unknxwn, wieenN  |
|            5 |     2837 | 2024-04-14 | Spirit fe   | W   | 0.458      | 0.250        | 0.005 (0.001)    | 0.140 (0.016)    | 0 (0.000) |     5.85 | k175un4, sosya, Stormy, trigusha, wieenN |
|            4 |     3048 | 2024-04-07 | ENCE Athena | W   | 0.412      | 0.250        | 0.002 (0.000)    | 0.036 (0.004)    | 0 (0.000) |     5.08 | k175un4, sosya, Stormy, trigusha, wieenN |
|            3 |     3814 | 2024-03-03 | BIG EQUIPA  | L   | 0.179      | -            | -                | -                | -         |    -2.37 | k175un4, sosya, Stormy, trigusha, wieenN |
|            2 |     4116 | 2024-02-18 | Astralis W  | L   | 0.086      | -            | -                | -                | -         |    -1.70 | k175un4, mikeri, sosya, Stormy, wieenN   |
|            1 |     4120 | 2024-02-18 | Crescent fe | L   | 0.085      | -            | -                | -                | -         |    -1.53 | k175un4, mikeri, sosya, Stormy, wieenN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,145.20)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $500.00        | $500.00         |
| 2024-06-30 |      0.972 | $750.00        | $728.73         |
| 2024-06-16 |      0.878 | $250.00        | $219.52         |
| 2024-04-14 |      0.458 | $750.00        | $343.13         |
| 2024-04-07 |      0.412 | $750.00        | $309.11         |
| 2024-03-03 |      0.179 | $250.00        | $44.70          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
