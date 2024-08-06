### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  749.1<br />
<br />
Final Rank Value (749.1) = Starting Rank Value (721.3) + Head To Head Adjustments (27.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.3
- 400 + ( ( 0.157 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 721.3


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
|           15 |     1416 | 2024-06-06 | Elevate          | L   | 0.797      | -            | -                | -                | -         |    -5.20 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1625 | 2024-06-01 | HSG fe           | L   | 0.762      | -            | -                | -                | -         |    -9.62 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1662 | 2024-05-31 | BIG EQUIPA       | L   | 0.755      | -            | -                | -                | -         |   -11.56 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1767 | 2024-05-26 | TSM Shimmer      | W   | 0.723      | 0.303        | 0.020 (0.004)    | 0.195 (0.043)    | 0 (0.000) |    10.49 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1770 | 2024-05-26 | Lotus fe         | W   | 0.722      | 0.303        | 0.004 (0.001)    | 0.038 (0.008)    | 0 (0.000) |     7.82 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2723 | 2024-04-19 | Nouns fe         | W   | 0.477      | 0.322        | 0.003 (0.001)    | 0.033 (0.005)    | 0 (0.000) |     5.21 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2900 | 2024-04-14 | TSM Shimmer      | W   | 0.443      | 0.250        | 0.020 (0.002)    | 0.195 (0.022)    | 0 (0.000) |     6.60 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2982 | 2024-04-10 | cleanup crew fe  | W   | 0.417      | 0.322        | 0.002 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     4.44 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3170 | 2024-04-04 | COVEN            | W   | 0.377      | -            | -                | -                | 0 (0.000) |     2.72 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3319 | 2024-03-28 | WG Bandits       | W   | 0.331      | -            | -                | -                | 0 (0.000) |     3.54 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3472 | 2024-03-20 | Limitless Angels | W   | 0.277      | 0.322        | 0.003 (0.000)    | 0.046 (0.004)    | 0 (0.000) |     3.39 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3614 | 2024-03-13 | Karma            | W   | 0.231      | 0.322        | 0.004 (0.000)    | 0.070 (0.005)    | 0 (0.000) |     2.91 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3794 | 2024-03-06 | TSM Shimmer      | W   | 0.184      | 0.322        | 0.020 (0.001)    | 0.195 (0.012)    | 0 (0.000) |     2.76 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3878 | 2024-03-03 | TSM Shimmer      | W   | 0.164      | 0.250        | 0.020 (0.001)    | 0.195 (0.008)    | -         |     2.49 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4018 | 2024-02-25 | TSM Shimmer      | W   | 0.117      | 0.250        | 0.020 (0.001)    | 0.195 (0.006)    | -         |     1.80 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,428.65)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.770 | $4,000.00      | $3,078.89       |
| 2024-05-26 |      0.723 | $2,500.00      | $1,806.83       |
| 2024-04-14 |      0.443 | $750.00        | $332.50         |
| 2024-03-03 |      0.164 | $750.00        | $122.73         |
| 2024-02-25 |      0.117 | $750.00        | $87.71          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
