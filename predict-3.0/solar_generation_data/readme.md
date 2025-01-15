# Overview of the Datasets

This README describes two datasets that provide observations for solar plant performance monitoring in India. Below are the details in the specified format:

---

# Dataset 1: Solar Plant Generation 

## Description:
Contains observations from the sensor panel attached to a solar plant, capturing environmental and panel-specific metrics recorded every 15 minutes.

## File Name:
`solar_plant_generation.csv`

## Time Period:
- **Start**: 15-05-2020
- **End**: 04-06-2020
- **No. of Years**: 21 days
- **No. of Rows**: 2010

## Columns
DATE_TIME
PLANT_ID
SOURCE_KEY
DC_POWER
DAILY_YIELD
TOTAL_YIELD

## Frequency:
15-minute intervals

---


# Dataset 2: Plant Weather Sensor

## Description:
Contains observations from the inverter of a solar plant, recording DC and AC power generation, along with cumulative daily and total yields.

## File Name:
`plant_weather_sensor.csv`

## Time Period:
- **Start**: 15-05-2020
- **End**: 05-06-2020
- **Time Period**: 22 days
- **No. of Rows**: 2011

## Column
DATE_TIME
PLANT_ID
SOURCE_KEY
AMBIENT_TEMPERATURE
MODULE_TEMPERATURE
IRRADIATION

## Frequency:
15-minute intervals