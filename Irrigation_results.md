
#Thunderstorm codes

Thunderstorm = rain

-200	Thunderstorm	thunderstorm with light rain	 11d
-201	Thunderstorm	thunderstorm with rain	 11d
-202	Thunderstorm	thunderstorm with heavy rain	 11d
-210	Thunderstorm	light thunderstorm	 11d
-211	Thunderstorm	thunderstorm	 11d
-212	Thunderstorm	heavy thunderstorm	 11d
-221	Thunderstorm	ragged thunderstorm	 11d
-230	Thunderstorm	thunderstorm with light drizzle	 11d
-231	Thunderstorm	thunderstorm with drizzle	 11d
-232	Thunderstorm	thunderstorm with heavy drizzle


#Rain codes

-500	Rain	light rain	 10d
-501	Rain	moderate rain	 10d
-502	Rain	heavy intensity rain	 10d
-503	Rain	very heavy rain	 10d
-504	Rain	extreme rain	 10d
-511	Rain	freezing rain	 13d
-520	Rain	light intensity shower rain	 09d
-521	Rain	shower rain	 09d
-522	Rain	heavy intensity shower rain	 09d
-531	Rain	ragged shower rain	 09d

#Clear codes

-800	Clear	clear sky	 01d
-801	Clouds	few clouds: 11-25%	 02d
-802	Clouds	scattered clouds: 25-50%	 03d
-803	Clouds	broken clouds: 51-84%	 04d
-804	Clouds	overcast clouds: 85-100%	 04d

Rules: 
after raining 2 days in a row = do not irrigate
if tomorrow forecast is moderate rain 501 to 531 = do not irrigate
if not rained for last day = irrigate
if tomorrow forecast is not rain = irrigate