## Flask Application Design

### HTML Files

- `index.html`: The homepage of the application. It will include a search bar for users to input their location and search for hairdressers.
- `results.html`: This page will display the list of hairdressers found near the user's location. It will include information such as the name, address, phone number, and website of each hairdresser.
- `appointment.html`: This page will allow users to schedule an appointment online with the selected hairdresser.

### Routes

- `/`: The route that renders the `index.html` page.
- `/search`: The route that processes the user's search query and returns the results. This route will query a database or API to find hairdressers near the user's location.
- `/appointment`: The route that renders the `appointment.html` page and allows the user to schedule an appointment. This route will require additional functionality to handle form submissions and store appointment data.