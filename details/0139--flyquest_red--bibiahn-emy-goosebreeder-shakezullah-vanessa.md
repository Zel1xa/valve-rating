### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  750.2<br />
<br />
Final Rank Value (750.2) = Starting Rank Value (721.3) + Head To Head Adjustments (28.9)<br />

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
|           15 |     1360 | 2024-06-06 | Elevate          | L   | 0.809      | -            | -                | -                | -         |    -5.30 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1569 | 2024-06-01 | HSG fe           | L   | 0.774      | -            | -                | -                | -         |    -9.81 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1606 | 2024-05-31 | BIG EQUIPA       | L   | 0.768      | -            | -                | -                | -         |   -11.77 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1711 | 2024-05-26 | TSM Shimmer      | W   | 0.735      | 0.303        | 0.020 (0.005)    | 0.199 (0.044)    | 0 (0.000) |    10.63 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1714 | 2024-05-26 | Lotus fe         | W   | 0.735      | 0.303        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |     7.89 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2667 | 2024-04-19 | Nouns fe         | W   | 0.490      | 0.322        | 0.003 (0.001)    | 0.035 (0.005)    | 0 (0.000) |     5.32 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2844 | 2024-04-14 | TSM Shimmer      | W   | 0.456      | 0.250        | 0.020 (0.002)    | 0.199 (0.023)    | 0 (0.000) |     6.76 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2926 | 2024-04-10 | cleanup crew fe  | W   | 0.430      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.55 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3114 | 2024-04-04 | COVEN            | W   | 0.390      | -            | -                | -                | 0 (0.000) |     2.79 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3263 | 2024-03-28 | WG Bandits       | W   | 0.343      | -            | -                | -                | 0 (0.000) |     3.65 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3416 | 2024-03-20 | Limitless Angels | W   | 0.290      | 0.322        | 0.003 (0.000)    | 0.048 (0.005)    | 0 (0.000) |     3.54 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3558 | 2024-03-13 | Karma            | W   | 0.243      | 0.322        | 0.004 (0.000)    | 0.073 (0.006)    | 0 (0.000) |     3.06 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3738 | 2024-03-06 | TSM Shimmer      | W   | 0.197      | 0.322        | 0.020 (0.001)    | 0.199 (0.013)    | 0 (0.000) |     2.94 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3822 | 2024-03-03 | TSM Shimmer      | W   | 0.176      | 0.250        | 0.020 (0.001)    | 0.199 (0.009)    | -         |     2.67 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     3962 | 2024-02-25 | TSM Shimmer      | W   | 0.130      | 0.250        | 0.020 (0.001)    | 0.199 (0.006)    | -         |     1.99 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,539.04)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.782 | $4,000.00      | $3,129.35       |
| 2024-05-26 |      0.735 | $2,500.00      | $1,838.37       |
| 2024-04-14 |      0.456 | $750.00        | $341.96         |
| 2024-03-03 |      0.176 | $750.00        | $132.19         |
| 2024-02-25 |      0.130 | $750.00        | $97.17          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
