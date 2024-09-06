### Roster Details<br />
Team Name: NAVI Junior<br />
Roster: cmtry, dem0n, dziugss, Krabeni, makazze<br />
Global Rank: [156](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [103]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  685.4<br />
<br />
Final Rank Value (685.4) = Starting Rank Value (679.9) + Head To Head Adjustments (5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.280[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.9
- 400 + ( ( 0.143 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 679.9


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
|           15 |       42 | 2024-09-05 | TNL        | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.073 (0.027)    | 0 (0.000) |     5.85 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           14 |      999 | 2024-08-08 | Illuminar  | L   | 1.000      | -            | -                | -                | -         |    -8.54 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           13 |     1088 | 2024-08-06 | UNiTY      | L   | 0.992      | -            | -                | -                | -         |    -7.24 | cmtry, dem0n, dziugss, Krabeni, makazze |
|           12 |     2437 | 2024-06-08 | Rhyno      | L   | 0.598      | -            | -                | -                | -         |    -4.66 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|           11 |     2554 | 2024-06-06 | Endpoint   | W   | 0.585      | 0.500        | 0.064 (0.019)    | 0.742 (0.217)    | 0 (0.000) |    15.18 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|           10 |     2604 | 2024-06-05 | Sampi      | L   | 0.579      | -            | -                | -                | -         |    -4.06 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            9 |     2656 | 2024-06-04 | MOUZ NXT   | L   | 0.572      | -            | -                | -                | -         |    -2.13 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            8 |     2678 | 2024-06-03 | Entropiq   | W   | 0.566      | 0.379        | 0.000 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     3.00 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            7 |     2785 | 2024-05-30 | Permitta   | L   | 0.539      | -            | -                | -                | -         |    -3.81 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            6 |     3009 | 2024-05-21 | Illuminar  | W   | 0.479      | 0.379        | 0.010 (0.002)    | 0.395 (0.072)    | 0 (0.000) |    10.97 | cmtry, dem0n, dziugss, froz1k, Krabeni  |
|            5 |     4403 | 2024-03-30 | GL Academy | L   | 0.132      | -            | -                | -                | -         |    -2.08 | dem0n, dezt, Krabeni, Magic, makazze    |
|            4 |     4412 | 2024-03-29 | Passion UA | W   | 0.125      | 0.333        | 0.147 (0.006)    | 1.000 (0.042)    | 0 (0.000) |     3.42 | dem0n, dezt, Krabeni, Magic, makazze    |
|            3 |     4415 | 2024-03-29 | Sashi      | W   | 0.124      | 0.333        | 0.003 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.69 | dem0n, dezt, Krabeni, Magic, makazze    |
|            2 |     4462 | 2024-03-27 | Metizport  | L   | 0.113      | -            | -                | -                | -         |    -1.44 | dem0n, dezt, Krabeni, Magic, makazze    |
|            1 |     4578 | 2024-03-20 | FORZE      | L   | 0.066      | -            | -                | -                | -         |    -0.71 | dem0n, froz1k, Krabeni, Magic, makazze  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($394.93)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
