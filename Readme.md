# ♔ Chess Master ♕

A fully-featured, interactive chess game built with HTML, CSS, and JavaScript. Play against a friend locally or challenge the computer AI in this beautifully designed chess implementation.

## 🎯 Features

### Game Modes
- **Human vs Human**: Play with a friend on the same device
- **Human vs Computer**: Challenge the built-in AI opponent

### Complete Chess Implementation
- ✅ All standard chess piece movements
- ✅ Special moves (En passant, Castling, Pawn promotion)
- ✅ Check, Checkmate, and Stalemate detection
- ✅ Move validation and legal move highlighting
- ✅ Turn-based gameplay with visual indicators

### User Interface
- 🎨 Beautiful wooden chess board design
- 🔮 Smooth animations and hover effects
- 💡 Interactive move highlighting (green for valid moves, red for captures)
- 📱 Responsive design for desktop and mobile
- 🎭 Elegant piece selection with visual feedback

### Additional Features
- 📖 Built-in rule book with comprehensive chess rules
- 🔄 Game restart functionality
- 🏠 Main menu navigation
- 👑 Pawn promotion dialog with piece selection
- 📊 Game status tracking and announcements

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or installations required

### Installation
1. Download the HTML file
2. Open it in your web browser
3. Start playing immediately!

### How to Play
1. **Launch the game** - Open the HTML file in your browser
2. **Select game mode** - Choose between Human vs Human or Human vs Computer
3. **Make moves** - Click on a piece to select it, then click on a valid square to move
4. **Special moves** - The game automatically handles all special chess rules
5. **Win the game** - Checkmate your opponent's king!

## 🎮 Game Controls

| Action | Method |
|--------|--------|
| Select piece | Click on any of your pieces |
| Move piece | Click on a highlighted valid square |
| Deselect | Click on the same piece again or empty square |
| Restart game | Click the "🔄 Restart" button |
| Main menu | Click the "🏠 Main Menu" button |
| View rules | Click "📖 Rule Book" from main menu |

## 📋 Chess Rules Implemented

### Piece Movements
- **Pawn (♙♟)**: Forward one square, captures diagonally, two squares on first move
- **Rook (♖♜)**: Horizontal and vertical movement
- **Bishop (♗♝)**: Diagonal movement
- **Knight (♘♞)**: L-shaped movement (2+1 squares)
- **Queen (♕♛)**: Combination of rook and bishop
- **King (♔♚)**: One square in any direction

### Special Rules
- **En Passant**: Special pawn capture move
- **Pawn Promotion**: Automatic promotion dialog when pawn reaches end
- **Castling Rights**: Tracked and enforced (basic implementation)
- **Check Detection**: Automatic check detection and highlighting
- **Checkmate/Stalemate**: Game ends automatically with appropriate message

## 🤖 AI Features

The computer opponent includes:
- **Move Validation**: Only makes legal moves
- **Capture Priority**: Prefers capturing opponent pieces
- **Random Strategy**: Adds unpredictability to gameplay
- **Responsive Timing**: Moves after a brief delay for natural feel

## 🎨 Visual Design

### Color Scheme
- **Board**: Rich wooden brown tones
- **Pieces**: High-contrast white and black Unicode symbols
- **Highlights**: Gold for selection, green for valid moves, red for captures
- **Background**: Elegant dark gradient

### Animations
- Smooth piece hover effects
- Pulsing selection animation
- Scaling transitions for interactive elements
- Glowing highlights for move validation

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Structure and layout
- **CSS3**: Styling, animations, and responsive design
- **Vanilla JavaScript**: Game logic and interactivity

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### Performance
- Lightweight single-file implementation
- No external dependencies
- Optimized for smooth 60fps animations
- Efficient move calculation algorithms

## 📱 Mobile Support

The game is fully responsive and works on:
- 📱 Smartphones (iOS/Android)
- 📟 Tablets
- 💻 Desktop computers
- 🖥️ Large screens

## 🎯 Future Enhancements

Potential improvements for future versions:
- [ ] Advanced AI with difficulty levels
- [ ] Online multiplayer support
- [ ] Move history and notation
- [ ] Save/load game functionality
- [ ] Chess puzzle mode
- [ ] Timer functionality
- [ ] Sound effects
- [ ] Multiple board themes

## 🐛 Known Limitations

- Castling moves are not fully implemented
- AI uses basic random strategy
- No move history display
- No game save functionality

## 🤝 Contributing

This is a self-contained chess implementation. Feel free to:
- Report bugs or issues
- Suggest new features
- Improve the AI logic
- Enhance the visual design
- Add new game modes

## 📄 License

This project is open source and available under the MIT License.

## 🎉 Acknowledgments

- Unicode Consortium for chess piece symbols
- Chess.com for rule references
- Modern web standards for making this possible

---

**Enjoy your chess games! ♔♕♖♗♘♙**