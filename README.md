# 🎲 Dice Roller

A beautiful, interactive web-based dice roller application. Roll multiple dices with customizable sides and track your statistics.

## Features

- **Multiple Dices**: Roll up to 16 dices simultaneously
- **Customizable Sides**: Configure the number of sides per dice (2-100)
- **3D Animation**: Smooth 3D rotating dice animation during rolls
- **Statistics Tracking**: Automatically tracks total rolls, last roll result, and rolling average
- **Square Grid Layout**: Dices are displayed in an organized square grid pattern
- **Reset Statistics**: Clear all statistics with a confirmation dialog
- **Keyboard Support**: Press Enter to roll the dices

## How to Use

1. **Open the Application**: Open `index.html` in your web browser
2. **Configure Dices** (Optional):
   - Click the ⚙️ settings icon in the top right
   - Set the number of dices (1-16)
   - Set the number of sides per dice (2-100)
   - Click "Save"
3. **Roll the Dices**:
   - Click the "Roll Dice" button or press Enter
   - Watch the dices animate and see the results
4. **Check Statistics**:
   - View total rolls, last roll, and average below the dices
   - Click "Reset Statistics" to clear the statistics (with confirmation)

## Configuration

Click the ⚙️ icon to open the configuration modal where you can set:

- **Number of Dices**: 1 to 16 dices
- **Sides per Dice**: 2 to 100 sides per dice

Configuration changes automatically reset the statistics to start fresh.

## Grid Layout

Dices are arranged in a square pattern:
- 1 dice: 1×1
- 2 dices: 1×2
- 3 dices: 2×2 (one empty space)
- 4 dices: 2×2
- 5-9 dices: 3×3
- 10-16 dices: 4×4

## Technical Details

- **Built with**: HTML5, CSS3, and JavaScript
- **3D Effects**: Uses CSS 3D transforms for dice animation
- **No Dependencies**: Pure vanilla JavaScript, no external libraries required
- **Responsive Design**: Works on desktop and tablet devices

## License

MIT License
