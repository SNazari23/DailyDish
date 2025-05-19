# 👩🏻‍💻 Daily Dish Developer Manual 

# 🖌️ System Design 

DailyDish is a meal planning web application that helps users:
- Organize weekly meals
- Discover new recipes
- Manage grocery lists
- Save favorite meals

**Technology Stack**:
- Frontend: HTML, CSS, and JavaScript
- Backend: Node.js, Express
- Database: superbase 
- External API: TheMealDB



# ⚙️ Prerequisites
- Html 
- Superbase 
- Javascript
- CSS

# 🐱 Setup
Dowland all the files on the GitHub repository and run home.html. 
**Installing**:
- type in a terminal "npm install @supabase/supabase-js".  
- downland files on the GitHub repository. 

#  🧪 Testing 
**Type**:
1. npm run server  
2. npm run build 
3. npm start
4. npm test
5. npm run test:[unitTestName]
6. npm run test:profile

# ⛓️ DailyDish API server application
Base URL: https://www.themealdb.com/ 
## API Endpoints

### 🔐 User Endpoints

| Method | Endpoint           | Description                     | Auth Required |
|--------|--------------------|---------------------------------|---------------|
| `POST` | `/users`           | Register new user               | No            |
| `POST` | `/users/login`     | Authenticate user               | No            |
| `GET`  | `/users/me`        | Get current user profile        | Yes           |

### 🍽️ Meal Endpoints

| Method   | Endpoint           | Description                     | Auth Required |
|----------|--------------------|---------------------------------|---------------|
| `GET`    | `/meals`           | List all saved meals            | Yes           |
| `POST`   | `/meals`           | Save new meal                   | Yes           |
| `GET`    | `/meals/:id`       | Get specific meal details       | Yes           |
| `DELETE` | `/meals/:id`       | Remove saved meal               | Yes           |

# 😑 Known Issues
1. Logo Banner & Navigation Button: Inconsistent CSS styling.
2. Image Uploads: Users must scroll through the Explore page because uploads are currently only supported through links, making it difficult to keep everything within the web frame.
3. Auto-Save Profile: Users experience difficulties when trying to change their profile.

# 😎 Future Development RoadMap 
1. Resolving Known Issues.
2. Grocery List Generator: Generates a grocery list based on user-saved meals, showing the items needed for their weekly meal plan. It also displays stores where the items can be purchased and their prices.
3. Enhanced Search Filters: Adding more search filters to align with user goals, such as filtering by dietary preferences (e.g., low-calorie diet for weight loss).

 

