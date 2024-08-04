### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  750.3<br />
<br />
Final Rank Value (750.3) = Starting Rank Value (721.3) + Head To Head Adjustments (28.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.3
- 400 + ( ( 0.157 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 721.3


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
|           15 |     1352 | 2024-06-06 | Elevate          | L   | 0.810      | -            | -                | -                | -         |    -5.31 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1561 | 2024-06-01 | HSG fe           | L   | 0.775      | -            | -                | -                | -         |    -9.83 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1598 | 2024-05-31 | BIG EQUIPA       | L   | 0.768      | -            | -                | -                | -         |   -11.78 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1703 | 2024-05-26 | TSM Shimmer      | W   | 0.736      | 0.303        | 0.020 (0.005)    | 0.199 (0.044)    | 0 (0.000) |    10.63 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1706 | 2024-05-26 | Lotus fe         | W   | 0.735      | 0.303        | 0.005 (0.001)    | 0.038 (0.009)    | 0 (0.000) |     7.89 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2659 | 2024-04-19 | Nouns fe         | W   | 0.490      | 0.322        | 0.003 (0.001)    | 0.035 (0.005)    | 0 (0.000) |     5.33 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2836 | 2024-04-14 | TSM Shimmer      | W   | 0.457      | 0.250        | 0.020 (0.002)    | 0.199 (0.023)    | 0 (0.000) |     6.77 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2918 | 2024-04-10 | cleanup crew fe  | W   | 0.430      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.55 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3106 | 2024-04-04 | COVEN            | W   | 0.390      | -            | -                | -                | 0 (0.000) |     2.79 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3255 | 2024-03-28 | WG Bandits       | W   | 0.344      | -            | -                | -                | 0 (0.000) |     3.66 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3408 | 2024-03-20 | Limitless Angels | W   | 0.291      | 0.322        | 0.003 (0.000)    | 0.048 (0.005)    | 0 (0.000) |     3.54 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3550 | 2024-03-13 | Karma            | W   | 0.244      | 0.322        | 0.004 (0.000)    | 0.073 (0.006)    | 0 (0.000) |     3.07 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3730 | 2024-03-06 | TSM Shimmer      | W   | 0.198      | 0.322        | 0.020 (0.001)    | 0.199 (0.013)    | 0 (0.000) |     2.95 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3814 | 2024-03-03 | TSM Shimmer      | W   | 0.177      | 0.250        | 0.020 (0.001)    | 0.199 (0.009)    | -         |     2.68 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     3954 | 2024-02-25 | TSM Shimmer      | W   | 0.130      | 0.250        | 0.020 (0.001)    | 0.199 (0.006)    | -         |     2.00 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,545.32)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.783 | $4,000.00      | $3,132.22       |
| 2024-05-26 |      0.736 | $2,500.00      | $1,840.16       |
| 2024-04-14 |      0.457 | $750.00        | $342.50         |
| 2024-03-03 |      0.177 | $750.00        | $132.73         |
| 2024-02-25 |      0.130 | $750.00        | $97.71          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
