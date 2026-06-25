# 75 Day Challenge Tracker

A simple browser-based tracker for a 75-day challenge. It lets you set a start date, check off each day, see your progress, and keep notes.

## How to Open the Tracker

1. Open this project folder:

   ```bash
   cd 75DayChallengeTracker
   ```

2. Open `index.html` in your browser.

   You can double-click the file in Finder, or run:

   ```bash
   open index.html
   ```

## How to Use the Tracker

1. Choose your start date in the **Start date** field.
2. The tracker will automatically show dates for all 75 days.
3. Click a tile to mark that day complete.
4. Click the same tile again to unmark it.
5. Use **Mark next** to check off the next unfinished day.
6. Use **Clear all** to reset completed days.
7. Add goals, rules, or reflections in the **Notes** box.

## What the Dashboard Shows

1. **Progress ring**: Your overall completion percentage.
2. **Done**: Number of completed days.
3. **Left**: Number of days remaining.
4. **Today**: Which challenge day today is, based on your start date.
5. **Date range**: The first and last day of your 75-day challenge.

## Saving Progress

Your progress is saved automatically in your browser using local storage.

That means:

1. You do not need to create an account.
2. You can refresh the page without losing progress.
3. Your progress stays in the same browser on the same computer.
4. Clearing browser data may delete your saved progress.

## GitHub Setup

This project is connected to:

```text
https://github.com/veloSVity/75DayChallengeTracker.git
```

## How to Push Changes to GitHub

1. Open Terminal.
2. Go to the project folder:

   ```bash
   cd 75DayChallengeTracker
   ```

3. Check your changes:

   ```bash
   git status
   ```

4. Stage changed files:

   ```bash
   git add .
   ```

5. Commit your changes:

   ```bash
   git commit -m "Update tracker"
   ```

6. Push to GitHub:

   ```bash
   git push -u origin master
   ```

If GitHub asks you to sign in, follow the prompt in Terminal.

## Files

```text
index.html  Main tracker app
README.md   Project instructions
```
