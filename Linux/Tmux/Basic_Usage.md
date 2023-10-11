# TMux Quick Start Guide

TMux (Terminal Multiplexer) is a powerful tool that allows you to manage multiple terminal sessions within a single window. It's particularly useful for remote development, pair programming, and multitasking on the command line.

## Installation

Make sure TMux is installed on your system. You can install it using your package manager. For example, on Ubuntu, you can use:

```bash
sudo apt-get install tmux
```

## Getting Started
To start TMux, simply type tmux in your terminal and press Enter. You'll enter the TMux session, and a status line will appear at the bottom of the terminal.

## Basic Commands
###Creating a new session:
```bash
tmux new-session -s mysession
```

### Detaching from a session:
Press Ctrl-b followed by d to detach from the current session.

### Attaching to a session:
If detached, you can reattach to a session with:
```bash
tmux attach-session -t mysession
```

### Listing sessions:
```bash
tmux list-sessions
```

### Splitting the terminal horizontally:
Press Ctrl-b followed by %.

### Splitting the terminal vertically:
Press Ctrl-b followed by ".

### Navigating between panes:
Horizontal: Ctrl-b + Left/Right arrow
Vertical: Ctrl-b + Up/Down arrow

### Resizing panes:
Press Ctrl-b followed by Alt and then use arrow keys.

### Closing a pane:
Close the current pane with Ctrl-b + x.

## Advanced Usage
TMux has many more features and customization options. Refer to the official documentation (https://github.com/tmux/tmux/wiki) for more details.
