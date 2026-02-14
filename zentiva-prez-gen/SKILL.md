---
name: zentiva-prez-gen
description: Generates professional PowerPoint presentations branded for Zentiva. Use when you need to create slide decks, project summaries, or reports that must adhere to Zentiva corporate branding (colors, fonts, layouts).
---

# Zentiva Presentation Generator

This skill enables you to create branded Zentiva presentations programmatically.

## Workflows

### 1. Generating a Branded Presentation

When the user asks for a branded Zentiva presentation:

1.  **Analyze Content**: Identify the presentation title and the key points for each slide.
2.  **Reference Branding**: Read `references/branding.md` to ensure all elements (colors, layouts) are understood.
3.  **Prepare Script**: Use the `scripts/generate_pptx.py` script.
4.  **Execute**: Run the script using Python. You may need to install `python-pptx` if it's not available in the environment.

**Example Command:**
```bash
python scripts/generate_pptx.py "2026 Strategic Plan" "strategic_plan.pptx" \
"Executive Summary" "Key growth drivers for Q1 and Q2." \
"Financial Outlook" "Projected 15% increase in revenue."
```

### 2. Manual Customization
If you need to perform more complex modifications than the script allows, use `python-pptx` directly in a custom script, referencing the `assets/Brand_v001.pptx` template to preserve master slides and branding.

## Resources

- **Template**: `assets/Brand_v001.pptx` (Use this as the base for all presentations).
- **Brand Guide**: `references/branding.md` (Contains HEX codes and layout rules).
- **Automation**: `scripts/generate_pptx.py` (A helper script for basic deck generation).

## Design Principles

- **Primary Colors**: Use Zentiva Blue (#004B79) and Teal (#00A98F).
- **Logo**: Ensure the logo in the template remains visible in the bottom-left corner.
- **Simplicity**: Zentiva branding favors clean, minimalist layouts with plenty of white space.
