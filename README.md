# logan-queueing
Files for APMTH 115 Final Project (Observed 5/3/2024)

This repository contains a variety of files based on observations made at Boston Logan International Airport (BOS) on 5/3/2024. From 12:49pm to 4:49pm, every observed takeoff and landing time, along with airline, runway at which the action occurred, and some other information, was collected.

For only the raw data file that holds the times, look to BostonLoganRunwayData.

For the working data file with multiple spreadsheets where time differences, probabilities, rates, and other calculations were made, check out logan data 5-4.

red_real_arrival_times, red_simulated_arrival_times, blue_real_arrival_times, and blue_simulated_arrival_times are all files where the time file was simplified to only include the minute at which the final action occurred over one hour (for "real" files this is 1:00pm to 2:00pm, for "simulated" files this is based on a Python simulation that simulated one hour).

four_hour_times and all_real_arrival_times both are similar to the four previous files, but these include the entire four hours observed (all_real_arrival_times), and in the case of four_hour_times, the same Python simulation that simulated four hours instead of one).
