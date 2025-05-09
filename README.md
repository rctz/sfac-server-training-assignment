# 🤖 SFAC Training – Assignments

| Assignment | Topic            | Path                                                      | Live Demo / Test |
| ---------- | ---------------- | --------------------------------------------------------- | ---------------- |
| 1          | Robot Control UI | [`assignment1-robot-ui/`](./assignment1-robot-control-ui) |                  |

## 🚀 Getting Started with the Assignment Repository

### 1. Fork this repository to your own GitHub account

Click the **"Fork"** button at the top right of this page to create a personal copy of this repository.  
You will get a URL like:

### 2. Clone the repository to your local machine

```bash
git clone https://github.com/rctz/sfac-server-training-assignment.git
```

```bash
cd sfac-server-training-assignment
```

### 3. Create a New Branch for Your Assignment

Before you start working on your assignment, **always create a new branch** from the `develop` branch. This keeps your work isolated, organized, and easier to review.

#### 🧭 Step-by-Step Instructions

```bash
git checkout develop # Switch to the base branch
```

```bash
git pull origin develop # Make sure you have the latest changes
```

```bash
git checkout -b feature/<your-feature-name> # Create a new feature branch
```

✅ Examples

```bash
git checkout -b feature/joystick-ui
git checkout -b feature/emergency-stop-button
git checkout -b feature/realtime-map-display
git checkout -b doc/state-control
git checkout -b test/binning-weight-calculation
```

| Type     | Format                        | Examples                               |
| -------- | ----------------------------- | -------------------------------------- |
| Feature  | `feature/<short-description>` | `feature/map-sync`, `feature/ui-theme` |
| Bug Fix  | `bug/<issue-description>`     | `bug/fix-map-lag`, `bug/ui-glitch`     |
| Document | `doc/<urgent-fix>`            | `doc/rollback-api-error`               |
| Test     | `test/<experiment>`           | `test/socket-latency-check`            |

### 4. Work on your assignment inside the designated folder

Each assignment is located in a separate folder, for example:

- `assignment1-robot-ui/`

- `assignment2-ros-node/`

- `assignment3-microcontroller/`

Read the README.md file in each folder to understand the assignment’s goals and requirements.

### 5. Commit your work using the Conventional Commits format

All commits should follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standard to ensure consistency, readability, and traceability.

#### ✏️ Format:

**Types** commonly used:

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation-only changes
- `style`: Code style changes (formatting, no logic changes)
- `refactor`: Code restructuring that doesn't change behavior
- `test`: Adding or modifying tests
- `chore`: Maintenance tasks (e.g. config, build tools)

**Optional scope**: a specific module, file, or feature in parentheses.

#### ✅ Examples:

```bash
git commit -m "feat(ui): add joystick control for robot movement"
git commit -m "fix(map): fix real-time update not syncing with server"
git commit -m "docs(readme): update instructions for assignment 1"
git commit -m "style(map): fix indentation in MapViewer component"
git commit -m "refactor(joystick): move logic to custom hook"
```
