## Overview
Chat Rooms is a real-time messaging application that allows users to create and join chat rooms, and exchange messages in real-time. This app demonstrates the implementation of modern Android development practices and Firebase integration for a seamless chatting experience.

## Key Features
- User authentication (Sign up, Login, Logout)
- Create and join chat rooms
- Real-time messaging within chat rooms
- List of available chat rooms

## Technologies Used
- **Language:** Kotlin
- **Architecture:** MVVM (Model-View-ViewModel)
- **Firebase:**
  - Authentication for user management
  - Firestore Realtime Database for storing chat rooms and messages
- **Jetpack Components:**
  - LiveData for observable data holder
  - ViewModel for managing UI-related data
- **Data Binding:** For efficient UI updates
- **RecyclerView:** For displaying lists of chat rooms and messages

## Architecture
This project follows the MVVM architecture pattern, which separates the app into three main components:
- Model: Represents the data and business logic
- View: The UI layer (Activities/Fragments)
- ViewModel: Acts as a link between Model and View, managing UI-related data

## Firebase Integration
- **Authentication:** Handles user sign-up, login, and logout processes
- **Firestore Realtime Database:** 
  - Stores chat room information
  - Manages real-time message synchronization

## Key Implementations
- Real-time updates using Firestore listeners
- Efficient list rendering with RecyclerView and ListAdapter
- Two-way data binding for seamless UI updates
- ViewModel for managing and persisting UI state across configuration changes

## Screenshots

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/41448a1b-c64f-4b5f-9322-eb292eb09bc5" width="300"></td>
    <td><img src="https://github.com/user-attachments/assets/a7f583f4-658b-4b51-85d5-2a897f102028" width="300"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ecd32bb3-96d6-4923-97fc-fae8e05fffd1" width="300"></td>
    <td><img src="https://github.com/user-attachments/assets/ed9ada9a-5f9b-427c-aad8-e9f55cd5e84a" width="300"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/f57cd185-07fb-43ce-bcb2-fc0ad277d21b" width="300"></td>
    <td><img src="https://github.com/user-attachments/assets/ec28989a-bece-46f8-9f8d-4ecb11ee5467" width="300"></td>
  </tr>
</table>


