### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  749.4<br />
<br />
Final Rank Value (749.4) = Starting Rank Value (721.4) + Head To Head Adjustments (28.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.4
- 400 + ( ( 0.157 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 721.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1412 | 2024-06-06 | Elevate          | L   | 0.799      | -            | -                | -                | -         |    -5.22 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1621 | 2024-06-01 | HSG fe           | L   | 0.764      | -            | -                | -                | -         |    -9.65 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1658 | 2024-05-31 | BIG EQUIPA       | L   | 0.758      | -            | -                | -                | -         |   -11.60 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1763 | 2024-05-26 | TSM Shimmer      | W   | 0.725      | 0.303        | 0.020 (0.004)    | 0.195 (0.043)    | 0 (0.000) |    10.52 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1766 | 2024-05-26 | Lotus fe         | W   | 0.725      | 0.303        | 0.004 (0.001)    | 0.038 (0.008)    | 0 (0.000) |     7.83 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2719 | 2024-04-19 | Nouns fe         | W   | 0.480      | 0.322        | 0.003 (0.001)    | 0.033 (0.005)    | 0 (0.000) |     5.23 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2896 | 2024-04-14 | TSM Shimmer      | W   | 0.446      | 0.250        | 0.020 (0.002)    | 0.195 (0.022)    | 0 (0.000) |     6.63 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2978 | 2024-04-10 | cleanup crew fe  | W   | 0.420      | 0.322        | 0.002 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     4.46 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3166 | 2024-04-04 | COVEN            | W   | 0.380      | -            | -                | -                | 0 (0.000) |     2.73 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3315 | 2024-03-28 | WG Bandits       | W   | 0.333      | -            | -                | -                | 0 (0.000) |     3.56 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3468 | 2024-03-20 | Limitless Angels | W   | 0.280      | 0.322        | 0.003 (0.000)    | 0.046 (0.004)    | 0 (0.000) |     3.42 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3610 | 2024-03-13 | Karma            | W   | 0.233      | 0.322        | 0.004 (0.000)    | 0.070 (0.005)    | 0 (0.000) |     2.94 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3790 | 2024-03-06 | TSM Shimmer      | W   | 0.187      | 0.322        | 0.020 (0.001)    | 0.195 (0.012)    | 0 (0.000) |     2.79 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3874 | 2024-03-03 | TSM Shimmer      | W   | 0.166      | 0.250        | 0.020 (0.001)    | 0.195 (0.008)    | -         |     2.52 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4014 | 2024-02-25 | TSM Shimmer      | W   | 0.119      | 0.250        | 0.020 (0.001)    | 0.195 (0.006)    | -         |     1.83 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,450.53)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.772 | $4,000.00      | $3,088.89       |
| 2024-05-26 |      0.725 | $2,500.00      | $1,813.08       |
| 2024-04-14 |      0.446 | $750.00        | $334.38         |
| 2024-03-03 |      0.166 | $750.00        | $124.60         |
| 2024-02-25 |      0.119 | $750.00        | $89.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
