# Manga-Chart-Instructions

## Requirements
- Use the modern native mobile development framework
    - **iOS:** Xcode + SwiftUI + Combine
    - **Android:** Android Studio + Jetpack Compose + Coroutines
- Fetch manga data from the **[Jikan API](https://api.jikan.moe/v4/top/manga)**.
    - **Tips:** (We already know)
        - The API **will** give us a success response
        - The API **will** provide the same data in every response. 
- Implement navigation between scenes.
- Display information as specified below.

**Bonus Points:** (Not required)
- Use a TDD commit sequence pattern in the repository
    - Red commit (Stub + Failing test)
    - Green commit (Implementation + Passing test)
    - Blue commit (Refactor + Passing test)

## Overview
Create a mobile app that allows users to explore the top 20 manga titles. The app should have the following scenes:

1. **Start Scene**
   - Display a start button.
   - Upon tapping the button, navigate to the second scene.

2. **Top Manga Scene**
   - Display a list of the top 20 manga titles.
   - Display each listing in rank order with the following information:
     - Rank
     - Title
   - Tapping a title should navigate to the detail scene.

3. **Manga Detail Scene**
   - Display detailed information for the selected manga:
     - **Image**: Show the manga cover (JPEG image).
     - **Status**: Ongoing, completed, etc.
     - **Synopsis**: Brief description of the manga.
     - **Title**: The manga's title.
     - **URL**: Link to the manga's official page.



Good luck, and happy coding!
