# My Global Harness

A portable folder of you carry across projects.

## Usage Steps
1. Copy MyGlobalHarness into your project directory.
2. Ask your agent to install:

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
Fork this repo and add your own skills and context.