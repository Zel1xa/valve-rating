### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  749.6<br />
<br />
Final Rank Value (749.6) = Starting Rank Value (721.4) + Head To Head Adjustments (28.2)<br />

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
|           15 |     1409 | 2024-06-06 | Elevate          | L   | 0.801      | -            | -                | -                | -         |    -5.24 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1618 | 2024-06-01 | HSG fe           | L   | 0.766      | -            | -                | -                | -         |    -9.69 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1655 | 2024-05-31 | BIG EQUIPA       | L   | 0.760      | -            | -                | -                | -         |   -11.64 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1760 | 2024-05-26 | TSM Shimmer      | W   | 0.727      | 0.303        | 0.020 (0.004)    | 0.196 (0.043)    | 0 (0.000) |    10.54 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1763 | 2024-05-26 | Lotus fe         | W   | 0.727      | 0.303        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |     7.85 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2716 | 2024-04-19 | Nouns fe         | W   | 0.482      | 0.322        | 0.003 (0.001)    | 0.034 (0.005)    | 0 (0.000) |     5.25 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2893 | 2024-04-14 | TSM Shimmer      | W   | 0.448      | 0.250        | 0.020 (0.002)    | 0.196 (0.022)    | 0 (0.000) |     6.66 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2975 | 2024-04-10 | cleanup crew fe  | W   | 0.422      | 0.322        | 0.002 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     4.48 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3163 | 2024-04-04 | COVEN            | W   | 0.382      | -            | -                | -                | 0 (0.000) |     2.74 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3312 | 2024-03-28 | WG Bandits       | W   | 0.335      | -            | -                | -                | 0 (0.000) |     3.58 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3465 | 2024-03-20 | Limitless Angels | W   | 0.282      | 0.322        | 0.003 (0.000)    | 0.047 (0.004)    | 0 (0.000) |     3.44 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3607 | 2024-03-13 | Karma            | W   | 0.235      | 0.322        | 0.004 (0.000)    | 0.070 (0.005)    | 0 (0.000) |     2.96 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3787 | 2024-03-06 | TSM Shimmer      | W   | 0.189      | 0.322        | 0.020 (0.001)    | 0.196 (0.012)    | 0 (0.000) |     2.83 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3871 | 2024-03-03 | TSM Shimmer      | W   | 0.168      | 0.250        | 0.020 (0.001)    | 0.196 (0.008)    | -         |     2.56 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4011 | 2024-02-25 | TSM Shimmer      | W   | 0.122      | 0.250        | 0.020 (0.001)    | 0.196 (0.006)    | -         |     1.87 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,469.97)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.774 | $4,000.00      | $3,097.78       |
| 2024-05-26 |      0.727 | $2,500.00      | $1,818.63       |
| 2024-04-14 |      0.448 | $750.00        | $336.04         |
| 2024-03-03 |      0.168 | $750.00        | $126.27         |
| 2024-02-25 |      0.122 | $750.00        | $91.25          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
