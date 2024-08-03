### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  750.9<br />
<br />
Final Rank Value (750.9) = Starting Rank Value (722.2) + Head To Head Adjustments (28.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.2
- 400 + ( ( 0.157 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 722.2


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
|           15 |     1288 | 2024-06-06 | Elevate          | L   | 0.815      | -            | -                | -                | -         |    -5.95 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1495 | 2024-06-01 | HSG fe           | L   | 0.780      | -            | -                | -                | -         |    -9.89 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1531 | 2024-05-31 | BIG EQUIPA       | L   | 0.773      | -            | -                | -                | -         |   -11.86 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1636 | 2024-05-26 | TSM Shimmer      | W   | 0.741      | 0.303        | 0.020 (0.005)    | 0.206 (0.046)    | 0 (0.000) |    10.68 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1639 | 2024-05-26 | Lotus fe         | W   | 0.740      | 0.303        | 0.005 (0.001)    | 0.039 (0.009)    | 0 (0.000) |     7.91 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2588 | 2024-04-19 | Nouns fe         | W   | 0.495      | 0.322        | 0.003 (0.001)    | 0.036 (0.006)    | 0 (0.000) |     5.36 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2765 | 2024-04-14 | TSM Shimmer      | W   | 0.461      | 0.250        | 0.020 (0.002)    | 0.206 (0.024)    | 0 (0.000) |     6.83 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2847 | 2024-04-10 | cleanup crew fe  | W   | 0.435      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     4.59 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3035 | 2024-04-04 | COVEN            | W   | 0.395      | -            | -                | -                | 0 (0.000) |     2.81 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3184 | 2024-03-28 | WG Bandits       | W   | 0.349      | -            | -                | -                | 0 (0.000) |     3.69 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3332 | 2024-03-20 | Limitless Angels | W   | 0.295      | 0.322        | 0.003 (0.000)    | 0.051 (0.005)    | 0 (0.000) |     3.59 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3473 | 2024-03-13 | Karma            | W   | 0.249      | 0.322        | 0.004 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     3.12 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3651 | 2024-03-06 | TSM Shimmer      | W   | 0.202      | 0.322        | 0.020 (0.001)    | 0.206 (0.013)    | 0 (0.000) |     3.01 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3735 | 2024-03-03 | TSM Shimmer      | W   | 0.182      | 0.250        | 0.020 (0.001)    | 0.206 (0.009)    | -         |     2.75 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     3875 | 2024-02-25 | TSM Shimmer      | W   | 0.135      | 0.250        | 0.020 (0.001)    | 0.206 (0.007)    | -         |     2.07 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,587.04)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.788 | $4,000.00      | $3,151.30       |
| 2024-05-26 |      0.741 | $2,500.00      | $1,852.08       |
| 2024-04-14 |      0.461 | $750.00        | $346.08         |
| 2024-03-03 |      0.182 | $750.00        | $136.30         |
| 2024-02-25 |      0.135 | $750.00        | $101.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
