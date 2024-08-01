### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [138](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  756.6<br />
<br />
Final Rank Value (756.6) = Starting Rank Value (725.8) + Head To Head Adjustments (30.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 725.8
- 400 + ( ( 0.158 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 725.8


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
|           16 |     1282 | 2024-06-06 | Elevate          | L   | 0.829      | -            | -                | -                | -         |    -5.34 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           15 |     1499 | 2024-06-01 | HSG fe           | L   | 0.794      | -            | -                | -                | -         |   -10.02 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           14 |     1533 | 2024-05-31 | BIG EQUIPA       | L   | 0.788      | -            | -                | -                | -         |   -12.07 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1640 | 2024-05-26 | TSM Shimmer      | W   | 0.756      | 0.303        | 0.021 (0.005)    | 0.200 (0.046)    | 0 (0.000) |    10.82 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1643 | 2024-05-26 | Lotus fe         | W   | 0.755      | 0.303        | 0.005 (0.001)    | 0.038 (0.009)    | 0 (0.000) |     7.97 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     2642 | 2024-04-19 | Nouns fe         | W   | 0.510      | 0.322        | 0.004 (0.001)    | 0.036 (0.006)    | 0 (0.000) |     5.46 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2823 | 2024-04-14 | TSM Shimmer      | W   | 0.476      | 0.250        | 0.021 (0.002)    | 0.200 (0.024)    | 0 (0.000) |     7.01 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2906 | 2024-04-10 | cleanup crew fe  | W   | 0.450      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     4.69 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     3094 | 2024-04-04 | COVEN            | W   | 0.410      | -            | -                | -                | 0 (0.000) |     2.86 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3251 | 2024-03-28 | WG Bandits       | W   | 0.363      | -            | -                | -                | 0 (0.000) |     3.81 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3409 | 2024-03-20 | Limitless Angels | W   | 0.310      | 0.322        | 0.003 (0.000)    | 0.050 (0.005)    | 0 (0.000) |     3.75 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3555 | 2024-03-13 | Karma            | W   | 0.263      | 0.322        | 0.004 (0.000)    | 0.075 (0.006)    | 0 (0.000) |     3.29 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3737 | 2024-03-06 | TSM Shimmer      | W   | 0.217      | 0.322        | 0.021 (0.001)    | 0.200 (0.014)    | 0 (0.000) |     3.21 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3826 | 2024-03-03 | TSM Shimmer      | W   | 0.196      | 0.250        | 0.021 (0.001)    | 0.200 (0.010)    | -         |     2.96 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3969 | 2024-02-25 | TSM Shimmer      | W   | 0.150      | 0.250        | 0.021 (0.001)    | 0.200 (0.007)    | -         |     2.29 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4404 | 2024-02-04 | TSM Shimmer      | W   | 0.010      | -            | -                | -                | -         |     0.15 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,722.78)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.802 | $4,000.00      | $3,210.00       |
| 2024-05-26 |      0.756 | $2,500.00      | $1,888.77       |
| 2024-04-14 |      0.476 | $750.00        | $357.08         |
| 2024-03-03 |      0.196 | $750.00        | $147.31         |
| 2024-02-25 |      0.150 | $750.00        | $112.29         |
| 2024-02-04 |      0.010 | $750.00        | $7.33           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
