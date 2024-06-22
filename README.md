# Hacking Simulation Script

This project simulates a hacking process by displaying a series of messages with random delays between them. The messages are displayed one by one in a specified container on a web page, giving the appearance of a real-time hacking process.

## Files

- **index.html**: The main HTML file that contains the structure of the web page.
- **script.js**: The JavaScript file that contains the logic for the hacking simulation.
- **README.md**: This file, providing an overview of the project.

## Usage

### HTML Structure

Ensure you have an HTML structure with a container to display the messages. For example, create a `<div>` element with a class of "container" to hold the messages.

### JavaScript Logic

The JavaScript code handles the following:

1. **Random Delay Function**: This function generates a random delay between 1 and 4 seconds before resolving. This simulates the variable time it might take to perform each hacking step.

2. **Add Item Function**: This asynchronous function waits for the random delay before creating a new `<div>` element and adding it to the container. The new `<div>` contains the current message.

3. **Main Function**: This asynchronous function orchestrates the sequence of messages. It uses an interval to append dots to the current message to simulate ongoing processing. It iterates over the predefined list of messages, calling the `addItem` function for each. After displaying all messages, it clears the interval and adds a final success message to the container.

## How to Run

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Watch the simulation of the hacking process unfold in the container
4. Or accesss the link https://tanmayhh3009.github.io/HackerSimulator/.

## Notes

- The random delay function creates a random delay between 1 and 4 seconds to add realism to the simulation.
- The add item function waits for the random delay before adding the next message to the container, simulating processing time for each step.
- The main function handles the sequencing of messages and includes an interval for displaying dots at the end of each message to indicate ongoing processing.

Feel free to customize the messages and the container style to fit your needs.
