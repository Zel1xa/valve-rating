### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: deb0, gxx-, juanflatroo, SENER1, sinnopsyy<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
<br />
Final Rank Value:  767.6<br />
<br />
Final Rank Value (767.6) = Starting Rank Value (730.9) + Head To Head Adjustments (36.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.302[<sup>1</sup>](#table2)
- Bounty Collected: 0.329[<sup>2</sup>](#table1)
- Opponent Network: 0.052[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.9
- 400 + ( ( 0.171 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 730.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2330 | 2024-06-11 | SINNERS         | L   | 0.606      | -            | -                | -                | -         |    -3.50 | deb0, gxx-, juanflatroo, SENER1, sinnopsyy  |
|           26 |     2926 | 2024-05-25 | Zero Tenacity   | L   | 0.495      | -            | -                | -                | -         |    -2.45 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     2935 | 2024-05-25 | The Suspect     | W   | 0.493      | 0.143        | 0.006 (0.000)    | 0.263 (0.019)    | 0 (0.000) |     8.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     2944 | 2024-05-24 | Zero Tenacity   | W   | 0.488      | 0.273        | 0.163 (0.022)    | 1.000 (0.133)    | 0 (0.000) |    13.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     2949 | 2024-05-24 | Partizan        | W   | 0.486      | 0.273        | 0.009 (0.001)    | 0.212 (0.028)    | 0 (0.000) |     7.84 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     3179 | 2024-05-17 | Sashi           | L   | 0.439      | -            | -                | -                | -         |    -1.60 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     3522 | 2024-05-05 | 1WIN            | L   | 0.359      | -            | -                | -                | -         |    -3.56 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     3636 | 2024-04-29 | EYEBALLERS      | L   | 0.321      | -            | -                | -                | -         |    -4.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     3677 | 2024-04-27 | Insilio         | L   | 0.308      | -            | -                | -                | -         |    -2.88 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     3703 | 2024-04-26 | BLEED           | L   | 0.301      | -            | -                | -                | -         |    -2.91 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     3738 | 2024-04-25 | PARIVISION      | L   | 0.294      | -            | -                | -                | -         |    -1.47 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     3762 | 2024-04-24 | Zero Tenacity   | W   | 0.286      | 0.435        | 0.163 (0.020)    | 1.000 (0.124)    | 0 (0.000) |     7.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     3789 | 2024-04-22 | 3DMAX           | L   | 0.274      | -            | -                | -                | -         |    -0.04 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     3801 | 2024-04-22 | Sangal          | W   | 0.272      | 0.435        | 0.248 (0.029)    | 0.878 (0.104)    | 0 (0.000) |     8.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     3914 | 2024-04-18 | Sashi           | L   | 0.248      | -            | -                | -                | -         |    -1.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     3919 | 2024-04-18 | KOI             | W   | 0.248      | 0.143        | 0.053 (0.002)    | 0.317 (0.011)    | 0 (0.000) |     6.00 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     3931 | 2024-04-18 | FRAGMATIC       | W   | 0.247      | -            | -                | -                | 0 (0.000) |     1.01 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     3938 | 2024-04-18 | AMKAL           | L   | 0.247      | -            | -                | -                | -         |    -0.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     4008 | 2024-04-16 | Sashi           | W   | 0.233      | 0.384        | 0.151 (0.014)    | 0.926 (0.083)    | 0 (0.000) |     6.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     4201 | 2024-04-09 | Metizport       | W   | 0.187      | 0.384        | 0.014 (0.001)    | 0.076 (0.005)    | 0 (0.000) |     3.21 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     4368 | 2024-04-03 | AMKAL           | L   | 0.147      | -            | -                | -                | -         |    -0.54 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     4398 | 2024-04-02 | Insilio         | L   | 0.141      | -            | -                | -                | -         |    -1.25 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     4407 | 2024-04-02 | AMKAL           | W   | 0.140      | 0.143        | 0.123 (0.002)    | 0.397 (0.008)    | 0 (0.000) |     3.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     4417 | 2024-04-02 | 500             | L   | 0.139      | -            | -                | -                | -         |    -2.67 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     4422 | 2024-04-01 | 500             | W   | 0.135      | 0.384        | 0.001 (0.000)    | 0.025 (0.001)    | -         |     1.68 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     4503 | 2024-03-27 | ALTERNATE aTTaX | L   | 0.101      | -            | -                | -                | -         |    -0.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     4573 | 2024-03-22 | VP.Prodigy      | L   | 0.066      | -            | -                | -                | -         |    -0.79 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,501.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      0.488 | $2,158.00      | $1,053.22       |
| 2024-05-18 |      0.448 | $1,000.00      | $447.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
