### Roster Details<br />
Team Name: NAVI Junior<br />
Roster: cmtry, dem0n, dziugss, Krabeni, makazze<br />
Global Rank: [156](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [103]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  684.9<br />
<br />
Final Rank Value (684.9) = Starting Rank Value (679.5) + Head To Head Adjustments (5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.256[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.5
- 400 + ( ( 0.143 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 679.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       47 | 2024-09-05 | TNL        | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.073 (0.027)    | 0 (0.000) |     5.86 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           14 |     1004 | 2024-08-08 | Illuminar  | L   | 1.000      | -            | -                | -                | -         |    -8.52 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           13 |     1093 | 2024-08-06 | UNiTY      | L   | 0.988      | -            | -                | -                | -         |    -7.21 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           12 |     2442 | 2024-06-08 | Rhyno      | L   | 0.594      | -            | -                | -                | -         |    -4.63 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|           11 |     2559 | 2024-06-06 | Endpoint   | W   | 0.581      | 0.500        | 0.064 (0.019)    | 0.744 (0.216)    | 0 (0.000) |    15.09 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|           10 |     2609 | 2024-06-05 | Sampi      | L   | 0.575      | -            | -                | -                | -         |    -4.03 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            9 |     2661 | 2024-06-04 | MOUZ NXT   | L   | 0.568      | -            | -                | -                | -         |    -2.11 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            8 |     2683 | 2024-06-03 | Entropiq   | W   | 0.562      | 0.379        | 0.000 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     2.99 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            7 |     2790 | 2024-05-30 | Permitta   | L   | 0.535      | -            | -                | -                | -         |    -3.76 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            6 |     3014 | 2024-05-21 | Illuminar  | W   | 0.475      | 0.379        | 0.010 (0.002)    | 0.396 (0.071)    | 0 (0.000) |    10.90 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            5 |     4408 | 2024-03-30 | GL Academy | L   | 0.128      | -            | -                | -                | -         |    -2.01 | dem0n, dezt, Krabeni, Magic, makazze    |
|            4 |     4417 | 2024-03-29 | Passion UA | W   | 0.121      | 0.333        | 0.147 (0.006)    | 1.000 (0.040)    | 0 (0.000) |     3.31 | dem0n, dezt, Krabeni, Magic, makazze    |
|            3 |     4420 | 2024-03-29 | Sashi      | W   | 0.120      | 0.333        | 0.003 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.63 | dem0n, dezt, Krabeni, Magic, makazze    |
|            2 |     4467 | 2024-03-27 | Metizport  | L   | 0.109      | -            | -                | -                | -         |    -1.39 | dem0n, dezt, Krabeni, Magic, makazze    |
|            1 |     4583 | 2024-03-20 | FORZE      | L   | 0.062      | -            | -                | -                | -         |    -0.67 | dem0n, froz1k, Krabeni, Magic, makazze  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($382.92)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
