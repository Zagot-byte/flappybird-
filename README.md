# Installation

Follow these steps to download and run FlappyBird.

Prerequisites
- Java Runtime Environment (JRE) 8 or later installed.
- Verify by running:
  ```
  java -version
  ```
  If Java is not installed, download it from https://www.java.com/ or install your platform's OpenJDK package.

Download the project
1. Clone the repository:
   ```
   git clone https://github.com/Zagot-byte/flappybird-.git
   ```
2. Enter the project directory:
   ```
   cd flappybird-
   ```

Run the game
- From the project directory, run:
  ```
  java -jar FlappyBird.jar
  ```
- On Unix-like systems (Linux, macOS), if you get a permission error first make the file executable and try again:
  ```
  chmod +x FlappyBird.jar
  java -jar FlappyBird.jar
  ```

Troubleshooting
- "java: command not found" — Java is not installed or not on your PATH. Install Java and re-run `java -version` to confirm.
- "Error: Unable to access jarfile FlappyBird.jar" — ensure you are in the directory that contains `FlappyBird.jar` (use `ls` / `dir` to check) or run with an explicit path:
  ```
  java -jar ./FlappyBird.jar
  ```
- "No main manifest attribute" or "Could not find or load main class" — the JAR may be corrupted or incomplete. Try re-downloading or re-cloning the repository.
- If the game window does not appear but Java runs, check for additional console output for clues (missing assets, exceptions).

Notes
- These steps assume the repository already includes `FlappyBird.jar`. If you don't find it in the project root after cloning, check the repository releases or the repository contents for a build step or alternative instructions.
