### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  749.5<br />
<br />
Final Rank Value (749.5) = Starting Rank Value (721.2) + Head To Head Adjustments (28.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.2
- 400 + ( ( 0.157 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 721.2


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
|           15 |     1401 | 2024-06-06 | Elevate          | L   | 0.802      | -            | -                | -                | -         |    -5.24 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1610 | 2024-06-01 | HSG fe           | L   | 0.767      | -            | -                | -                | -         |    -9.71 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1647 | 2024-05-31 | BIG EQUIPA       | L   | 0.761      | -            | -                | -                | -         |   -11.66 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1752 | 2024-05-26 | TSM Shimmer      | W   | 0.729      | 0.303        | 0.020 (0.004)    | 0.198 (0.044)    | 0 (0.000) |    10.55 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1755 | 2024-05-26 | Lotus fe         | W   | 0.728      | 0.303        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |     7.85 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2708 | 2024-04-19 | Nouns fe         | W   | 0.483      | 0.322        | 0.003 (0.001)    | 0.034 (0.005)    | 0 (0.000) |     5.26 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2885 | 2024-04-14 | TSM Shimmer      | W   | 0.449      | 0.250        | 0.020 (0.002)    | 0.198 (0.022)    | 0 (0.000) |     6.68 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2967 | 2024-04-10 | cleanup crew fe  | W   | 0.423      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.49 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3155 | 2024-04-04 | COVEN            | W   | 0.383      | -            | -                | -                | 0 (0.000) |     2.75 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3304 | 2024-03-28 | WG Bandits       | W   | 0.337      | -            | -                | -                | 0 (0.000) |     3.59 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3457 | 2024-03-20 | Limitless Angels | W   | 0.283      | 0.322        | 0.003 (0.000)    | 0.047 (0.004)    | 0 (0.000) |     3.46 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3599 | 2024-03-13 | Karma            | W   | 0.237      | 0.322        | 0.004 (0.000)    | 0.071 (0.005)    | 0 (0.000) |     2.98 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3779 | 2024-03-06 | TSM Shimmer      | W   | 0.190      | 0.322        | 0.020 (0.001)    | 0.198 (0.012)    | 0 (0.000) |     2.84 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3863 | 2024-03-03 | TSM Shimmer      | W   | 0.169      | 0.250        | 0.020 (0.001)    | 0.198 (0.008)    | -         |     2.57 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4003 | 2024-02-25 | TSM Shimmer      | W   | 0.123      | 0.250        | 0.020 (0.001)    | 0.198 (0.006)    | -         |     1.89 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,479.69)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.776 | $4,000.00      | $3,102.22       |
| 2024-05-26 |      0.729 | $2,500.00      | $1,821.41       |
| 2024-04-14 |      0.449 | $750.00        | $336.88         |
| 2024-03-03 |      0.169 | $750.00        | $127.10         |
| 2024-02-25 |      0.123 | $750.00        | $92.08          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
