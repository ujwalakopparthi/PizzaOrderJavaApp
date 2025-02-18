
# 🍕 Pizza Ordering App

A simple Android app for ordering pizza, allowing users to choose pizza size, crust, and toppings. The app also contains a form where users can enter their name, and a settings and help menu. 🍕

## Features 🌟

- **Home Screen** 🏠: User enters their name to get started with the pizza order.
- **Menu Screen** 🍽️: Users can choose pizza size, crust, and toppings.
- **Help Menu** ❓: Provides instructions for the user on how to use the app.
- **Exit Confirmation** ❌: Prompts user to confirm before exiting the app.
- **SQLite Database** 💾: Stores pizza orders with details like size, crust, and toppings.

## Prerequisites 🛠️

To build and run this application, you need to have the following:

- Android Studio (or any preferred Android IDE) 💻
- Android SDK 📱
- Java Development Kit (JDK) ☕

## Installation 🔧

### Clone the Repository

```bash
git clone https://github.com/ujwalakopparthi/PizzaOrderJavaApp.git
cd pizza-order-app
```

### Import the Project into Android Studio

1. Open Android Studio.
2. Select **File > Open**.
3. Choose the directory of the project.
4. Android Studio will sync and install any required dependencies.

### Build and Run the App 🚀
- Select your preferred device (or emulator) and click on the **Run** button in Android Studio.

## Screenshots 📸

### Home Screen

![Home Screen](screenshots/home_screen.png)

### Menu Screen

![Menu Screen](screenshots/menu_screen.png)

## Files and Structure 🗂️

The app is organized as follows:

- **`OrderPage.java`**: Activity that shows the order menu for pizza.
- **`Pizza.java`**: Main activity for the app where users enter their name and start the order.
- **`PizzaData.java`**: SQLite database helper class to manage the pizza order data.
- **`strings.xml`**: Contains all the string resources for text displayed in the app.
- **`colors.xml`**: Contains color resources for the app.
- **`dimens.xml`**: Contains dimension values for layout.
- **`menu.xml`**: Defines the app’s menu options (Settings, Help, Exit).
- **`AndroidManifest.xml`**: Application-level configuration for activities and permissions.
- **`build.gradle`**: Gradle build file for project dependencies and configuration.

## Configuration ⚙️

### SQLite Database

The application uses an SQLite database (`pizza.db`) to store pizza orders. The database schema includes the following columns:

- `id`: Auto-increment primary key.
- `size`: Pizza size (e.g., small, medium, large).
- `crust`: Pizza crust (e.g., thin, thick).
- `toppings_whole`: Whole pizza toppings (optional).
- `toppings_left`: Left half toppings (optional).
- `toppings_right`: Right half toppings (optional).


## Acknowledgments 🙏

- Android SDK 📱
- SQLite for local storage 💾

## Contributing 🤝

Feel free to fork this repository and submit pull requests with bug fixes or improvements.

---

Let me know if you'd like to make further adjustments!


 ![image](https://github.com/user-attachments/assets/0c781e00-a184-485a-b09f-98b920b82ab2)

 ![image](https://github.com/user-attachments/assets/5ffcde1f-c7be-40ad-8223-1087c90a2cd7)

 ![image](https://github.com/user-attachments/assets/a8c40fac-940f-4fe0-8b7d-a98d398e14a4)

 ![image](https://github.com/user-attachments/assets/73704409-8125-4f44-abd5-7f5d99b36454)
 
 ![image](https://github.com/user-attachments/assets/e835cb80-661d-46ac-83b5-d8153c2b2f5e)
