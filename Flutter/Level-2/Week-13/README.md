### 📚 Resources

- **▶️ YouTube -** API  : [→ LINK](https://youtube.com/playlist?list=PLdIyiVt7IcnG4CFtsxF7C8EkHnJ9z3uFd&si=qFeIj_bBAI64uvmJ)
- Async Dart: this playlist is very good for revising some main concepts like Async, Futures, Null Safety, etc.
    
    https://youtube.com/playlist?list=PLjxrf2q8roU0Net_g1NT5_vOO3s_FR02J
  ### 🎯 Tasks

### Task:

In this project, each member will do the required app individually. The app we will work on is a Food Recipe App. We will use the [**Spoonacular API](https://spoonacular.com/food-api).** The app should have the following screens with the following features:

- **First Screen:** Recipes List: this screen should show a list of different recipes. You can achieve this using the Search Recipe section in the API Docs. When the user clicks on any recipe, the app should navigate to the second screen to show the recipe details.
- **Second Screen:** Recipe Details: when the user clicks a specific recipe, it should navigate the user to another screen with the recipe details. You can achieve this using the Get Recipe Information section in the API Docs. Also, a very mandatory feature in this screen, the user should have a button to choose the Recipe as a favorite recipe. For the favorite recipe part, we will use SQLite to save favorite recipes id, name and some more data to use in the third screen, to be able to retrieve the recipe information later.
- **Third Screen:** Favorite Recipes List:  this screen should show a list of favorite recipes using the favorite recipes added to the SQLite database using the favorite button in the Recipe Details Screen. When the user clicks on any recipe, the app should navigate to the second screen to show the recipe details.
- For this app, we will use the following design. The components marked with yellow are excluded, this design is from [this page](https://uxplanet.org/case-study-freshly-dropped-app-ux-design-for-cooking-and-shopping-a19c7a00c322) but we only need the general main details. For the first and third screen, they will be similar but the screen title will change. The user can navigate between Recipes List and Favorite Recipes List using a BottomNavigationBar, Home and Favorites. The design shouldn’t be exactly the same, so feel free to add or edit any part to make it better.

[Example]([attachment:2f159d15-6681-4b18-b23c-68afed9ec6cc:Inked1_bbxRRAQBVGRXQMurjuXixA_LI.jpg](https://img.notionusercontent.com/s3/prod-files-secure%2F69265367-28f9-442a-baad-99d149be1c46%2F2f159d15-6681-4b18-b23c-68afed9ec6cc%2FInked1_bbxRRAQBVGRXQMurjuXixA_LI.jpg/size/w=1420?exp=1763405762&sig=aRs67lUhkIB2qG_a243afEYf0fr7MClkD_rHlXD4tdc&id=26c3f5d2-0d4b-8037-bf6f-c6ed21a377ca&table=block))

You can use this API:

https://www.themealdb.com/api.php

and this design:

[Figma Link](https://www.figma.com/design/u7no9PBTXiwxINFGG7kQ6O/Food-Recipe-App--Community-?node-id=1-3&p=f&t=9YCriQAwZlkc7wsz-0)

to build the Home screen, the Save screen, and the Details screen.
