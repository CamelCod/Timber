# GitHub Copilot Prompts

This directory contains specialized prompts for use with GitHub Copilot Chat.

## Available Prompts

### Template Variable Extraction Agent
**File:** `template-variable-agent.md`

**Purpose:** Analyze a Shopify theme or template repository to identify all hard-coded values that should be configurable. This helps when reusing templates across multiple projects with different branding and settings.

**How to use:**
1. Open this repository in your editor with GitHub Copilot enabled
2. Open the GitHub Copilot Chat panel
3. Copy the entire content of `template-variable-agent.md`
4. Paste it into the Copilot Chat
5. Copilot will analyze the repository and provide:
   - A structured JSON schema of all configurable variables
   - Categories for organizing variables (branding, SEO, integrations, etc.)
   - Recommendations for improvements

**Best for:**
- Shopify themes and templates
- HTML/CSS/JS template projects
- Any codebase you want to reuse across multiple clients/projects

## Tips

- For large repositories, you can add context like "focus on the theme/ folder" or "analyze only the layout/ and templates/ directories"
- The prompts are designed to be conversational - you can ask follow-up questions after the initial analysis
- You can modify the prompts to fit your specific needs

## Contributing

Feel free to add more specialized prompts to this directory for different use cases.
