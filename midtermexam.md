SEND "Please enter the temperature" TO DISPLAY
RECEIVE temperature FROM KEYBOARD
IF temperature < 18 degrees THEN
SEND "Cold, the perfect temperature for sleep is 18-21 degrees" TO DISPLAY
ELSE
IF temperature > 21 degrees THEN
SEND "Perfect" TO DISPLAY
ELSE
SEND "No!, the perfect temperature for sleep is 18-21 degrees" TO DISPLAY
END IF
END IF
