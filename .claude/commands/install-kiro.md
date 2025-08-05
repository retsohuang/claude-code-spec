# Install Kiro Commands

Copy the kiro commands from this project to your global Claude Code commands directory.

```bash
# Get the user's Claude commands directory
CLAUDE_COMMANDS_DIR="$HOME/.claude/commands"

# Create the kiro directory if it doesn't exist
mkdir -p "$CLAUDE_COMMANDS_DIR/kiro"

# Copy all kiro command files
cp -r .claude/commands/kiro/* "$CLAUDE_COMMANDS_DIR/kiro/"

echo "Kiro commands installed to $CLAUDE_COMMANDS_DIR/kiro/"
echo "Available commands:"
echo "  /kiro:spec-init"
echo "  /kiro:spec-requirements" 
echo "  /kiro:spec-design"
echo "  /kiro:spec-tasks"
echo "  /kiro:spec-status"
echo "  /kiro:steering"
echo "  /kiro:steering-custom"
```