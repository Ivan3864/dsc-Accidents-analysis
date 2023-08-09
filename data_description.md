
crash - https://data.cityofchicago.org/resource/85ca-t3if.csv

* `CRASH_RECORD_ID` -This number can be used to link to the same crash in the Vehicles and People datasets. This number also serves as a unique ID in this dataset.
* `RD_NO` -Chicago Police Department report number. For privacy reasons, this column is blank for recent crashes.
* `CRASH_DATE_EST_I` -Crash date estimated by desk officer or reporting party (only used in cases where crash is reported at police station days after the crash)
* `CRASH_DATE` -Date and time of crash as entered by the reporting officer
* `POSTED_SPEED_LIMIT` -Posted speed limit, as determined by reporting officer
* `TRAFFIC_CONTROL_DEVICE` -Traffic control device present at crash location, as determined by reporting officer
* `DEVICE_CONDITION` -Condition of traffic control device, as determined by reporting officer
* `WEATHER_CONDITION` -Weather condition at time of crash, as determined by reporting officer
* `LIGHTING_CONDITION` -Light condition at time of crash, as determined by reporting officer
* `FIRST_CRASH_TYPE` -Type of first collision in crash
* `TRAFFICWAY_TYPE` -Trafficway type, as determined by reporting officer
* `LANE_CNT` -Total number of through lanes in either direction, excluding turn lanes, as determined by reporting officer (0 = intersection)
* `ALIGNMENT` -Street alignment at crash location, as determined by reporting officer
* `ROADWAY_SURFACE_COND` -Road surface condition, as determined by reporting officer
* `ROAD_DEFECT` -Road defects, as determined by reporting officer
* `REPORT_TYPE` -Administrative report type (at scene, at desk, amended)
* `CRASH_TYPE` -A general severity classification for the crash. Can be either Injury and/or Tow Due to Crash or No Injury / Drive Away
* `INTERSECTION_RELATED_I` -A field observation by the police officer whether an intersection played a role in the crash. Does not represent whether or not the crash occurred within the intersection.
* `NOT_RIGHT_OF_WAY_I` -	Whether the crash begun or first contact was made outside of the public right-of-way.
* `HIT_AND_RUN_I` -Crash did/did not involve a driver who caused the crash and fled the scene without exchanging information
* `DAMAGE` -A field observation of estimated damage.
* `DATE_POLICE_NOTIFIED` -	Calendar date on which police were notified of the crash
* `PRIM_CONTRIBUTORY_CAUSE	` -The factor which was most significant in causing the crash, as determined by officer judgment
* `SEC_CONTRIBUTORY_CAUSE` -	The factor which was second most significant in causing the crash, as determined by officer judgment
* `STREET_NO	` -Street address number of crash location, as determined by reporting officer
* `STREET_DIRECTION` -	Street address direction (N,E,S,W) of crash location, as determined by reporting officer
* `STREET_NAME	` -Street address name of crash location, as determined by reporting officer
* `BEAT_OF_OCCURRENCE` -	Chicago Police Department Beat ID. Boundaries available at https://data.cityofchicago.org/d/aerh-rz74
* `PHOTOS_TAKEN_I` -	Whether the Chicago Police Department took photos at the location of the crash
* `STATEMENTS_TAKEN_I` -	Whether statements were taken from unit(s) involved in crash
* `DOORING_I` -	Whether crash involved a motor vehicle occupant opening a door into the travel path of a bicyclist, causing a crash
* `WORK_ZONE_I` -	Whether the crash occurred in an active work zone
* `WORK_ZONE_TYPE` -	The type of work zone, if any
* `WORKERS_PRESENT_I` -	Whether construction workers were present in an active work zone at crash location
* `NUM_UNITS` -	Number of units involved in the crash. A unit can be a motor vehicle, a pedestrian, a bicyclist, or another non-passenger roadway user.
* `MOST_SEVERE_INJURY`-Most severe injury sustained by any person involved in the crash
* `INJURIES_TOTAL` -	Total persons sustaining fatal, incapacitating, non-incapacitating, and possible injuries as determined by the reporting officer
* `INJURIES_FATAL` -Total persons sustaining fatal injuries in the crash
* `INJURIES_INCAPACITATING` -	Total persons sustaining incapacitating/serious injuries in the crash as determined by the reporting officer. Any injury other than fatal injury, which prevents the injured person from walking, driving, or normally continuing the activities they were capable of performing before the injury occurred. Includes severe lacerations, broken limbs, skull or chest injuries, and abdominal injuries.
* `INJURIES_NON_INCAPACITATING` -	Total persons sustaining non-incapacitating injuries in the crash as determined by the reporting officer. Any injury, other than fatal or incapacitating injury, which is evident to observers at the scene of the crash. Includes lump on head, abrasions, bruises, and minor lacerations.
* `INJURIES_REPORTED_NOT_EVIDENT` -	Total persons sustaining possible injuries in the crash as determined by the reporting officer. Includes momentary unconsciousness, claims of injuries not evident, limping, complaint of pain, nausea, and hysteria.
* `INJURIES_NO_INDICATION	` -Total persons sustaining no injuries in the crash as determined by the reporting officer
* `INJURIES_UNKNOWN	` -Total persons for whom injuries sustained, if any, are unknown
* `CRASH_HOUR` -	The hour of the day component of CRASH_DATE.
* `CRASH_DAY_OF_WEEK` -	The day of the week component of CRASH_DATE. Sunday=1
* `CRASH_MONTH` -	The month component of CRASH_DATE.
* `LATITUDE` -	The latitude of the crash location, as determined by reporting officer, as derived from the reported address of crash
* `LONGITUDE` -	The longitude of the crash location, as determined by reporting officer, as derived from the reported address of crash
* `LOCATION	` -The crash location, as determined by reporting officer, as derived from the reported address of crash, in a column type that allows for mapping and other geographic analysis in the data portal software



