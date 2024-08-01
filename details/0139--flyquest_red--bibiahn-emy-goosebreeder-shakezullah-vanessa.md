### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  756.0<br />
<br />
Final Rank Value (756.0) = Starting Rank Value (725.3) + Head To Head Adjustments (30.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 725.3
- 400 + ( ( 0.158 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 725.3


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
|           16 |     1286 | 2024-06-06 | Elevate          | L   | 0.828      | -            | -                | -                | -         |    -5.33 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           15 |     1503 | 2024-06-01 | HSG fe           | L   | 0.793      | -            | -                | -                | -         |   -10.01 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           14 |     1537 | 2024-05-31 | BIG EQUIPA       | L   | 0.787      | -            | -                | -                | -         |   -12.05 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1644 | 2024-05-26 | TSM Shimmer      | W   | 0.754      | 0.303        | 0.021 (0.005)    | 0.200 (0.046)    | 0 (0.000) |    10.81 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1647 | 2024-05-26 | Lotus fe         | W   | 0.753      | 0.303        | 0.005 (0.001)    | 0.038 (0.009)    | 0 (0.000) |     7.96 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     2646 | 2024-04-19 | Nouns fe         | W   | 0.508      | 0.322        | 0.004 (0.001)    | 0.036 (0.006)    | 0 (0.000) |     5.45 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2827 | 2024-04-14 | TSM Shimmer      | W   | 0.475      | 0.250        | 0.021 (0.002)    | 0.200 (0.024)    | 0 (0.000) |     6.99 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2910 | 2024-04-10 | cleanup crew fe  | W   | 0.448      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     4.68 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     3098 | 2024-04-04 | COVEN            | W   | 0.408      | -            | -                | -                | 0 (0.000) |     2.85 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3255 | 2024-03-28 | WG Bandits       | W   | 0.362      | -            | -                | -                | 0 (0.000) |     3.80 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3413 | 2024-03-20 | Limitless Angels | W   | 0.309      | 0.322        | 0.003 (0.000)    | 0.050 (0.005)    | 0 (0.000) |     3.74 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3559 | 2024-03-13 | Karma            | W   | 0.262      | 0.322        | 0.004 (0.000)    | 0.075 (0.006)    | 0 (0.000) |     3.27 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3741 | 2024-03-06 | TSM Shimmer      | W   | 0.216      | 0.322        | 0.021 (0.001)    | 0.200 (0.014)    | 0 (0.000) |     3.19 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3830 | 2024-03-03 | TSM Shimmer      | W   | 0.195      | 0.250        | 0.021 (0.001)    | 0.200 (0.010)    | -         |     2.94 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3973 | 2024-02-25 | TSM Shimmer      | W   | 0.148      | 0.250        | 0.021 (0.001)    | 0.200 (0.007)    | -         |     2.27 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4408 | 2024-02-04 | TSM Shimmer      | W   | 0.008      | -            | -                | -                | -         |     0.13 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,709.59)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.801 | $4,000.00      | $3,204.44       |
| 2024-05-26 |      0.754 | $2,500.00      | $1,885.30       |
| 2024-04-14 |      0.475 | $750.00        | $356.04         |
| 2024-03-03 |      0.195 | $750.00        | $146.27         |
| 2024-02-25 |      0.148 | $750.00        | $111.25         |
| 2024-02-04 |      0.008 | $750.00        | $6.28           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
