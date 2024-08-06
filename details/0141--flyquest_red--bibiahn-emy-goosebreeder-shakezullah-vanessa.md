### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [141](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  749.6<br />
<br />
Final Rank Value (749.6) = Starting Rank Value (721.9) + Head To Head Adjustments (27.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.9
- 400 + ( ( 0.156 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 721.9


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
|           15 |     1420 | 2024-06-06 | Elevate          | L   | 0.796      | -            | -                | -                | -         |    -5.22 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1629 | 2024-06-01 | HSG fe           | L   | 0.761      | -            | -                | -                | -         |    -9.60 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1666 | 2024-05-31 | BIG EQUIPA       | L   | 0.755      | -            | -                | -                | -         |   -11.55 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1771 | 2024-05-26 | TSM Shimmer      | W   | 0.722      | 0.303        | 0.020 (0.004)    | 0.191 (0.042)    | 0 (0.000) |    10.49 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1774 | 2024-05-26 | Lotus fe         | W   | 0.722      | 0.303        | 0.004 (0.001)    | 0.037 (0.008)    | 0 (0.000) |     7.82 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2727 | 2024-04-19 | Nouns fe         | W   | 0.477      | 0.322        | 0.003 (0.001)    | 0.032 (0.005)    | 0 (0.000) |     5.21 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2904 | 2024-04-14 | TSM Shimmer      | W   | 0.443      | 0.250        | 0.020 (0.002)    | 0.191 (0.021)    | 0 (0.000) |     6.60 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2986 | 2024-04-10 | cleanup crew fe  | W   | 0.417      | 0.322        | 0.002 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     4.44 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3174 | 2024-04-04 | COVEN            | W   | 0.377      | -            | -                | -                | 0 (0.000) |     2.71 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3323 | 2024-03-28 | WG Bandits       | W   | 0.330      | -            | -                | -                | 0 (0.000) |     3.53 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3476 | 2024-03-20 | Limitless Angels | W   | 0.277      | 0.322        | 0.003 (0.000)    | 0.045 (0.004)    | 0 (0.000) |     3.38 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3618 | 2024-03-13 | Karma            | W   | 0.230      | 0.322        | 0.004 (0.000)    | 0.068 (0.005)    | 0 (0.000) |     2.90 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3798 | 2024-03-06 | TSM Shimmer      | W   | 0.184      | 0.322        | 0.020 (0.001)    | 0.191 (0.011)    | 0 (0.000) |     2.75 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3882 | 2024-03-03 | TSM Shimmer      | W   | 0.163      | 0.250        | 0.020 (0.001)    | 0.191 (0.008)    | -         |     2.48 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4022 | 2024-02-25 | TSM Shimmer      | W   | 0.117      | 0.250        | 0.020 (0.001)    | 0.191 (0.006)    | -         |     1.79 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,426.22)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.769 | $4,000.00      | $3,077.78       |
| 2024-05-26 |      0.722 | $2,500.00      | $1,806.13       |
| 2024-04-14 |      0.443 | $750.00        | $332.29         |
| 2024-03-03 |      0.163 | $750.00        | $122.52         |
| 2024-02-25 |      0.117 | $750.00        | $87.50          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />