# GPS_Roll_Over
A timing correction implementation to resolve an integer roll-over that happened with some older UBlox chips. This correction has been independently validated to be accurate to within 2.74 s. This result is acuraccy-limited by the instruments used.

This is a problem that occured in April 2019 and cause a number of GPS units to Y2K themselves, reporting dates ~20 years in the past.

