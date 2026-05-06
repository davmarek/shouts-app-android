# Shouts

A Twitter/X-inspired microblogging Android app built as a school project. Users can post short messages ("shouts"), browse a feed, view user profiles, and search for content.

## Features

- Registration & login with JWT authentication
- Browse, create, edit, and delete shouts
- User profiles with their shout history
- Search shouts by content

## Tech Stack

| Area | Technology |
|---|---|
| Language | Kotlin |
| UI | Jetpack Compose, Material 3 |
| Architecture | MVVM (ViewModel + Repository) |
| Networking | Retrofit, OkHttp |
| Navigation | Navigation Compose |
| Async | Kotlin Coroutines |
| Backend | REST API (Azure) |

## Architecture

The app follows the MVVM pattern - UI screens observe `ViewModel` state, ViewModels delegate data operations to Repositories, and Repositories communicate with a remote REST API via Retrofit.

---

> School project - Android Development course
