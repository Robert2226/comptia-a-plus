# [Week X] Lab Recap

## Objective
[What this week's lab covers.]

## Tools Used
- Terminal
- VS Code
- macOS

## Commands Used
```bash
# command examples here

🧠 Explanation:
- You’ll replace `[Week X]`, `[What this week’s lab covers]`, and other placeholders each time you create a new week.
- The code block is wrapped with triple backticks (` ```bash ` and ` ``` `) so you don’t forget!

Save and exit:
- `Ctrl + O`, `Enter`
- `Ctrl + X`

✅ Now your Markdown template is ready.

---

## ✅ Step 3.3: Create the Scaffolding Script

This is the **automated script** that copies your template and sets up folders for new labs.

### Run:

```bash
nano new-week.sh
#!/bin/bash

# Check if user passed a week name
if [ -z "$1" ]; then
  echo "❌ Please provide a week name (e.g., Week4)"
  exit 1
fi

# Set variable for the week
WEEK_NAME=$1

# Create folders
mkdir -p $WEEK_NAME/Screenshots

# Copy template Markdown to the new week folder and rename it
cp Templates/Lab_Template.md $WEEK_NAME/${WEEK_NAME}_Recap.md

# Confirm success
echo "✅ Created scaffold for $WEEK_NAME:"
echo "- $WEEK_NAME/${WEEK_NAME}_Recap.md"
echo "- $WEEK_NAME/Screenshots/"

