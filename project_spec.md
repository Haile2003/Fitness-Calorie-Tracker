# **NutriLog**

## Table of Contents

1. [App Overview](#App-Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
1. [Build Notes](#Build-Notes)

## App Overview

### Description 

**A comprehensive and easy-to-use food diary app, Allows users to track and monitor their food intake, as well as set and achieve personal health goals.**

### App Evaluation

<!-- Evaluation of your app across the following attributes -->

- **Category:** Health & Fitness / Lifestyle
- **Mobile:** App available on iOS and Android, uses camera, mobile first experience.
- **Story:** Allows users to track and monitor their food intake, as well as set and achieve personal health goals. Users can log their meals, snacks, and beverages, and receive personalized recommendations based on their dietary needs and preferences. The app also offers features such as calorie tracking, macro tracking, and recipe suggestions.
- **Market:** Anyone who is interested in monitoring their food intake and improving their dietary habits could enjoy this app. It is particularly popular among those who want to lose weight, manage chronic health conditions, or simply maintain a healthy lifestyle.
- **Habit:** Users can use the app to log their meals and track their progress on a daily basis, and the app's personalized recommendations and recipe suggestions make it a highly habit-forming tool for improving overall health and nutrition. However, the frequency and extent of use may depend on individual dietary goals and preferences.
- **Scope:** The Food Diary app is focused on providing a comprehensive and customizable platform for tracking and monitoring food intake and dietary habits. While it offers features such as calorie tracking and recipe suggestions, it is primarily designed for logging and analyzing dietary data. However, some food diary apps may offer additional features such as meal planning and grocery list generation.

## Product Spec

### 1. User Features (Required and Optional)

Required Features:

- Food Database: A comprehensive database of foods and their nutritional values, which can be easily searched and added to the user's food diary.
- Calorie Tracking: The ability to track calories consumed and burned, as well as monitor macronutrient and micronutrient intake.
Stretch Features:

### 2. Chosen API(s)
**API #1: USDA FoodData Central API**

- **Endpoint:** /foods/search
  - **Required Feature:** Food Database
- **Endpoint:** /foods/{fdcId}
  - **Required Feature:** Detailed Nutrient Information

**API #2: OpenWeatherMap API**

- **Endpoint:** /weather
  - **Required Feature:** Weather Forecast
  - 
### 3. User Interaction

Required Feature: Food Diary

- **Add food to diary**
  - => **The selected food is added to the user's food diary, and the nutrient information is automatically calculated and displayed.**
  
- **Edit food in diary**
  - => **The user can edit the quantity of the food or remove it entirely from the food diary, and the nutrient information is updated accordingly.**

## Wireframes

<!-- Add picture of your hand sketched wireframes in this section -->
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Build Notes

Here's a place for any other notes on the app, it's creation 
process, or what you learned this unit!  

For Milestone 2, include **2+ GIFs** of the build process here!

## License

Copyright **2003** **Group 18**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
