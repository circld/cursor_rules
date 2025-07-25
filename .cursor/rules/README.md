# Cursor Rules Directory

This directory hosts `.mdc` files that provide persistent, reusable context for Cursor's AI.

## Organization Structure
- `core-rules/` - Rules about Cursor behavior and core coding principles
- `language-rules/` - Language-specific coding standards
- `framework-rules/` - Framework-specific conventions
- `project-rules/` - Project-specific patterns and standards
- `workflow-rules/` - Development workflows

## File Naming Convention
- `*-always.mdc`   - Always applied
- `*-auto.mdc`     - Auto-attached based on globs
- `*-agent.mdc`    - AI decides when to apply
- `*-manual.mdc`   - Only when explicitly referenced 