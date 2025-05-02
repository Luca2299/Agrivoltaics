# Agrivoltaics
Group work in FPSS
## Erklärung Daten: 

**Niederschlag:**
QN: Qualitaetsniveau
RWS_DAU_10: [\Niederschlagsdauer\,\Fehlwert=-999\] minute NUMBER 9990.0
RWS_10: [\Summe der Niederschlagshöhe der vorangegangen 10 Minuten\,\Fehlwert=-999\] mm NUMBER 9990.90
RWS_IND_10: [\Niederschlagsindikator\,\wenn QN = 1 dann gilt:\,\0 = kein Niederschlag gefallen, Dauergeber installiert\,\1 = Niederschlag gefallen, Dauergeber installiert\,\2 = kein Niederschlag gefallen, Heizung in Betrieb, Dauergeber installiert\,\3 = Niederschlag gefallen, Heizung in Betrieb, Dauergeber installiert\,\wenn QN > 1 dann gilt:\,\0 = kein Niederschlag gefallen\,\1 = Niederschlag gefallen\,\Fehlwert=-999\]

**Temperatur:**
QN: Qualitaetsniveau [QN = 1 : nur formale Prüfung; QN = 2 : nach individuellen Kriterien geprüft; QN = 3 : automatische Prüfung und Korrektur;] numerical NUMBER 990 code
PP_10 [\Luftdruck in Stationshoehe\, \Fehlwert=-999\] hPa NUMBER 9990.0
TT_10 [\Lufttemperatur in 2 m Höhe\, \instantan\,\Fehlwert=-999\] °C NUMBER 990.0
TM5_10 [\Lufttemperatur in 5 cm Hoehe\, \instantan\,\Fehlwert=-999\] °C NUMBER 990.0
RF_10 [\relative Feuchte\,\Fehlwert=-999\] % NUMBER 990.0
TD_10 [\Taupunkttemperatur\,\Die Taupunkttemperatur wird aus der Lufttemperatur in 2 m Höhe und der relativen Feuchtemessung berechnet.\, \Fehlwert=-999\]

**Solar:**
QN: Qualitaetsniveau [QN = 1 : nur formale Prüfung; QN = 2 : nach individuellen Kriterien geprüft; QN = 3 : automatische Prüfung und Korrektur;] numerical NUMBER 990 code
DS_10: [\Summe der diffusen Himmelstrahlung der vorangegangenen 10 Minuten\, \Fehlwert=-999\] J/cm² NUMBER 9990.0
GS_10: [\Summe der Globalstrahlung der vorangegangenen 10 Minuten\,\Fehlwert=-999\] J/cm² NUMBER 9990.0
SD_10: [\Summe der Sonnenscheindauer in den vorangegangenen 10 Minuten\, \Fehlwert=-999\] h NUMBER 90.990
LS_10: [\Summe der langwelligen Strahlung der vorangegangenen 10 Minuten\, \Fehlwert=-999\] J/cm² NUMBER 9990.0

**Wind:**
SLA_10 [\standard deviation of the lateral windspeed during the previous 10 minutes\,\missing_value=-999\] NUMBER 990.0
SLO_10 [\standard deviation of the longitudal windspeed during the previous 10 minutes\,\missing_value=-999\] NUMBER 990.0 
FF_10 [\mean wind speed during the previous 10 minutes\,\missing_value=-999\] m/s NUMBER 990.0
DD_10 [\mean wind direction during the previous 10 minutes\,\missing_value=-999\] ° NUMBER 990
