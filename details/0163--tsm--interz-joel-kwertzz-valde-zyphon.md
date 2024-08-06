### Roster Details<br />
Team Name: TSM<br />
Roster: interz, joel, KWERTZZ, valde, Zyphon<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [106]( ../standings_europe.md)<br />
<br />
Final Rank Value:  678.0<br />
<br />
Final Rank Value (678.0) = Starting Rank Value (669.8) + Head To Head Adjustments (8.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.8
- 400 + ( ( 0.132 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 669.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2731 | 2024-04-19 | Sangal         | L   | 0.478      | -            | -                | -                | -         |    -1.08 | interz, joel, KWERTZZ, valde, Zyphon |
|           11 |     2993 | 2024-04-10 | FORZE          | L   | 0.418      | -            | -                | -                | -         |    -2.58 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           10 |     3052 | 2024-04-09 | Betera         | W   | 0.411      | 0.500        | 0.005 (0.001)    | 0.037 (0.008)    | 0 (0.000) |     7.08 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            9 |     3181 | 2024-04-04 | 9 Pandas       | L   | 0.378      | -            | -                | -                | -         |    -1.59 | joel, KWERTZZ, poizon, valde, Zyphon |
|            8 |     3260 | 2024-04-02 | KOI            | L   | 0.365      | -            | -                | -                | -         |    -1.14 | joel, KWERTZZ, poizon, valde, Zyphon |
|            7 |     3318 | 2024-03-28 | 9INE           | W   | 0.332      | 0.500        | 0.000 (0.000)    | 0.066 (0.011)    | 0 (0.000) |     3.15 | joel, KWERTZZ, poizon, valde, Zyphon |
|            6 |     3479 | 2024-03-20 | VP.Prodigy     | L   | 0.276      | -            | -                | -                | -         |    -2.23 | joel, KWERTZZ, poizon, valde, Zyphon |
|            5 |     3593 | 2024-03-14 | EYEBALLERS     | W   | 0.238      | 0.500        | 0.005 (0.001)    | 0.500 (0.060)    | 0 (0.000) |     5.89 | interz, joel, MoDo, valde, Zyphon    |
|            4 |     3800 | 2024-03-06 | Sangal         | L   | 0.185      | -            | -                | -                | -         |    -0.37 | interz, JACKZ, joel, poizon, valde   |
|            3 |     3882 | 2024-03-03 | The Chosen Few | L   | 0.165      | -            | -                | -                | -         |    -2.61 | joel, KWERTZZ, poizon, valde, Zyphon |
|            2 |     3893 | 2024-03-03 | Nexus          | W   | 0.164      | 0.143        | 0.014 (0.000)    | 0.457 (0.011)    | 0 (0.000) |     3.71 | joel, KWERTZZ, poizon, valde, Zyphon |
|            1 |     4404 | 2024-02-08 | ex-Preasy      | L   | 0.002      | -            | -                | -                | -         |    -0.03 | joel, KWERTZZ, MoDo, valde, Zyphon   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,661.53)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $2,000.00      | $1,634.86       |
| 2024-02-09 |      0.009 | $3,000.00      | $26.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
