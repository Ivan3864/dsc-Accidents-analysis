
crash - https://data.cityofchicago.org/resource/85ca-t3if.csv



vehicle - https://data.cityofchicago.org/resource/68nd-jvt3.csv






person - https://data.cityofchicago.org/resource/u6pd-qa9d.csv
* `crash_unit_id` - A unique identifier for each vehicle record. (continuous)
* `crash_record_id` - This number can be used to link to the same crash in the Crashes and People datasets. This number also serves as a unique ID in the Crashes dataset. (id)
* `rd_no` - Chicago Police Department report number. For privacy reasons, this column is blank for recent crashes.
* `crash_date` - Date and time of crash as entered by the reporting officer. (datetime)
* `unit_no` - A unique ID for each unit within a specific crash report. (id)
* `unit_type` - The type of unit. (continuous)
* `num_passengers` - Number of passengers in the vehicle. The driver is not included. More information on passengers is in the People dataset. (int)
* `vehicle_id` - ()
* `cmrc_veh_i` -
* `make` - The make (brand) of the vehicle, if relevant. (categorical)
* `model` - The model of the vehicle, if relevant. (categorical)
* `lic_plate_state` - The state issuing the license plate of the vehicle, if relevant. (categorical)
* `vahicle_year` - The model year of the vehicle, if relevant. (datetime)
* `vahicle_defect` - vahicle defect (categorical)
* `vehicle_type` - The type of vehicle, if relevant (categorical)
* `vehicle_use` - The normal use of the vehicle, if relevant. (categorical)
* `travel_direction` - he direction in which the unit was traveling prior to the crash, as determined by the reporting officer. (categorical)
* `maneuver` - The action the unit was taking prior to the crash, as determined by the reporting officer.(categorical)
* `towed_id` - Indicator of whether the vehicle was towed.(categorical)
* `fire_i` -
* `occupant_cnt` - The number of people in the unit, as determined by the reporting officer.(numerical)
* `exceed_speed_limit_i` - Indicator of whether the unit was speeding, as determined by the reporting officer.(categorical)
* `towed_by` - Entity that towed the unit, if relevant.(categorical)

