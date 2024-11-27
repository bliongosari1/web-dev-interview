# Task Description: User Fetch, List, and Click Tracker

## Goal
Build a web app where users can fetch random users from the [Random User API](https://randomuser.me/), display them in a list, and track the number of clicks for each user individually.

---

## Requirements

### Random User Fetching
- **On Page Load**: Fetch and display a random user's name and profile picture.
- **Fetch More Users**: Add a button to fetch additional users and append them to a list of previously fetched users.

### Click Counter for Each User
- Track the number of clicks for each user individually.
- Display the click count next to each user in the list.

### Reset Button
- Add a button to clear the entire list of users and reset all click counts.

---

## Bonus Features (Optional, Time Permitting)

1. **Persistent Data**: Save the list of fetched users and their click counts to local storage so that the data persists even after refreshing the page.
2. **Make sure API's aren't spammed when clicking fetch users**: Max 1 API calls per second 
