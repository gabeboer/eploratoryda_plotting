
# eploratoryda_plotting

Dataset: Electric power consumption 
Description: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

The following descriptions of the 9 variables in the dataset are taken from the UCI web site:
1 Date: Date in format dd/mm/yyyy
2 Time: time in format hh:mm:ss
3 Global_active_power: household global minute-averaged active power (in kilowatt)
4 Global_reactive_power: household global minute-averaged reactive power (in kilowatt)
5 Voltage: minute-averaged voltage (in volt)
6 Global_intensity: household global minute-averaged current intensity (in ampere)
7 Sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a     dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
8 Sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
9 Sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

# Steps executed:
## Loading the data
restrict the data set (when reading, not subsetting) to 2007-02-01 - 2007-02-02 (YYYY-MM-DD)
leaving 2.880 rows and the 9 columns

see the EDA_graphs1.R script for coding the first plot

