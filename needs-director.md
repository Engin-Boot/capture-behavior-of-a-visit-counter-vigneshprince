# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

  Given A person visits the hospital, the sensor for fall foot counter woks properly

  When a person enters through the sensor

  Then increment the no of entries by 1 and display on the report for that day.
  
  Beds, seating arrangement, parking lot provided accordingly.

## Scenario: Compute parking slots to reserve for visiting specialists

  Given Specialist visits the hospital and the entry card issuer sensor works properly

  When Specialist passes through the sensor increment the counter by 1 and
  
  On exiting decrement the sensor counter

  Then based on remaining spaces compute and reserve a parking slot
