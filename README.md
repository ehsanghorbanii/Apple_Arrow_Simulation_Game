# AppleArrowSimulation

AppleArrowSimulation is a JavaFX-based educational tool that demonstrates projectile motion by simulating an arrow's attempt to hit a moving apple. This application visualizes the concepts of gravity, initial velocity, and angles in a fun and interactive way.

## Features

- Interactive simulation of arrow physics.
- User input for initial arrow velocity and angle.
- Real-time control over the simulation (start, pause, resume, reset).
- Dynamic visualization of both arrow and apple trajectories.
- Auto-generated random horizontal velocity for the apple.
- Trial count with a maximum of 5 trials per session.

## Prerequisites

Before running the application, ensure you have the following installed:
- JDK 11 or above
- JavaFX SDK 11 or above
- Maven (if building with Maven)

## Installation

Clone the repository to your local machine:

```sh
git clone https://github.com/ehsanghorbanii/Apple_Arrow_Simulation_Game.git
```
Navigate to the project directory:

```sh
cd Apple_Arrow_Simulation_Game
```

## Running the Application

### With an IDE
Open the project in your favorite IDE (such as IntelliJ IDEA, Eclipse, or NetBeans), configure your JavaFX library path, and run the `FinalSimulation` class.

### With Maven
If you have Maven installed, you can run the application using the following command:

```bash
mvn clean javafx:run
```

## With Command Line
To run the application directly from the command line, use the following commands:

```sh
cd path/to/your/project
javac --module-path /path/to/javafx-sdk-11/lib --add-modules javafx.controls,javafx.fxml -d out $(find src -name "*.java")
java --module-path /path/to/javafx-sdk-11/lib --add-modules javafx.controls,javafx.fxml -cp out com.example.applearrowsimulation.FinalSimulation
```
Replace `/path/to/javafx-sdk-11/lib` with the actual path to your JavaFX SDK library.
## Usage

- Enter the initial arrow velocity and angle in the designated text fields.
- Press 'Start' to initiate the simulation.
- Use 'Pause' and 'Resume' to control the simulation as it runs.
- 'Reset' will clear the current state and prepare for a new trial.
- The application automatically ends after 5 trials, or you can exit at any time using the 'Exit' button.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

## Contact

Ehsan Ghorbani - [ehsanoddinghorbani@gmail.com](mailto:ehsanoddinghorbani@gmail.com)

Project Link: [Apple Arrow Simulation](https://github.com/ehsanghorbanii/Apple_Arrow_Simulation_Game.git)

## Additional Documentation and Screenshots

- Link to Documentation: [Manual](Manual.pdf)





