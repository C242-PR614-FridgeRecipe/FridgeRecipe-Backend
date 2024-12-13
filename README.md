## LOGIN API 
| ENDPOINTS | METHOD | ACTION |
| :--------- | :--------- | :--------- |
| /api/auth/login | POST | User login. Returns authentication token on successful login |
| /api/auth/reister | POST | User registration. Creates a new user account |

## SEARCH RECIPE API
| ENDPOINTS | METHOD | ACTION |
| :--------- | :--------- | :--------- |
| /api/recipes/search?ingredients=ingredients1,ingrdients2,.. | GET | Search for recipes based on ingredients |
| /api/recipes/:id | GET | Get details of a recipe by its ID |

## FAVORITE RECIPE API 
| ENDPOINTS | METHOD | ACTION |
| :--------- | :--------- | :--------- |
| /api/user/favorite | GET | Get a list of favorite recipes for the user. |
| /api/user/favorite/:recipeId | GET | Get details of a specific favorite recipe. |
| /api/user/favorite | POST | Add a recipe to the user's favorites. |
| /api/user/favorite/:recipeId | DELETE | Remove a recipe from the user's favorites. |

## CREDIT
[Muhammad Fauzi Nauval Abrari](https://github.com/FauziNauvalAbrari)
