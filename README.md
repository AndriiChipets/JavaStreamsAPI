Formula 1 application. 

There are 2 log files ‘start.log’ and ‘end.log’ that contain start and end data of the best lap for each racer of Formula 1 - Monaco 2018 Racing. (Start and end times are fictional, but the best lap times are true). Data contains only the first 20 minutes that refers to the first stage of the qualification

Q1: For the first 20 minutes (Q1), all cars together on the track try to set the fastest time. The slowest seven cars are eliminated, getting the bottom grid positions. Drivers are allowed to complete as many laps as they want during this short period of time.

Top 15 cars go to the Q2 stage.

The third file abbreviations '.txt ' contains abbreviation explanations.

Parse the hint:
SVF2018-05-24_12:02:58.917

SVF - racer abbreviation 
2018-05-24 - date
12:02:58.917 - time

Example of output:

Application reads the data from 2 files, order racers by time and print report that shows the top 15 racers and the rest ones after the underline, for example:

1. Daniel Ricciardo      | RED BULL RACING TAG HEUER     | 1:12.013
2. Sebastian Vettel      | FERRARI                       | 1:12.415
3. ...
------------------------------------------------------------------------
16. Brendon Hartley   | SCUDERIA TORO ROSSO HONDA         | 1:13.179
17. Marcus Ericsson    | SAUBER FERRARI                   | 1:13.265

*abbreviations.txt
DRR_Daniel Ricciardo_RED BULL RACING TAG HEUER
SVF_Sebastian Vettel_FERRARI
LHM_Lewis Hamilton_MERCEDES
KRF_Kimi Raikkonen_FERRARI
VBM_Valtteri Bottas_MERCEDES
EOF_Esteban Ocon_FORCE INDIA MERCEDES
FAM_Fernando Alonso_MCLAREN RENAULT
CSR_Carlos Sainz_RENAULT
SPF_Sergio Perez_FORCE INDIA MERCEDES
PGS_Pierre Gasly_SCUDERIA TORO ROSSO HONDA
NHR_Nico Hulkenberg_RENAULT
SVM_Stoffel Vandoorne_MCLAREN RENAULT
SSW_Sergey Sirotkin_WILLIAMS MERCEDES
CLS_Charles Leclerc_SAUBER FERRARI
RGH_Romain Grosjean_HAAS FERRARI
BHS_Brendon Hartley_SCUDERIA TORO ROSSO HONDA
MES_Marcus Ericsson_SAUBER FERRARI
LSW_Lance Stroll_WILLIAMS MERCEDES
KMH_Kevin Magnussen_HAAS FERRARI

*end.log
MES2018-05-24_12:05:58.778
RGH2018-05-24_12:06:27.441
SPF2018-05-24_12:13:13.883
LSW2018-05-24_12:07:26.834
DRR2018-05-24_12:15:24.067
NHR2018-05-24_12:04:02.979
CSR2018-05-24_12:04:28.095
KMH2018-05-24_12:04:04.396
BHS2018-05-24_12:16:05.164
SVM2018-05-24_12:19:50.198
KRF2018-05-24_12:04:13.889
VBM2018-05-24_12:01:12.434
SVF2018-05-24_12:04:03.332
EOF2018-05-24_12:19:11.838
PGS2018-05-24_12:08:36.586
SSW2018-05-24_12:17:24.354
FAM2018-05-24_12:14:17.169
CLS2018-05-24_12:10:54.750
LHM2018-05-24_12:19:32.585

*start.log
SVF2018-05-24_12:02:58.917
NHR2018-05-24_12:02:49.914
FAM2018-05-24_12:13:04.512
KRF2018-05-24_12:03:01.250
SVM2018-05-24_12:18:37.735
MES2018-05-24_12:04:45.513
LSW2018-05-24_12:06:13.511
BHS2018-05-24_12:14:51.985
EOF2018-05-24_12:17:58.810
RGH2018-05-24_12:05:14.511
SSW2018-05-24_12:16:11.648
KMH2018-05-24_12:02:51.003
PGS2018-05-24_12:07:23.645
CSR2018-05-24_12:03:15.145
SPF2018-05-24_12:12:01.035
DRR2018-05-24_12:14:12.054
LHM2018-05-24_12:18:20.125
CLS2018-05-24_12:09:41.921
VBM2018-05-24_12:00:00.000
