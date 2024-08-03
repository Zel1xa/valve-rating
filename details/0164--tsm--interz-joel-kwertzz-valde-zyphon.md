### Roster Details<br />
Team Name: TSM<br />
Roster: interz, joel, KWERTZZ, valde, Zyphon<br />
Global Rank: [164](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  678.4<br />
<br />
Final Rank Value (678.4) = Starting Rank Value (670.9) + Head To Head Adjustments (7.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.9
- 400 + ( ( 0.132 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 670.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2600 | 2024-04-19 | Sangal            | L   | 0.494      | -            | -                | -                | -         |    -1.17 | interz, joel, KWERTZZ, valde, Zyphon |
|           12 |     2862 | 2024-04-10 | FORZE             | L   | 0.434      | -            | -                | -                | -         |    -2.63 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           11 |     2921 | 2024-04-09 | Betera            | W   | 0.427      | 0.500        | 0.005 (0.001)    | 0.040 (0.009)    | 0 (0.000) |     7.50 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           10 |     3050 | 2024-04-04 | 9 Pandas          | L   | 0.394      | -            | -                | -                | -         |    -1.65 | joel, KWERTZZ, poizon, valde, Zyphon |
|            9 |     3129 | 2024-04-02 | KOI               | L   | 0.380      | -            | -                | -                | -         |    -2.33 | joel, KWERTZZ, poizon, valde, Zyphon |
|            8 |     3187 | 2024-03-28 | 9INE              | W   | 0.347      | 0.500        | 0.000 (0.000)    | 0.069 (0.012)    | 0 (0.000) |     3.28 | joel, KWERTZZ, poizon, valde, Zyphon |
|            7 |     3343 | 2024-03-20 | VP.Prodigy        | L   | 0.292      | -            | -                | -                | -         |    -2.37 | joel, KWERTZZ, poizon, valde, Zyphon |
|            6 |     3456 | 2024-03-14 | EYEBALLERS        | W   | 0.254      | 0.500        | 0.006 (0.001)    | 0.528 (0.067)    | 0 (0.000) |     6.28 | interz, joel, MoDo, valde, Zyphon    |
|            5 |     3661 | 2024-03-06 | Sangal            | L   | 0.201      | -            | -                | -                | -         |    -0.41 | interz, JACKZ, joel, poizon, valde   |
|            4 |     3743 | 2024-03-03 | The Chosen Few    | L   | 0.180      | -            | -                | -                | -         |    -2.86 | joel, KWERTZZ, poizon, valde, Zyphon |
|            3 |     3754 | 2024-03-03 | Nexus             | W   | 0.180      | 0.143        | 0.014 (0.000)    | 0.441 (0.011)    | 0 (0.000) |     4.07 | joel, KWERTZZ, poizon, valde, Zyphon |
|            2 |     4264 | 2024-02-08 | ex-Preasy         | L   | 0.018      | -            | -                | -                | -         |    -0.20 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            1 |     4268 | 2024-02-07 | Gaimin Gladiators | L   | 0.012      | -            | -                | -                | -         |    -0.06 | joel, KWERTZZ, MoDo, valde, Zyphon   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,739.54)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $2,000.00      | $1,666.06       |
| 2024-02-09 |      0.024 | $3,000.00      | $73.47          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
