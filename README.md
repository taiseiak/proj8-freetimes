# proj8-freetimes
Snarf appointment data from a selection of a user's Google calendars and
let the user select some. It will show the busy times in yellow, and the
open times in green.

## Author

Taisei Klasen taiseik@uoregon.edu http://github.com/taiseiak

## Implementation

The application uses the google calendar api to search what events
are happening in the time frame that is specified in the check box.
The backend is done with Flask. For now it takes time for the calendar
to actually get information.

## Running the program

When running the program you will need to install all the dependencies
from pip, by using a virtual environment. When running the actual server
you need to be inside the meetings directory, or the credentials file
and google key file cannot be found.