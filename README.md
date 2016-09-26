#pull it to your local repo and run "npm install" in your terminal to install all the require packages
### project 3 "A-meal-zing" meal planner backend API services
- RESTful APIs on express

### routes
- GET /API/recipes : all recipes
- GET /API/recipes/:id : specific recipe
- POST /API/meals/user_id?day? :  create a new meal
- PUT /API/meals/:id : add a recipe to that meal
- GET /API/meals/:id : show recipes in the meal
- DELETE /API/meals/:id : delete meal
- GET /API/meals? with data {start: yyyy-mm-dd,end:yyyy-mm-dd, user_id:id} : get all meals for a user within the selected range
- PUT /API/users? with data {id:id, recipe_id:recipe_id, action: like/dislike} : allows a user to like or dislike a recipe
- GET /API/users/list? with data { id:user_id, action: like/dislike} : get favourite list or blacklist for the user

### "A-meal-zing" backend [demo]
[demo]:<https://team5-backend.herokuapp.com/>

### "a-meal-zing"  [project demo]
[project demo]: <https://wdi4groupproject.github.io/front_end_consume_A_Pie/views/>
