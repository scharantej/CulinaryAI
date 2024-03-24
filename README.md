## Flask Application Design
### HTML Files:
- index.html: the main page displayed to users, containing the interface for inputting dietary preferences, restrictions, and nutritional goals. Also includes a button for submitting the information.
- meal_plan.html: displays the personalized meal plan generated based on the user's input. Includes a list of meals with their recipes.

### Routes:
- /: the route for the index.html page, which handles the initial display of the website and user input form.
- /meal_plan: the route for the meal_plan.html page, which processes the user's input and generates the personalized meal plan. This route receives the user's input as form data and uses it to generate the meal plan, which is then displayed on the meal_plan.html page.