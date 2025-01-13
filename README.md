# New Year Countdown

This webpage displays a countdown timer to the New Year. It features a dynamic display that alternates colors and shows a confetti effect upon reaching zero.

## Features

*   Countdown timer that accurately calculates the remaining time until the New Year.
   
*   Alternating background and text colors between black and white when the remaining time is less than or equal to 1 minute.
   
*   Confetti effect that is displayed when the New Year arrives.
   
*   Dynamic calculation of the next New Year's Day, ensuring it works every year.

## Usage

1.  Open the `countdown_v3.html` file in a web browser.
    
2.  The countdown timer will automatically start, displaying the remaining time until the New Year.
    
3.  Once the timer reaches zero, the background and text colors will alternate, and a confetti effect will be displayed to celebrate the New Year.
    

## Code Explanation

*   The JavaScript code calculates the time remaining until the next New Year's Day by dynamically determining the current year and setting the target date to January 1st of the next year.
   
*   The `formatTime` function converts the remaining time in milliseconds to a human-readable format (days, hours, minutes, seconds).
   
*   The `alternateColors` function alternates the background and text colors between black and white when the remaining time is less than or equal to 1 minute.
   
*   The `displayConfetti` function creates and displays a confetti effect when the New Year arrives.

## Additional Notes

*   The countdown timer is accurate to within 1 second.
   
*   The confetti effect is displayed for 5 minutes.
   
*   The webpage is designed to work in all modern web browsers.
