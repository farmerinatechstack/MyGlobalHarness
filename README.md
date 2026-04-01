# My Global Harness

A folder to keep and copy your favorite components across agent collaborations.

## Usage Steps
Set Up Your Harness
1. Clone the repo.
2. Populate your resulting MyGlobalHarness folder with the components you want to reuse.
3. Add more components over time.

Deploy Your Harness
1. Copy your MyGlobalHarness folder into the project directory where you want to copy over your components.
2. Ask your agent to follow the instructions in the MyGlobalHarness folder that you copied into your project directory. Here are the agent instructions:

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
- And more...

## Make Your Own
- Fork the repo.
- Configure your global harness.
- Copy and paste your global harness folder into a project you're working on.
- Ask your agent to follow the instructions.
- Delete the global harness folder from your project.
