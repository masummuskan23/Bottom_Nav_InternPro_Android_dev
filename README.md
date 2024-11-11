Bottom Navigation Bar with Multiple Fragments

This Android app demonstrates how to implement a bottom navigation bar that allows users to switch seamlessly between multiple fragments. The app includes three primary fragments: Home, Profile, and Settings, along with a smooth navigation experience and proper back stack handling.

Features

Bottom Navigation Bar: A bottom navigation bar for easy access to multiple fragments.
Multiple Fragments: Home, Profile, and Settings fragments with individual layouts.
Back Stack Navigation: Properly manages back stack to prevent unexpected behaviors during fragment transitions.
Smooth Navigation: Ensures smooth and consistent transitions between fragments.

Project Structure

MainActivity: Hosts the bottom navigation bar and manages fragment transactions.
Fragments: Three main fragments (HomeFragment, ProfileFragment, SettingsFragment) with separate XML layouts.
Navigation Handling: Fragment transactions are managed in MainActivity to ensure smooth and consistent navigation.

Implementation Details

Bottom Navigation: The bottom navigation bar is set up in activity_main.xml and managed in MainActivity.java.
Fragment Transactions: Fragment transactions are used to switch between fragments while adding each transaction to the back stack.
Back Stack: Custom handling for back stack to avoid fragment recreation and ensure a smooth user experience.

Screenshots
![1](https://github.com/user-attachments/assets/ea8a572d-50f6-441c-a8c6-f7a2022202b9)
![2](https://github.com/user-attachments/assets/8a45bf37-433e-4f2b-9a1f-9bf836e4befa)
![3](https://github.com/user-attachments/assets/71dd84ed-faa7-431b-83ed-3637b8d6e4be)

