### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa<br />
Global Rank: [141](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  750.1<br />
<br />
Final Rank Value (750.1) = Starting Rank Value (721.3) + Head To Head Adjustments (28.8)<br />

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
- 400 + ( ( 0.157 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 721.3


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
|           15 |     1383 | 2024-06-06 | Elevate          | L   | 0.808      | -            | -                | -                | -         |    -5.29 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           14 |     1592 | 2024-06-01 | HSG fe           | L   | 0.774      | -            | -                | -                | -         |    -9.80 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |     1629 | 2024-05-31 | BIG EQUIPA       | L   | 0.767      | -            | -                | -                | -         |   -11.76 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     1734 | 2024-05-26 | TSM Shimmer      | W   | 0.735      | 0.303        | 0.020 (0.005)    | 0.199 (0.044)    | 0 (0.000) |    10.62 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           11 |     1737 | 2024-05-26 | Lotus fe         | W   | 0.734      | 0.303        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |     7.88 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2690 | 2024-04-19 | Nouns fe         | W   | 0.489      | 0.322        | 0.003 (0.001)    | 0.035 (0.005)    | 0 (0.000) |     5.31 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2867 | 2024-04-14 | TSM Shimmer      | W   | 0.455      | 0.250        | 0.020 (0.002)    | 0.199 (0.023)    | 0 (0.000) |     6.75 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2949 | 2024-04-10 | cleanup crew fe  | W   | 0.429      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.54 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3137 | 2024-04-04 | COVEN            | W   | 0.389      | -            | -                | -                | 0 (0.000) |     2.78 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     3286 | 2024-03-28 | WG Bandits       | W   | 0.343      | -            | -                | -                | 0 (0.000) |     3.64 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     3439 | 2024-03-20 | Limitless Angels | W   | 0.289      | 0.322        | 0.003 (0.000)    | 0.048 (0.004)    | 0 (0.000) |     3.53 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     3581 | 2024-03-13 | Karma            | W   | 0.243      | 0.322        | 0.004 (0.000)    | 0.072 (0.006)    | 0 (0.000) |     3.05 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     3761 | 2024-03-06 | TSM Shimmer      | W   | 0.196      | 0.322        | 0.020 (0.001)    | 0.199 (0.013)    | 0 (0.000) |     2.93 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     3845 | 2024-03-03 | TSM Shimmer      | W   | 0.175      | 0.250        | 0.020 (0.001)    | 0.199 (0.009)    | -         |     2.66 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     3985 | 2024-02-25 | TSM Shimmer      | W   | 0.129      | 0.250        | 0.020 (0.001)    | 0.199 (0.006)    | -         |     1.98 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,532.36)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.782 | $4,000.00      | $3,126.30       |
| 2024-05-26 |      0.735 | $2,500.00      | $1,836.46       |
| 2024-04-14 |      0.455 | $750.00        | $341.39         |
| 2024-03-03 |      0.175 | $750.00        | $131.61         |
| 2024-02-25 |      0.129 | $750.00        | $96.60          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
