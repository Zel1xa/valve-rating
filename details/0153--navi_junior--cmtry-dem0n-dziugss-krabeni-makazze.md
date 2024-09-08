### Roster Details<br />
Team Name: NAVI Junior<br />
Roster: cmtry, dem0n, dziugss, Krabeni, makazze<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  696.8<br />
<br />
Final Rank Value (696.8) = Starting Rank Value (678.2) + Head To Head Adjustments (18.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.255[<sup>1</sup>](#table2)
- Bounty Collected: 0.280[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.2
- 400 + ( ( 0.144 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 678.2


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
|           16 |        9 | 2024-09-07 | 500        | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.126 (0.047)    | 0 (0.000) |    10.35 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           15 |       79 | 2024-09-05 | TNL        | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.109 (0.041)    | 0 (0.000) |     9.61 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           14 |     1036 | 2024-08-08 | Illuminar  | L   | 0.993      | -            | -                | -                | -         |    -8.58 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           13 |     1125 | 2024-08-06 | UNiTY      | L   | 0.980      | -            | -                | -                | -         |    -7.34 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           12 |     2474 | 2024-06-08 | Rhyno      | L   | 0.586      | -            | -                | -                | -         |    -4.66 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|           11 |     2591 | 2024-06-06 | Endpoint   | W   | 0.573      | 0.500        | 0.065 (0.019)    | 0.723 (0.207)    | 0 (0.000) |    14.83 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|           10 |     2641 | 2024-06-05 | Sampi      | L   | 0.567      | -            | -                | -                | -         |    -4.08 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            9 |     2693 | 2024-06-04 | MOUZ NXT   | L   | 0.560      | -            | -                | -                | -         |    -2.14 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            8 |     2715 | 2024-06-03 | Entropiq   | W   | 0.554      | 0.379        | 0.000 (0.000)    | 0.019 (0.004)    | 0 (0.000) |     2.97 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            7 |     2822 | 2024-05-30 | Permitta   | L   | 0.527      | -            | -                | -                | -         |    -3.77 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            6 |     3046 | 2024-05-21 | Illuminar  | W   | 0.467      | 0.379        | 0.010 (0.002)    | 0.384 (0.068)    | 0 (0.000) |    10.63 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            5 |     4440 | 2024-03-30 | GL Academy | L   | 0.120      | -            | -                | -                | -         |    -1.90 | dem0n, dezt, Krabeni, Magic, makazze    |
|            4 |     4449 | 2024-03-29 | Passion UA | W   | 0.113      | 0.333        | 0.164 (0.006)    | 1.000 (0.038)    | 0 (0.000) |     3.10 | dem0n, dezt, Krabeni, Magic, makazze    |
|            3 |     4452 | 2024-03-29 | Sashi      | W   | 0.112      | 0.333        | 0.003 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.51 | dem0n, dezt, Krabeni, Magic, makazze    |
|            2 |     4499 | 2024-03-27 | Metizport  | L   | 0.102      | -            | -                | -                | -         |    -1.30 | dem0n, dezt, Krabeni, Magic, makazze    |
|            1 |     4615 | 2024-03-20 | FORZE      | L   | 0.054      | -            | -                | -                | -         |    -0.59 | dem0n, froz1k, Krabeni, Magic, makazze  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($359.17)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
