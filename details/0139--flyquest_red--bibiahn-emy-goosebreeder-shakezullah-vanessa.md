### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  750.6<br />
<br />
Final Rank Value (750.6) = Starting Rank Value (721.4) + Head To Head Adjustments (29.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.4
- 400 + ( ( 0.157 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 721.4


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
|           15 |     1348 | 2024-06-06 | Elevate          | L   | 0.813      | -            | -                | -                | -         |    -5.33 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1557 | 2024-06-01 | HSG fe           | L   | 0.778      | -            | -                | -                | -         |    -9.87 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1594 | 2024-05-31 | BIG EQUIPA       | L   | 0.772      | -            | -                | -                | -         |   -11.83 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1699 | 2024-05-26 | TSM Shimmer      | W   | 0.739      | 0.303        | 0.020 (0.005)    | 0.199 (0.045)    | 0 (0.000) |    10.66 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1702 | 2024-05-26 | Lotus fe         | W   | 0.738      | 0.303        | 0.005 (0.001)    | 0.038 (0.009)    | 0 (0.000) |     7.91 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2654 | 2024-04-19 | Nouns fe         | W   | 0.493      | 0.322        | 0.003 (0.001)    | 0.035 (0.006)    | 0 (0.000) |     5.35 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2831 | 2024-04-14 | TSM Shimmer      | W   | 0.460      | 0.250        | 0.020 (0.002)    | 0.199 (0.023)    | 0 (0.000) |     6.81 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2913 | 2024-04-10 | cleanup crew fe  | W   | 0.433      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.58 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3101 | 2024-04-04 | COVEN            | W   | 0.393      | -            | -                | -                | 0 (0.000) |     2.81 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3250 | 2024-03-28 | WG Bandits       | W   | 0.347      | -            | -                | -                | 0 (0.000) |     3.68 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3403 | 2024-03-20 | Limitless Angels | W   | 0.294      | 0.322        | 0.003 (0.000)    | 0.049 (0.005)    | 0 (0.000) |     3.58 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3545 | 2024-03-13 | Karma            | W   | 0.247      | 0.322        | 0.004 (0.000)    | 0.073 (0.006)    | 0 (0.000) |     3.10 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3724 | 2024-03-06 | TSM Shimmer      | W   | 0.201      | 0.322        | 0.020 (0.001)    | 0.199 (0.013)    | 0 (0.000) |     2.99 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3808 | 2024-03-03 | TSM Shimmer      | W   | 0.180      | 0.250        | 0.020 (0.001)    | 0.199 (0.009)    | -         |     2.73 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     3948 | 2024-02-25 | TSM Shimmer      | W   | 0.133      | 0.250        | 0.020 (0.001)    | 0.199 (0.007)    | -         |     2.04 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,572.05)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.786 | $4,000.00      | $3,144.44       |
| 2024-05-26 |      0.739 | $2,500.00      | $1,847.80       |
| 2024-04-14 |      0.460 | $750.00        | $344.79         |
| 2024-03-03 |      0.180 | $750.00        | $135.02         |
| 2024-02-25 |      0.133 | $750.00        | $100.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
