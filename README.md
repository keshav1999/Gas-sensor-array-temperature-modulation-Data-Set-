# Gas sensor array exposed to dynamic mixtures of carbon monoxide and humidity

Source:

Creators: 
Javier Burgués (jburgues8 '@'ibecbarcelona.eu, jburgues8 '@'gmail.com) 
Institute of Bioengineering of Catalonia (IBEC)
Baldiri Reixac 10-12
Barcelona, Spain

Donors of the Dataset: 
Javier Burgués (jburgues '@'ibecbarcelona.eu, jburgues8 '@'gmail.com) 
Santiago Marco (smarco '@'ibecbarcelona.eu) 

Data Set Information:

A chemical detection platform composed of 14 temperature-modulated metal oxide semiconductor (MOX) gas sensors was exposed to dynamic mixtures of carbon monoxide (CO) and humid synthetic air in a gas chamber. 

The acquired time series of the sensors and the measured values of CO concentration, humidity and temperature inside the gas chamber are provided. 

a) Chemical detection platform: 
The chemical detection platform was composed of 14 MOX gas sensors that generate a time-dependent multivariate response to the different gas stimuli. 
The utilized sensors were made commercially available by Figaro Engineering (7 units of TGS 3870-A04) and FIS (7 units of SB-500-12).
The operating temperature of the sensors was controlled by the built-in heater, which voltage was modulated in the range 0.2-0.9 V in cycles of 20 and 25 s, following the manufacturer recommendations (0.9 V for 5s, 0.2 V for 20s, 0.9 V for 5 s, 0.2 V for 25 s, ...). 
The sensors were pre-heated for one week before starting the experiments.
The MOX read-out circuits consisted of voltage dividers with 1 MOhm load resistors and powered at 5V.
The output voltage of the sensors was sampled at 3.5 Hz using an Agilent HP34970A/34901A DAQ configured at 15 bits of precision and input impedance greater than 10 GOhm.

b) Generator of dynamic gas mixtures
Dynamic mixtures of CO and humid synthetic air were delivered from high purity gases in cylinders to a small-sized polytetrafluoroethylene (PTFE) test chamber (250 cm3 internal volume), by means of a piping system and mass flow controllers (MFCs).
Gas mixing was performed using mass flow controllers (MFC),which controlled three different gas streams (CO, wet air and dry air). These streams were delivered from high quality pressurized
gases in cylinders. 
The selected MFCs (EL-FLOW Select, Bronkhorst) had full scale flow rates of 1000 mln/min for the dry and wet air streams and 3 mln/min for the CO channel. 
The CO bottle contained 1600 ppm of CO diluted in synthetic air with 21 ± 1% O2. 
The relative uncertainty in the generated CO concentration was below 5.5%.
The wet and dry air streams were both delivered from a synthetic air bottle with 99.995% purity and 21 ± 1% O2. 
Humidification of the wet stream was based on the saturation method using a glass bubbler (Drechsler bottles). 

c)  Temperature/humidity values
A temperature/humidity sensor (SHT75, from Sensirion) provided reference humidity and temperature values inside the test chamber with tolerance below 1.8% r.h. and 0.5 ºC, respectively, every 5 s.
The temperature variations inside the gas chamber, for each experiment, were below 3 ºC. 

d) Experimental protocol: 
Each experiment consisted on 100 measurements: 10 experimental concentrations uniformly distributed in the range 0-20 ppm and 10 replicates per concentration. 
Each replicate had a relative humidity randomly chosen from a uniform distribution between 15% and 75% r.h. 
At the beginning of each experiment, the gas chamber was cleaned for 15 min using a stream of synthetic air at a flow rate of 240 mln/min. 
After that, the gas mixtures were released in random order at a constant flow rate of 240 mln/min for 15 min each. 
A single experiment lasted 25 hours (100 samples x 15 minutes/sample) and was replicated on 13 working days spanning a natural period of 17 days.


Attribute Information:

The dataset is presented in 13 text files, where each file corresponds to a different measurement day. The filenames indicate the timestamp (yyyymmdd_HHMMSS) of the start of the measurements.
Each file includes the acquired time series, presented in 20 columns: Time (s), CO concentration (ppm), Humidity (%r.h.), Temperature (ºC), Flow rate (mL/min), Heater voltage (V), and the resistance of the 14 gas sensors: R1 (MOhm),R2 (MOhm),R3 (MOhm),R4 (MOhm),R5 (MOhm),R6 (MOhm),R7 (MOhm),R8 (MOhm),R9 (MOhm),R10 (MOhm),R11 (MOhm),R12 (MOhm),R13 (MOhm),R14 (MOhm)
Resistance values R1-R7 correspond to FIGARO TGS 3870 A-04 sensors, whereas R8-R14 correspond to FIS SB-500-12 units.
The time series are sampled at 3.5 Hz.


Relevant Papers:

The description of the experimental setup and chemical detection platform can be found in [1-2]. The dataset has been used also in [3].

[1] Burgués, Javier, Juan Manuel Jiménez-Soto, and Santiago Marco. "Estimation of the limit of detection in semiconductor gas sensors through linearized calibration models." Analytica chimica acta 1013 (2018): 13-25.

[2] Burgués, Javier, and Santiago Marco. "Multivariate estimation of the limit of detection by orthogonal partial least squares in temperature-modulated MOX sensors." Analytica chimica acta 1019 (2018): 49-64.

[3] Fernandez, Luis, Jia Yan, Jordi Fonollosa, Javier Burgués, Agustin Gutierrez, and Santiago Marco. "A practical method to estimate the resolving power of a chemical sensor array: application to feature selection." Frontiers in chemistry 6 (2018).


Citation Request:

The following citations are requested if you use the dataset: 

Burgués, Javier, Juan Manuel Jiménez-Soto, and Santiago Marco. "Estimation of the limit of detection in semiconductor gas sensors through linearized calibration models." Analytica chimica acta 1013 (2018): 13-25
Burgués, Javier, and Santiago Marco. "Multivariate estimation of the limit of detection by orthogonal partial least squares in temperature-modulated MOX sensors." Analytica chimica acta 1019 (2018): 49-64.
