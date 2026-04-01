# My Global Harness

A folder to keep and copy your favorite components across agent collaborations.

## Usage Steps
Set Up Your Harness
1. Clone the repo to make your MyGlobalHarness folder.
2. Populate the folder with the components you want to reuse (skills, context, guides, etc).
3. Add more components over time.

Deploy Your Harness
1. Copy your MyGlobalHarness folder into the project directory where you want to copy over your components. Make any edits in the copy.
2. Ask your agent to follow the instructions in the MyGlobalHarness folder. Here are the agent instructions:

```
Ask me where to look for files and install files.
Look at MyGlobalHarness/ and install to my local project based on the instructions you see.
For each file: if it doesn't exist, create it.
If it already exists, show me the diff and ask whether to overwrite.
```

3. Delete the MyGlobalHarness folder from your project.

## Structure
- `skills/` — each folder becomes a slash command (e.g., `/plan`, `/match-style`)
- `context/` — reference files you want to keep
- And more - anything you want to keep and reuse.
