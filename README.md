# Elbil-vs.-bensinbil
#%% Data
K = 20000  # [antall kjørte km/år]
D = 365  # [dager per år]
W = 0.2  # [kWh/km]

#%% Beregning
E = 5000 + 8.38*D + W*K*2 + 0.1*K  # [årlige totalkostnadene for en elbil]
B = 7500 + 8.38*D + 1.0*K + 0.3*K  # [årlige totalkostnadene for en bensinbil]
S = E - B  # [årlig kostnadsdifferanse mellom elbil og bensinbil]

#%% Resultater i kroner
print('E =', E, 'og B =', B)
print('S =', S)
