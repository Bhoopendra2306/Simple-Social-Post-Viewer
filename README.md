# Simple Social Post Viewer

A basic Unity project simulating a social media-style post using dummy data. Created as part of a Unity intern assignment to demonstrate understanding of UI design, C# scripting, and user interaction.

## 📌 Features

- Display a single social media post with:
  - Username (text)
  - Profile picture (placeholder image)
  - Post content (dummy text)
  - Like button (toggles liked/unliked state)

- Like button changes appearance and optionally updates like count
> _"Required UI animations are implemented using [LeanTween](https://assetstore.unity.com/packages/tools/animation/leantween-3595), a lightweight and powerful tweening engine for Unity."_

## 📁 Data Format

Supports hardcoded values or local JSON loading. Example JSON structure:
```json
{
  "username": "John Doe",
  "profilePic": "profile1.png",
  "content": "This is my first post!",
  "likes": 10
}


