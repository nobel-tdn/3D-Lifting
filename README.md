# 3D Volley Shoot ⚽

A 3D volleyball shooting game in the browser, using webcam motion tracking and 3D physics. Score goals by volleying the ball into the moving targets!

🎮 **Play here: [https://your-username.github.io/3d-volley-shoot/](https://nobel-tdn.github.io/3D-Volley-Shoot/)**

## How to Play

1. Allow webcam access when prompted
2. Position yourself so your full body is visible to the camera
3. Use your knees and feet to volley the soccer ball into the goal
4. When you score, the goal will move to the opposite side!
5. To reset the ball position, perform a squat motion (move your knees down)

## Features

- **3D Volleyball Shooting**: Aim and shoot the ball into moving goal posts
- **Dynamic Goal System**: Goals automatically switch sides after each score
- **Real-time Motion Tracking**: Uses MediaPipe for accurate body pose detection
- **3D Physics Simulation**: Realistic ball physics with Rapier3D
- **No Downloads Required**: Play directly in your browser
- **Privacy-First**: All processing happens locally in your browser

## Game Mechanics

- **Scoring**: Volley the ball through the goal posts to score points
- **Goal Movement**: After each goal, the target moves to the opposite side
- **Ball Reset**: Perform a squat motion to reset the ball position
- **Visual Feedback**: See your knee and foot positions as colored markers
- **Score Tracking**: Keep track of your volley goals

## Technology Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **3D Graphics**: Three.js for rendering
- **Physics**: Rapier3D for realistic ball physics
- **Motion Tracking**: MediaPipe Pose for body detection
- **Styling**: Custom CSS with modern UI elements

## Privacy

The game processes all webcam data locally in your browser. No video or images are sent to any server - your privacy is protected.

## Development

To run locally:
1. Clone the repository
2. Serve the files using a local server (e.g., `python -m http.server`)
3. Open in your browser at `localhost:8000`

## Credits & Acknowledgments

This project is based on the excellent **[3D Keep-Ups](https://github.com/collidingScopes/keep-ups)** game by [Alan 👾](https://github.com/collidingScopes). 

### Original Repository
- **Original Game**: [collidingScopes/keep-ups](https://github.com/collidingScopes/keep-ups)
- **Original Creator**: Alan 👾
- **Original Concept**: Football keep-ups with webcam motion tracking

### Modifications Made
- **Game Type**: Converted from keep-ups to volleyball shooting
- **Goal System**: Added dynamic goal posts that move after scoring
- **Scoring Mechanics**: Implemented goal-based scoring instead of keep-up counting
- **Visual Elements**: Added goal posts and modified UI elements
- **Instructions**: Updated game instructions for volleyball shooting
- **Styling**: Enhanced visual design with new color schemes and effects

Thank you to Alan 👾 for creating the original foundation that made this volleyball shooting game possible!

## License

This project is based on the original keep-ups game. Please refer to the original repository for licensing information.
