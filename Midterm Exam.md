SEND "Give temperature" TO DISPLAY
IF temperature < 18 THEN
  SEND "Cold, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY 
ELSE IF temperature > 21 THEN
  SEND "Perfect" TO DISPLAY
  ELSE
    SEND "No!, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
