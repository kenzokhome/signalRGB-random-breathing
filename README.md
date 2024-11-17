# Random Breathing Effect for SignalRGB

A custom lighting effect for **SignalRGB** that creates a visually appealing **breathing animation** with smooth brightness transitions. The color of the effect changes randomly when the brightness reaches 0, adding a dynamic and engaging look to your RGB devices.

## Features

- **Breathing Animation**: Smooth brightness fade in and out.
- **Random Color Transitions**: Color changes to a random hue when brightness reaches 0.
- **Adjustable Speed**: Control the speed of the breathing effect with the SignalRGB slider.
- **Hold Duration**: When the brightness reaches 1, it stays there for a brief moment (controlled by `holdDuration`).


## Installation

1. Download the `random_breathing_effect.html` file from this repository.
2. Place the file in the following directory:
`Users/<your-username>/Documents/WhirlwindFX/Effects`
Replace `<your-username>` with your actual username.

3. **Restart SignalRGB** to apply the new effect.

## Usage

1. Open **SignalRGB**.
2. Navigate to the **Effects** tab.
3. Find and select **Random Breathing Effect** from the list of installed effects.
4. Adjust:
- **Breathing Speed**: Controls how quickly the brightness changes. A higher value increases the speed.
- **Hold Duration**: The time (in frames) the brightness stays at 1 before continuing the cycle. A higher value increases the wait on full brightness

## How It Works

The effect utilizes the HTML `<canvas>` element to render the animation in real-time. Brightness is smoothly adjusted between 0 and 1 to create the breathing effect, and the color (hue) changes randomly whenever brightness reaches 0. The speed of the effect is controlled by a **SignalRGB** slider, allowing for customization.

## Customization

You can edit the effect's code to suit your preferences:

- **Adjust speed**: Modify the `speed` variable in the code for faster or slower transitions.
- **Change behavior**: Customize the brightness or color transition logic.

To get started with customization, clone or download the repository and modify the `random_breathing_effect.html` file.

## Compatibility

- Requires **SignalRGB** to be installed and running on your system.
- Supports any RGB device compatible with SignalRGB.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Let me know if you'd like further edits!
