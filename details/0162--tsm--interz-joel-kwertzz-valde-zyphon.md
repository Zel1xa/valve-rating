### Roster Details<br />
Team Name: TSM<br />
Roster: interz, joel, KWERTZZ, valde, Zyphon<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  678.0<br />
<br />
Final Rank Value (678.0) = Starting Rank Value (669.9) + Head To Head Adjustments (8.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.9
- 400 + ( ( 0.131 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 669.9


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
|           11 |     2737 | 2024-04-19 | Sangal         | L   | 0.475      | -            | -                | -                | -         |    -1.06 | interz, joel, KWERTZZ, valde, Zyphon |
|           10 |     2999 | 2024-04-10 | FORZE          | L   | 0.415      | -            | -                | -                | -         |    -2.56 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            9 |     3058 | 2024-04-09 | Betera         | W   | 0.408      | 0.500        | 0.005 (0.001)    | 0.036 (0.007)    | 0 (0.000) |     7.03 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            8 |     3187 | 2024-04-04 | 9 Pandas       | L   | 0.375      | -            | -                | -                | -         |    -1.59 | joel, KWERTZZ, poizon, valde, Zyphon |
|            7 |     3266 | 2024-04-02 | KOI            | L   | 0.361      | -            | -                | -                | -         |    -1.14 | joel, KWERTZZ, poizon, valde, Zyphon |
|            6 |     3324 | 2024-03-28 | 9INE           | W   | 0.328      | 0.500        | 0.000 (0.000)    | 0.064 (0.011)    | 0 (0.000) |     3.12 | joel, KWERTZZ, poizon, valde, Zyphon |
|            5 |     3485 | 2024-03-20 | VP.Prodigy     | L   | 0.273      | -            | -                | -                | -         |    -2.20 | joel, KWERTZZ, poizon, valde, Zyphon |
|            4 |     3599 | 2024-03-14 | EYEBALLERS     | W   | 0.235      | 0.500        | 0.005 (0.001)    | 0.488 (0.057)    | 0 (0.000) |     5.80 | interz, joel, MoDo, valde, Zyphon    |
|            3 |     3806 | 2024-03-06 | Sangal         | L   | 0.182      | -            | -                | -                | -         |    -0.36 | interz, JACKZ, joel, poizon, valde   |
|            2 |     3888 | 2024-03-03 | The Chosen Few | L   | 0.161      | -            | -                | -                | -         |    -2.55 | joel, KWERTZZ, poizon, valde, Zyphon |
|            1 |     3899 | 2024-03-03 | Nexus          | W   | 0.161      | 0.143        | 0.014 (0.000)    | 0.447 (0.010)    | 0 (0.000) |     3.64 | joel, KWERTZZ, poizon, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,628.01)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
