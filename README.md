# Chess.com Stats Card
A beautiful glassmorphism card displaying Chess.com player statistics with gradient background and interactive elements.

## Features

✨ **Modern UI Design**
- Glassmorphism effect with backdrop blur
- Gradient background with dark theme
- Responsive layout for all devices
- Hover animations on stat cards

📊 **Comprehensive Stats Display**
- Shows Rapid, Blitz, Bullet, and Daily chess stats
- Displays current and best ratings
- Includes win/loss/draw records
- Tactics and Puzzle Rush statistics

🎨 **Visual Enhancements**
- Color-coded game type indicators
- Rating glow effects
- Clean typography hierarchy
- Interactive elements

## Technologies Used

- HTML5
- CSS3 (with custom animations)
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- Glassmorphism design technique

## How to Use

1. Simply open the `index.html` file in any modern browser
2. To customize for a different player:
   - Replace the sample data in the HTML with actual API response
   - Update the player name and avatar as needed

## Data Structure

The card displays statistics from the Chess.com API which includes:

```json
{
  "chess_rapid": {
    "last": {"rating": 334},
    "best": {"rating": 490},
    "record": {"win": 247, "loss": 239, "draw": 46}
  },
  "chess_blitz": {
    "last": {"rating": 257},
    "best": {"rating": 345},
    "record": {"win": 811, "loss": 831, "draw": 69}
  },
  // ... other game modes
}
