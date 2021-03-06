# Assignment - Week 4

## Assignment: Hardware
Keep your Arduino sending data to MQTT so we continue to collect data. It's fine to update or modify your hardware and code to get better data. If you have problems with your hardware, please contact me.

If future classes we're going to be sending data back to the Arduino. You can use the LED for this part. Think about other hardware you can add to your Ardiono that can be controlled via MQTT messages, perhaps a servo, solenoid, relay, or NeoPixels.

## Assignment: SQL

1) Practice writing SQL queries against the `itp` and `farm` databases in MongoDB, InfluxDB, and TimescaleDB.

2) Use the `farm` database on InfluxDB. Write queries to answer the following questions:
  - When did the outside sensor break and stop sending data?
  - What was the lowest temperature recorded in 2018? Which sensor recorded this data?

3) Find the min and max temperatures by week for the root cellar for the last 3 months of 2018. 
  - Use InfluxDB and the `farm` database. Hint: use `group by time(interval)`
  - Use TimescaleDB and the `tsfarm` database. Hint: use the `time_bucket` function

Explain the differences between the InfluxDB and TimescaleDB and query results.

Challenge: Run the same query in MongoDB using the `farm` database

4) Write two queries that use data from your sensor data from InfluxDB.

Submit queries and results for SQL parts 2, 3 and 4 via email or Google doc before class on **March 4th**. Make sure queries are formatted so they are easy to understand. It's fine to submit a screenshot of the query results.
