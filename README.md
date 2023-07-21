# Caffeinate - Keep Your System Awake

## Idea

Caffeinate is a program designed to prevent your system from entering sleep mode or screen dimming due to inactivity. It achieves this by programmatically performing actions, such as moving the cursor or pressing keys at specified intervals, to simulate user activity and keep the system awake.

## Tech Stack / Tools Used

- [Python](https://www.python.org/): The core programming language used for implementing the 'Caffeinate' program.
- [Bash](https://www.gnu.org/software/bash/): For bash script implementation (if applicable).

## Installation

### Prerequisites

- [Python](https://www.python.org/downloads/): Make sure you have Python installed on your system.

### Clone the Repository

```bash
git clone https://github.com/your-username/caffeinate.git
cd caffeinate
```
### Running Caffeinate

```python
# For Python implementation
caffeinate.py
```

```bash
# For bash script implementation
./caffeinate.sh
```
## Future Scope

1. **Scheduling and Profiles:** Implement the ability to set schedules or profiles for 'Caffeinate' to allow users more control over wake-up actions at specific times or during particular applications.

2. **Power Management Optimization:** Continuously optimize 'Caffeinate' to achieve a balance between keeping the system awake and minimizing resource consumption.

3. **Integration with System Events:** Enable automatic activation/deactivation of 'Caffeinate' based on system events or triggers.

4. **Remote Activation:** Implement the ability to activate 'Caffeinate' remotely through network commands or a mobile app.

5. **Battery Management:** Add intelligent battery management features to pause or adjust 'Caffeinate' actions when running on battery power, helping conserve energy.

6. **Advanced Configuration:** Allow power users to fine-tune 'Caffeinate' settings through configuration files for extensive customization.

7. **Error Handling and Reporting:** Enhance the program's robustness by implementing proper error handling and reporting mechanisms.

8. **Notification System:** Add a notification feature to inform users when 'Caffeinate' is activated or deactivated, providing transparency and control over the program's behavior.

9. **Cross-Platform Support:** While the initial implementation may be focused on one operating system (e.g., macOS, Linux, or Windows), expanding support to multiple platforms would increase the program's reach and user base.

## Contribution

Contributions are welcome! If you have any ideas, bug fixes, or feature suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](link-to-your-license-file).
