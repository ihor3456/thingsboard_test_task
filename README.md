# thingsboard_test_task
JavaScript Test Task: Star Wars Characters Table

Objective: Build a simple web page that displays a table of Star Wars characters. The data should be fetched from the public API SWAPI and displayed in a dynamic table.

Functional Requirements:
    1. Fetching Data:
        ◦ Fetch character data from https://swapi.info/api/people
        ◦ Display only 5 random characters from response
    2. Table Requirements:
        ◦ The table should include the following columns:
            ▪ Character Name (name)
            ▪ Gender (gender)
            ▪ Birth Year (birth_year)
            ▪ Home World (homeworld) - contains endpoint to fetch planet info;
        ◦ The homeworld column should have button and on click small popover element should open with a list of planet properties:
            ▪ Name (name)
            ▪ Climate (climate)
            ▪ Terrain (terrain)
            ▪ Population (population)
        ◦ Ensure the table is responsive for different screen sizes.
    3. Additional Features:
        ◦ Implement a search functionality to filter characters by name in real-time.

Implementation Guidelines:
    1. Use plain JavaScript, HTML, and CSS for the implementation.
    2. Use the Fetch API to retrieve data from SWAPI.
    3. You may use a CSS framework (e.g., Bootstrap) for styling, but it’s not required.
Submission Guidelines:
    • Send implemented page in single html file