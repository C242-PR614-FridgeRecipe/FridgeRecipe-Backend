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
| GET    | /api/user/favorite | Get a list of favorite recipes for the user. |
| GET    | /api/user/favorite/:recipeId | Get details of a specific favorite recipe. |
| POST   | /api/user/favorite | Add a recipe to the user's favorites. |
| DELETE | /api/user/favorite/:recipeId | Remove a recipe from the user's favorites. |

## CREDIT
[Muhammad Fauzi Nauval Abrari](https://github.com/FauziNauvalAbrari)
