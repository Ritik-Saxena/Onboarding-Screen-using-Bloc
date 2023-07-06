<img src="https://user-images.githubusercontent.com/62079355/121505629-9f847180-ca00-11eb-8db6-155e61a091a5.png" align="right" style: height=150 width=150/>

<img align='right' src='https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc/assets/62079355/30c43a63-23b5-42a2-b39b-4ef28d0b1f1e' width='200'>


<img align='right' src='https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc/assets/62079355/ce4dad91-f66a-47de-946d-ee1d37ef68ce' width='150'>

# Onboarding Screen using Bloc <br> [![Instagram](https://img.shields.io/twitter/url?label=%40ritiksaxenaofficial&logo=Instagram&style=social&url=https%3A%2F%2Fwww.instagram.com%2Fritiksaxenaofficial%2F)](https://www.instagram.com/ritiksaxenaofficial/)&nbsp;[![Instagram](https://img.shields.io/twitter/url?label=%40ultimateflutter&logo=Instagram&style=social&url=https%3A%2F%2Fwww.instagram.com%2Fultimateflutter%2F)](https://www.instagram.com/ultimateflutter/)
> Connect with me on Instagram <a href='https://www.instagram.com/ritiksaxenaofficial/'>@ritiksaxenaofficial</a>

<br>
This project implements an onboarding screen using the BLoC state management pattern in Flutter. The onboarding screen is typically the first screen that users see when they launch the app for the first time, and it provides an introduction to the app's features and guides users through the initial setup.

## Features
* A sleek and user-friendly onboarding screen design.
* Multiple screens/pages with customizable content and illustrations.
* BLoC state management for managing the onboarding flow.
* Seamless navigation between onboarding screens.
* Persistent state management to remember the user's onboarding progress.
* Easy customization and extension for adding new screens.

<br>

## Screens
<img src="https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc/assets/62079355/30aa916d-c616-471b-a9ef-3db18660b8c6" height=609, width=281>
<img src="https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc/assets/62079355/2d3e67e4-84a0-4e90-abde-aa1623bfaf05" height=609, width=281>
<img src="https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc/assets/62079355/dc3223fe-d8de-4006-97d4-a5a7228ca142" height=609, width=281>

<br>
<br>

## Preview
<img src="https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc/assets/62079355/c3227396-9127-456f-9e6d-7c291899f330" height=600, width=290>

<br>
<br>

## Folder Structure
The project follows a recommended folder structure for better organization and maintainability:

<pre>
  lib/
|- bloc/
|  |- onboarding_bloc.dart
|  |- onboarding_events.dart
|  |- onboarding_states.dart
|
|- screens/
|  |- login.dart
|  |- onboarding.dart
|
|- main.dart
</pre>

<b>bloc/</b>: Contains the BLoC implementation for managing the onboarding flow. <br>
<b>screens/</b>: Holds the main onboarding screen widget that orchestrates the flow.


<br>

## State Management with BLoC
The onboarding screen uses the BLoC (Business Logic Component) pattern for state management. It separates the UI from business logic, making the code more maintainable and testable.

The BLoC classes used in this project are:

<b>OnboardingBloc</b>: Manages the state and handles events related to the onboarding flow. <br>
<b>OnboardingEvent</b>: Represents the different events that can occur during the onboarding process. <br>
<b>OnboardingState</b>: Defines the various states that the onboarding screen can be in. <br><br>
The OnboardingBloc listens for events, updates the state accordingly, and emits the updated state to the UI. The UI components subscribe to the state changes and update their appearance based on the current state.

<br>


#### Feel free to explore and modify the code to fit your app's requirements!

<br>


---
If you like this repository, do <img src="https://user-images.githubusercontent.com/62079355/200077014-f3e95bba-57a6-4c7a-b26a-212bf18e5162.png" width=25 height=25> and <img src="https://user-images.githubusercontent.com/62079355/220893415-ea2015e9-6df6-4de2-ab66-041a3f890be2.png" width=25 height=25> the repo for more amazing stuff coming soon.

---

[![GitHub stars](https://img.shields.io/github/stars/Ritik-Saxena/Onboarding-Screen-using-Bloc?style=social)](https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc)
[![GitHub followers](https://img.shields.io/github/followers/Ritik-Saxena?style=social)](https://github.com/Ritik-Saxena?tab=followers)
[![GitHub forks](https://img.shields.io/github/forks/Ritik-Saxena/Onboarding-Screen-using-Bloc?style=social)](https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc)
[![GitHub watchers](https://img.shields.io/github/watchers/Ritik-Saxena/Onboarding-Screen-using-Bloc?style=social)](https://github.com/Ritik-Saxena/Onboarding-Screen-using-Bloc)
