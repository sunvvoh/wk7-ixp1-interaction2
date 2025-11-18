# Slay the Fire Dragon! 🐉

An interactive browser-based game where you choose your class, select your weapon, and battle a fearsome fire dragon!

## Game Features

- **Class Selection**: Choose between Melee or Ranger classes
- **Weapon Choices**:
  - Melee: Sword or Wet Mop
  - Ranger: Bow or Super Soaker
- **Dragon Battle**: Face off against a fire-breathing dragon
- **Multiple Outcomes**: Win or lose based on your strategic attack choices

## How to Play

### Option 1: Open Directly in Browser
Simply open `index.html` in your web browser by double-clicking the file or dragging it into your browser window.

### Option 2: Run with Local Server
For a better experience, you can serve it with a local HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server -p 8000
```

Then visit `http://localhost:8000` in your browser.

## Game Instructions

1. Click "start" to begin
2. Choose your class: **melee** or **ranger**
3. Select your weapon based on your class
4. Click "lets gooooooo!!!!" to start the battle
5. Choose your attack wisely!
   - Some attacks will defeat the dragon
   - Others... well, you'll become ashes 💀

## Winning Strategy

Choose the right attack! Good attacks include:
- Sword Strike
- Mop Whack
- Arrow Strike
- Pew Pew

Avoid silly attacks like "I'm hungry" or "It looks like a boomerang" unless you want to lose!

## Customization

The game currently uses CSS-drawn graphics. The code includes comments showing where you can replace elements with custom images:
- Character sprites
- Weapon graphics
- Dragon sprite
- Fire effects
- UI elements

Check the HTML comments marked with `<!-- REPLACE -->` for customization points.

## Technologies Used

- Pure HTML5
- CSS3 (with animations and gradients)
- Vanilla JavaScript (no frameworks needed!)

## Browser Compatibility

Works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

Enjoy slaying dragons! 🗡️🏹
