
Diet and Health APP - Mobile Android Application developed in Java with Android Studio.

This app was developed because traditional calorie trackers suffer from the tedious task of having to manually record foods and their nutrition. Fict adds the ability to take a photo of your meal, and use Visual Recognition to classify the dish, and return nutritional information. The goal of the app was to create something useful and simple that we could see ourselves using everyday.

![Login Activity](https://user-images.githubusercontent.com/97665712/153186989-4bb3ffd7-626a-40f9-ad1c-8f9c4c2950e9.JPG)


# Home Page
The daily home screen page greets users and acts as a hub for convenient access to all the other features of the app. At the top of the page is the Calories section which displays the calorie goal, calories consumed, and calories remaining. Under it is the the Nutrition section which shows the 3 main macro nutrients: protein, fat, carbohydrates and the user's current weight which can be changed by tapping on the scale icon. Underneath that is a Food section which displays all the meals the user recorded that day. Finally on the bottom there is a task bar for easy navigation to the History, Add Food, and Macros Calculator pages.

![Dailypage Activity](https://user-images.githubusercontent.com/97665712/153187080-e8526fdd-b677-4607-ad07-35d51c0fe756.JPG)

# Visual Recognition
The user has the option to either manually input nutritional information for their dish, or use the Visual Recognition option. This option allows the user to take a photo of their meal, and utilizing IBM Watson's Visual Recognition API, return a list of possible classifications for the dish.

![Manual_add Activity](https://user-images.githubusercontent.com/97665712/153188086-5aa7bf41-9db1-4224-b205-69e8df94fe08.JPG)


# Nutritional Information
After the user selects the correct dish, the Nutritionix API is used to return relevant caloric, and nutritional information. This information is then recorded in an database for caching, in the case of repeated food entries. This improves response time, limits accesses to the network, and reduces API calls. The information is also saved to the daily food intake table, which is then displayed on the homepage.

![Selecting food Activity](https://user-images.githubusercontent.com/97665712/153188266-ab111e3d-b97f-440f-af9e-28faab2d8ba5.JPG)


# Macronutrient Calculator
Upon first use of the app the user is brought to a macronutrients / "If It Fits Your Macros" (IIFYM) calculator. IIFYM is a widely used dieting plan that allows you to eat any type foods you want, so long as you don't go over your caloric and macronutrient values for the day. The user fills in a few personal details to gauge their fitness needs and select a goal. The numbers are plugged into an IIFYM formula to determine the user's daily caloric and macronutrients intake. This information is then saved into the database the app will display as goals everyday.



![Manual_add Activity](https://user-images.githubusercontent.com/97665712/153187333-54796c9b-6fd9-45e7-a7fb-19b8f7dbc91f.JPG)


# History
The data for the user's food intake is saved locally on a database for future access in order to track the user's progression. After selecting an entry, a snapshot of that day's daily home page is brought up so the user can view changes day by day. 

![History Activity](https://user![Goals Activity](https://user-images.githubusercontent.com/97665712/153187489-e7ee12fb-130d-448d-8374-df50fd782445.JPG)
-images.githubusercontent.com/97665712/153187452-a5441302-40ac-40b8-8168-49646ec6d3a2.JPG)
