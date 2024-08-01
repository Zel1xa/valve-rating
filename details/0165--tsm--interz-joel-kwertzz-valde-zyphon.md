### Roster Details<br />
Team Name: TSM<br />
Roster: interz, joel, KWERTZZ, valde, Zyphon<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [106]( ../standings_europe.md)<br />
<br />
Final Rank Value:  683.4<br />
<br />
Final Rank Value (683.4) = Starting Rank Value (675.6) + Head To Head Adjustments (7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.6
- 400 + ( ( 0.134 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 675.6


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
|           14 |     2655 | 2024-04-19 | Sangal            | L   | 0.508      | -            | -                | -                | -         |    -1.25 | interz, joel, KWERTZZ, valde, Zyphon |
|           13 |     2921 | 2024-04-10 | FORZE             | L   | 0.448      | -            | -                | -                | -         |    -2.65 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           12 |     2980 | 2024-04-09 | Betera            | W   | 0.442      | 0.500        | 0.005 (0.001)    | 0.040 (0.009)    | 0 (0.000) |     7.61 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           11 |     3109 | 2024-04-04 | 9 Pandas          | L   | 0.408      | -            | -                | -                | -         |    -1.70 | joel, KWERTZZ, poizon, valde, Zyphon |
|           10 |     3196 | 2024-04-02 | KOI               | L   | 0.395      | -            | -                | -                | -         |    -2.39 | joel, KWERTZZ, poizon, valde, Zyphon |
|            9 |     3254 | 2024-03-28 | 9INE              | W   | 0.362      | 0.500        | 0.000 (0.000)    | 0.093 (0.017)    | 0 (0.000) |     3.36 | joel, KWERTZZ, poizon, valde, Zyphon |
|            8 |     3420 | 2024-03-20 | VP.Prodigy        | L   | 0.306      | -            | -                | -                | -         |    -2.49 | joel, KWERTZZ, poizon, valde, Zyphon |
|            7 |     3536 | 2024-03-14 | EYEBALLERS        | W   | 0.269      | 0.500        | 0.006 (0.001)    | 0.513 (0.069)    | 0 (0.000) |     6.65 | interz, joel, MoDo, valde, Zyphon    |
|            6 |     3747 | 2024-03-06 | Sangal            | L   | 0.215      | -            | -                | -                | -         |    -0.47 | interz, JACKZ, joel, poizon, valde   |
|            5 |     3834 | 2024-03-03 | The Chosen Few    | L   | 0.195      | -            | -                | -                | -         |    -3.10 | joel, KWERTZZ, poizon, valde, Zyphon |
|            4 |     3845 | 2024-03-03 | Nexus             | W   | 0.195      | 0.143        | 0.014 (0.000)    | 0.504 (0.014)    | 0 (0.000) |     4.38 | joel, KWERTZZ, poizon, valde, Zyphon |
|            3 |     4376 | 2024-02-08 | ex-Preasy         | L   | 0.033      | -            | -                | -                | -         |    -0.36 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            2 |     4380 | 2024-02-07 | Gaimin Gladiators | L   | 0.027      | -            | -                | -                | -         |    -0.13 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            1 |     4400 | 2024-02-05 | Metizport         | W   | 0.013      | 0.371        | 0.038 (0.000)    | 0.425 (0.002)    | 0 (0.000) |     0.33 | joel, KWERTZZ, MoDo, valde, Zyphon   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,812.92)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $2,000.00      | $1,695.42       |
| 2024-02-09 |      0.039 | $3,000.00      | $117.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
