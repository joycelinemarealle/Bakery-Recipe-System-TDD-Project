# Bakery-Recipe-System-TDD-Project

SUMMARY:
Developed a scalable Recipe System for a local bakery, employing Test-Driven Development (TDD) to ensure robust functionality including ingredient management, recipe creation, batch processing, and cost analysis.

PROJECT DETAILS:
Recipe System
Bakery Production Scaling
During a phase of significant expansion for a local bakery, they needed a system to efficiently manage their production and ingredient requirements as they scaled operations to supply multiple cafes across the city. My partner and I undertook this assessment using a Test-Driven Development (TDD) approach, ensuring each functionality was rigorously tested before implementation.

Part 1: Ingredients
We began by managing individual ingredients within the system:
US1: Added functionality to allow bakers to add ingredients to the system for future use.
US2: Implemented features enabling bakers to retrieve detailed information about each ingredient, including its name, purchase price, quantity per unit (e.g., "grams"), and supplier's name.
US3: Enabled modification of ingredient details, such as price updates, ensuring the system stayed current with changes.


Part 2: Recipes
Next, we focused on creating and managing recipes within the system:
US1: Developed capabilities to store recipes in the system for easy retrieval and usage.
US2: Implemented features allowing bakers to define recipes using one or more ingredients, ensuring clarity and usability of recipe information.
US3: Provided functionalities for specifying ingredient quantities needed per recipe and calculating the production output (e.g., "twelve cupcakes") for each recipe.
US4: Developed a feature to calculate the exact amounts of ingredients required for a single execution of a recipe, aiding in production planning.
US5: Extended functionalities to calculate ingredient quantities needed for executing a recipe multiple times, facilitating advanced production planning.
US6: Implemented calculations for determining production costs per unit and setting appropriate product prices to ensure desired profit margins, supporting bakery profitability strategies.

Part 3: Batches
We introduced batch management functionalities to streamline production planning:
US1: Enabled bakers to input desired output products and receive comprehensive ingredient requirements from the system, facilitating accurate ingredient ordering.
US2: Implemented features to calculate total production costs for a given batch of products, aiding in expense management.

Part 4: Outputs that are Ingredients
Finally, we addressed scenarios where outputs of one recipe serve as inputs for subsequent recipes:
US1: Developed functionalities allowing the definition of recipes using intermediate products produced by other recipes, reflecting complex production workflows in the bakery.
US2: Implemented calculations to determine intermediate steps required for producing a batch, enhancing understanding of intricate production chains.
US3: Extended functionalities to recursively calculate ingredient requirements for intermediate products used in recipes, ensuring comprehensive production planning.
US4: Integrated validation mechanisms to check for cyclic dependencies or unavailable ingredients within recipe/ingredient graphs, minimizing manual error handling for bakers.
