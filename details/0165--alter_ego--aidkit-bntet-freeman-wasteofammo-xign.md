### Roster Details<br />
Team Name: Alter Ego<br />
Roster: aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  658.1<br />
<br />
Final Rank Value (658.1) = Starting Rank Value (527.5) + Head To Head Adjustments (130.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 527.5
- 400 + ( ( 0.066 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 527.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      236 | 2024-08-30 | Gods Reign        | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.247 (0.035)    | 0 (0.000) |    18.98 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN    |
|           10 |      287 | 2024-08-29 | Gods Reign        | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.247 (0.035)    | 0 (0.000) |    20.04 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN    |
|            9 |      342 | 2024-08-28 | Niory             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.113 (0.016)    | 0 (0.000) |    11.72 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN    |
|            8 |      352 | 2024-08-28 | Dewa United       | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.038 (0.005)    | 0 (0.000) |    10.92 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN    |
|            7 |      469 | 2024-08-26 | Forward           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |    11.71 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN    |
|            6 |      474 | 2024-08-26 | Revenge           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.075 (0.011)    | 0 (0.000) |    12.38 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN    |
|            5 |      493 | 2024-08-26 | ONi               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.113 (0.016)    | 0 (0.000) |    12.07 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN    |
|            4 |     1990 | 2024-07-13 | Rare Atom         | L   | 0.818      | -            | -                | -                | -         |    -4.07 | BnTeT, Freeman, splashske, WasteOfAmmo, XigN |
|            3 |     1995 | 2024-07-12 | Chinggis Warriors | W   | 0.813      | 0.143        | 0.013 (0.002)    | 0.187 (0.022)    | 0 (0.000) |    22.11 | BnTeT, Freeman, splashske, WasteOfAmmo, XigN |
|            2 |     1997 | 2024-07-12 | GR                | W   | 0.813      | 0.143        | 0.006 (0.001)    | 0.169 (0.020)    | 0 (0.000) |    17.22 | BnTeT, Freeman, splashske, WasteOfAmmo, XigN |
|            1 |     2003 | 2024-07-12 | TYLOO             | L   | 0.812      | -            | -                | -                | -         |    -2.48 | BnTeT, Freeman, splashske, WasteOfAmmo, XigN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
