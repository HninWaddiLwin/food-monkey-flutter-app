# Food Monkey: Mobile Shopping App

A cross-platform mobile app (Android and iOS) for browsing products, placing orders, and chatting with the shop in real time.

Built June–July 2021 in Yangon, Myanmar, as a self-taught project during internet shutdowns and power cuts after the military coup. Uploaded to GitHub in 2026.

## Features
- Splash screen that checks the app version with the server before opening
- User registration and login with token-based authentication
- Product browsing by category and tag, with page-by-page loading (pagination)
- Product detail pages, shopping cart, order checkout, and order history
- Real-time customer chat using WebSockets (Socket.IO), including image messages
- Bilingual interface with English (Lora) and Burmese (Padauk) fonts

## Tech Stack
- Language: Dart (null safety)
- Framework: Flutter
- Libraries: http (REST API client), socket_io_client (real-time chat), image_picker

## Project Structure
- lib/pages/: 10 screens (Home, Login, Register, Product, Detail, Cart, Chat, History, Preview, Splash)
- lib/models/: 7 data models (Product, Category, Tag, User, Message, History, ImgResult)
- lib/utils/: API calls and app settings
- lib/helpers/: custom shape painters for the UI
- assets/: fonts, icons, and images
