### Roster Details<br />
Team Name: Nouns fe<br />
Roster: ashe, jesscas, katalyyst, lunari, raynee<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [53]( ../standings_americas.md)<br />
<br />
Final Rank Value:  566.5<br />
<br />
Final Rank Value (566.5) = Starting Rank Value (617.5) + Head To Head Adjustments (-50.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.162[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 617.5
- 400 + ( ( 0.112 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 617.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       59 | 2024-09-05 | Lumen fe         | L   | 1.000      | -            | -                | -                | -         |   -19.03 | ashe, jesscas, katalyyst, lunari, raynee |
|           10 |      302 | 2024-08-28 | Aware fe         | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.23 | ashe, jesscas, katalyyst, lunari, raynee |
|            9 |      737 | 2024-08-18 | TSM Shimmer      | L   | 1.000      | -            | -                | -                | -         |   -11.96 | ashe, jesscas, katalyyst, lunari, raynee |
|            8 |     1424 | 2024-07-28 | TSM Shimmer      | L   | 0.923      | -            | -                | -                | -         |   -12.01 | ashe, jesscas, katalyyst, lunari, raynee |
|            7 |     2099 | 2024-06-30 | Lotus fe         | L   | 0.736      | -            | -                | -                | -         |   -11.10 | ashe, daria, jesscas, katalyyst, raynee  |
|            6 |     3858 | 2024-04-19 | FlyQuest RED     | L   | 0.256      | -            | -                | -                | -         |    -3.02 | ashe, katalyyst, Knopk@, lunari, tokkis  |
|            5 |     4080 | 2024-04-11 | Limitless Angels | L   | 0.203      | -            | -                | -                | -         |    -3.28 | ashe, jesscas, katalyyst, lunari, tokkis |
|            4 |     4304 | 2024-04-04 | cleanup crew fe  | W   | 0.156      | 0.322        | 0.001 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     2.30 | ashe, jesscas, katalyyst, lunari, tokkis |
|            3 |     4479 | 2024-03-27 | Blue Otter Karma | L   | 0.103      | -            | -                | -                | -         |    -1.60 | ashe, jesscas, katalyyst, lunari, tokkis |
|            2 |     4576 | 2024-03-21 | COVEN            | W   | 0.063      | 0.322        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.73 | ashe, jesscas, katalyyst, lunari, tokkis |
|            1 |     4719 | 2024-03-14 | TSM Shimmer      | L   | 0.017      | -            | -                | -                | -         |    -0.21 | ashe, jesscas, katalyyst, lunari, Rice   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($998.06)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $250.00        | $250.00         |
| 2024-07-28 |      0.923 | $250.00        | $230.69         |
| 2024-06-30 |      0.736 | $250.00        | $184.06         |
| 2024-04-19 |      0.256 | $1,300.00      | $333.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
