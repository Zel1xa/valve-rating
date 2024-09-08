### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  735.7<br />
<br />
Final Rank Value (735.7) = Starting Rank Value (698.1) + Head To Head Adjustments (37.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.252[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 698.1
- 400 + ( ( 0.154 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 698.1


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
|           15 |      108 | 2024-09-04 | TSM Shimmer      | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.156 (0.052)    | 0 (0.000) |    13.54 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           14 |      251 | 2024-08-29 | Lumen fe         | W   | 1.000      | 0.333        | -                | 0.038 (0.013)    | 0 (0.000) |     6.99 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           13 |      497 | 2024-08-25 | Imp Pact fe      | W   | 1.000      | 0.250        | 0.001 (0.000)    | 0.075 (0.019)    | 0 (0.000) |    11.40 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           12 |     2551 | 2024-06-06 | timbermen        | L   | 0.576      | -            | -                | -                | -         |    -3.86 | BiBiAhn, Emy, GooseBreeder, Shakezullah, vanessa |
|           11 |     2760 | 2024-06-01 | HSG fe           | L   | 0.541      | -            | -                | -                | -         |    -7.42 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|           10 |     2797 | 2024-05-31 | BIG EQUIPA       | L   | 0.534      | -            | -                | -                | -         |    -8.50 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            9 |     2902 | 2024-05-26 | TSM Shimmer      | W   | 0.502      | 0.303        | 0.018 (0.003)    | 0.156 (0.024)    | 0 (0.000) |     7.52 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            8 |     2905 | 2024-05-26 | Lotus fe         | W   | 0.501      | 0.303        | 0.003 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     6.00 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            7 |     3858 | 2024-04-19 | Nouns fe         | W   | 0.256      | 0.322        | 0.003 (0.000)    | 0.046 (0.004)    | 0 (0.000) |     3.02 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            6 |     4035 | 2024-04-14 | TSM Shimmer      | W   | 0.223      | 0.250        | 0.018 (0.001)    | 0.156 (0.009)    | 0 (0.000) |     3.38 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            5 |     4117 | 2024-04-10 | cleanup crew fe  | W   | 0.196      | 0.322        | 0.001 (0.000)    | -                | 0 (0.000) |     2.16 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            4 |     4305 | 2024-04-04 | COVEN            | W   | 0.156      | 0.322        | 0.001 (0.000)    | -                | 0 (0.000) |     1.30 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            3 |     4454 | 2024-03-28 | WG Bandits       | W   | 0.110      | 0.322        | 0.001 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.25 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            2 |     4607 | 2024-03-20 | Limitless Angels | W   | 0.057      | 0.322        | 0.001 (0.000)    | 0.012 (0.000)    | -         |     0.68 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |
|            1 |     4749 | 2024-03-13 | Blue Otter Karma | W   | 0.010      | 0.322        | -                | 0.064 (0.000)    | -         |     0.12 | BiBiAhn, Emy, GooseBreeder, Kaoday, vanessa      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,367.18)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-25 |      1.000 | $750.00        | $750.00         |
| 2024-06-02 |      0.549 | $4,000.00      | $2,195.56       |
| 2024-05-26 |      0.502 | $2,500.00      | $1,254.75       |
| 2024-04-14 |      0.223 | $750.00        | $166.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
