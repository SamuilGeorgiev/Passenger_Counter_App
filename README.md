# Passenger Counter App

This is a simple web application that counts passengers entering and exiting a location (e.g., a subway station, an event venue).

## Functionality

The app features:

* **Counter Display:** A prominent display showing the current passenger count.
* **Increment Button:** A button to increase the count when a passenger enters.
* **Save Button:** A button to save the current count to a log.
* **Entry Log:** A display area showing the history of saved counts.
* **Reset Button:** A button to reset the counter to zero.

## How to Use

1.  **Increment:** Each time a passenger enters, click the "Increment" button. The main counter display will update.
2.  **Save Count:** To record the current count, click the "Save" button. The count will be added to the entry log below.
3.  **View Log:** The entry log displays a history of the saved counts, showing the order in which they were recorded.
4.  **Reset Counter:** To reset the counter to zero, click the "Reset" button. This will not clear the entry log.

## Technologies Used

* **HTML**: For structuring the web page.
* **CSS**: For styling the layout and appearance.
* **JavaScript**: For implementing the counting logic and updating the display dynamically.

## Deployment

This app is deployed on Netlify and can be accessed here:

* [Netlify Deployment](https://app.netlify.com/sites/zippy-cajeta-77deed/overview)

## Potential Enhancements

* **Decrement Button:** Add a button to decrease the count when a passenger exits.
* **Timestamp:** Include a timestamp with each saved entry in the log.
* **Multiple Counters:** Allow the user to manage multiple counters (e.g., for different entrances).
* **User Interface Improvements:** Enhance the design and user experience.
* **Data Persistence:** Store the count and log data persistently (e.g., using local storage or a database).
