### Roster Details<br />
Team Name: NAVI Junior<br />
Roster: cmtry, dem0n, dziugss, Krabeni, makazze<br />
Global Rank: [149](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  727.9<br />
<br />
Final Rank Value (727.9) = Starting Rank Value (713.6) + Head To Head Adjustments (14.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.6
- 400 + ( ( 0.152 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 713.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       11 | 2024-08-06 | UNiTY      | L   | 1.000      | -            | -                | -                | -         |    -7.19 | cmtry, dem0n, dziugss, Krabeni, makazze  |
|           14 |     1357 | 2024-06-08 | Rhyno      | L   | 0.805      | -            | -                | -                | -         |    -5.14 | cmtry, dem0n, dziugss, froz1k, Krabeni   |
|           13 |     1474 | 2024-06-06 | Endpoint   | W   | 0.792      | 0.500        | 0.012 (0.005)    | 0.540 (0.214)    | 0 (0.000) |    17.60 | cmtry, dem0n, dziugss, froz1k, Krabeni   |
|           12 |     1524 | 2024-06-05 | Sampi      | L   | 0.786      | -            | -                | -                | -         |    -6.08 | cmtry, dem0n, dziugss, froz1k, Krabeni   |
|           11 |     1576 | 2024-06-04 | MOUZ NXT   | L   | 0.779      | -            | -                | -                | -         |    -2.58 | cmtry, dem0n, dziugss, froz1k, Krabeni   |
|           10 |     1598 | 2024-06-03 | Entropiq   | W   | 0.773      | 0.379        | 0.000 (0.000)    | 0.028 (0.008)    | 0 (0.000) |     3.42 | cmtry, dem0n, dziugss, froz1k, Krabeni   |
|            9 |     1705 | 2024-05-30 | Permitta   | L   | 0.746      | -            | -                | -                | -         |    -5.80 | cmtry, dem0n, dziugss, froz1k, Krabeni   |
|            8 |     1929 | 2024-05-21 | Illuminar  | W   | 0.686      | 0.379        | 0.012 (0.003)    | 0.340 (0.088)    | 0 (0.000) |    15.52 | cmtry, dem0n, dziugss, froz1k, Krabeni   |
|            7 |     3323 | 2024-03-30 | GL Academy | L   | 0.339      | -            | -                | -                | -         |    -5.02 | dem0n, dezt, Krabeni, Magic, makazze     |
|            6 |     3332 | 2024-03-29 | Passion UA | W   | 0.332      | 0.333        | 0.173 (0.019)    | 1.000 (0.111)    | 0 (0.000) |     9.14 | dem0n, dezt, Krabeni, Magic, makazze     |
|            5 |     3335 | 2024-03-29 | Sashi      | W   | 0.331      | 0.333        | 0.009 (0.001)    | 0.024 (0.003)    | 0 (0.000) |     4.84 | dem0n, dezt, Krabeni, Magic, makazze     |
|            4 |     3382 | 2024-03-27 | Metizport  | L   | 0.321      | -            | -                | -                | -         |    -2.39 | dem0n, dezt, Krabeni, Magic, makazze     |
|            3 |     3498 | 2024-03-20 | FORZE      | L   | 0.273      | -            | -                | -                | -         |    -2.19 | dem0n, froz1k, Krabeni, Magic, makazze   |
|            2 |     4166 | 2024-02-20 | ECLOT      | L   | 0.079      | -            | -                | -                | -         |    -0.14 | alkarenn, dem0n, Krabeni, Magic, makazze |
|            1 |     4198 | 2024-02-19 | Viperio    | W   | 0.071      | 0.303        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.33 | alkarenn, dem0n, Krabeni, Magic, makazze |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,016.25)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
