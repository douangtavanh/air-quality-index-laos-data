# Air Quality Index Lao PDR

**Disclaimer: This is the personal project and is not supported from the agencies mentioned below.**

## About

The data is obtained in every 10 minutes (start from 24 June 2025) from [AirGradient](https://www.airgradient.com) with the contribution from [UNICEF Lao PDR](https://www.unicef.org/laos/).

You can visit the real-time data on [AirGradient Map](https://www.airgradient.com/map/).

Learn more about this project: [**Real-Time Air Monitoring Launches in Schools \|** UNICEF Lao PDR](https://www.unicef.org/laos/stories/real-time-air-monitoring-launches-schools)

## Metadata

**time** [`character`]: Time set to fetch the data from AriGradient(AG) API.

**dateTimeLocalFetch** [`datetime`]: Actual time at fetching the data from AG API (Local time UTC+7).

**timestamp** [`datetime`]: Time on device, Timestamp of the measures in ISO 8601 format with UTC offset.

**timezone** [`character`]: Timezone where the device is located.

**locationId** [`double`]: The unique id of the location, not present for averages

**province_pcode** [`character`]: Province code based on the Lao Statistics Bureau.

**province_en** [`character`]: Province name in English.

**province_lo** [`character`]: Province name in Lao.

**district_pcode** [`character`]: District code based on the Lao Statistics Bureau.

**district_en** [`character`]: District name in English.

**district_lo** [`character`]: District name in Lao.

**locationName** [`character`]: The name of the location as on the AG dashboard, not present for averages.

**publicLocationName** [`character`]: The public name of the location.

**latitude** [`double`]: The latitude of the location where the measurement was taken.

**longitude** [`double`]: The longitude of the location where the measurement was taken.

**pm01** [`double`]: The raw PM 1 value in ug / m3.

**pm02** [`double`]: The raw PM 2.5 value in ug / m3.

**pm10** [`double`]: The raw PM 10 value in ug / m3.

**pm003Count** [`double`]: The number of particles with a diameter beyond 0.3 microns in 1 deciliter of air.

**atmp** [`double`]: The ambient temperature in Celsius.

**rhum** [`double`]: The relative humidity in percent.

**rco2** [`logical`]: The CO2 value in ppm. **NOTE: ALL NA**

**tvoc** [`double`]: The TVOC value in ppb, provided in case that the sensor delivers an absolute value.

**tvocIndex** [`double`]: The value of the TVOC index, sensor model dependent.

**noxIndex** [`double`]: The value of the NOx index, sensor model dependent.

**heatindex** [`double`]: The index that combines air temperature and relative humidity.

**publicContributorName** [`character`]: The public name of the contributor.

**publicPlaceUrl** [`character`]: The URL of the public place.