person - https://data.cityofchicago.org/resource/68nd-jvt3.csv


* `PERSON_ID` -	A unique identifier for each person record. IDs starting with P indicate passengers. IDs starting with O indicate a person who was not a passenger in the vehicle (e.g., driver, pedestrian, cyclist, etc.).
* `PERSON_TYPE` -	Type of roadway user involved in crash
* `CRASH_RECORD_ID` -	This number can be used to link to the same crash in the Crashes and Vehicles datasets. This number also serves as a unique ID in the Crashes dataset.
* `RD_NO` -	Chicago Police Department report number. For privacy reasons, this column is blank for recent crashes.
* `VEHICLE_ID` -	The corresponding CRASH_UNIT_ID from the Vehicles dataset.
* `CRASH_DATE` -	Date and time of crash as entered by the reporting officer
* `SEAT_NO` -	Code for seating position of motor vehicle occupant: 1= driver, 2= center front, 3 = front passenger, 4 = second row left, 5 = second row center, 6 = second row right, 7 = enclosed passengers, 8 = exposed passengers, 9= unknown position, 10 = third row left, 11 = third row center, 12 = third row right
* `CITY` -	City of residence of person involved in crash
* `STATE	` -State of residence of person involved in crash
* `ZIPCODE` -	ZIP Code of residence of person involved in crash
* `SEX	` -Gender of person involved in crash, as determined by reporting officer
* `AGE	` -Age of person involved in crash
* `DRIVERS_LICENSE_STATE` -	State issuing driver's license of person involved in crash
* `DRIVERS_LICENSE_CLASS` -	Class of driver's license of person involved in crash
* `SAFETY_EQUIPMENT	` -Safety equipment used by vehicle occupant in crash, if any
* `AIRBAG_DEPLOYED` -	Whether vehicle occupant airbag deployed as result of crash
* `EJECTION	` -Whether vehicle occupant was ejected or extricated from the vehicle as a result of crash
* `INJURY_CLASSIFICATION` -	Severity of injury person sustained in the crash
* `HOSPITAL	` -Hospital to which person injured in the crash was taken
* `EMS_AGENCY` -	EMS agency who transported person injured in crash to the hospital
* `EMS_RUN_NO` -	EMS agency run number
* `DRIVER_ACTION` -	Driver action that contributed to the crash, as determined by reporting officer
* `DRIVER_VISION` -	What, if any, objects obscured the driver’s vision at time of crash
* `PHYSICAL_CONDITION` -	Driver’s apparent physical condition at time of crash, as observed by the reporting officer
* `PEDPEDAL_ACTION` -	Action of pedestrian or cyclist at the time of crash
* `PEDPEDAL_VISIBILITY` -	Visibility of pedestrian of cyclist safety equipment in use at time of crash
* `PEDPEDAL_LOCATION` -	Location of pedestrian or cyclist at the time of crash
* `BAC_RESULT	` -Status of blood alcohol concentration testing for driver or other person involved in crash
* `BAC_RESULT VALUE	` -Driver’s blood alcohol concentration test result (fatal crashes may include pedestrian or cyclist results)
* `CELL_PHONE_USE` -	Whether person was/was not using cellphone at the time of the crash, as determined by the reporting officer


vahicle - https://data.cityofchicago.org/resource/68nd-jvt3.csv
* `CRASH_UNIT_ID` - A unique identifier for each vehicle record. (continuous)
* `CRASH_RECORD_ID` - This number can be used to link to the same crash in the Crashes and People datasets. This number also serves as a unique ID in the Crashes dataset. (id)
* `RD_NO` - Chicago Police Department report number. For privacy reasons, this column is blank for recent crashes.
* `CRASH_DATE` - Date and time of crash as entered by the reporting officer. (datetime)
* `UNIT_NO` - A unique ID for each unit within a specific crash report. (id)
* `UNIT_TYPE` - The type of unit. (continuous)
* `NUM_PASSENGER` - Number of passengers in the vehicle. The driver is not included. More information on passengers is in the People dataset. (int)
* `VEHICLE_ID` - ()
* `CMRC_VEH_I` -
* `MAKE` - The make (brand) of the vehicle, if relevant. (categorical)
* `MODEL` - The model of the vehicle, if relevant. (categorical)
* `LIC_PLATE_STATE` - The state issuing the license plate of the vehicle, if relevant. (categorical)
* `VEHICLE_YEAR` - The model year of the vehicle, if relevant. (datetime)
* `VEHICLE_DEFECT` - vahicle defect (categorical)
* `VEHICLE_TYPE` - The type of vehicle, if relevant (categorical)
* `VEHICLE_USE` - The normal use of the vehicle, if relevant. (categorical)
* `TRAVEL_DIRECTION` - he direction in which the unit was traveling prior to the crash, as determined by the reporting officer. (categorical)
* `MANEUVER` - The action the unit was taking prior to the crash, as determined by the reporting officer.(categorical)
* `TOWED_I` - Indicator of whether the vehicle was towed.(categorical)
* `FIRE_I` -
* `OCCUPANT_CNT` - The number of people in the unit, as determined by the reporting officer.(numerical)
* `EXCEED_SPEED_LIMIT_I` - Indicator of whether the unit was speeding, as determined by the reporting officer.(categorical)
* `TOWED_BY` - Entity that towed the unit, if relevant.(categorical)
* `TOWED_TO` - Location to which the unit was towed, if relevant
* `FIRST_CONTACT_POINT` - where the vehicle was hit.
* 

