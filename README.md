# Code Skillz

Instructions for AI-assisted coding collaboration with strict process control.

## Description

This skill defines collaboration guidelines when working with either Claude (and Claude Code) or ChatGPT( and Codex) on coding tasks.
The details can, and should, be modified to fit the programmer's coding style and workflow.

### Core Principles available:
- Controlled iteration with explicit confirmation at each step. Human directs, model provides focused responses without autonomous changes or unsolicited optimizations.
- Opinionated formatting and language and tool use. And follow existing conventions in the codebase.
- Simplicity by default, start with the simplest solution, scale complexity only when demonstrated necessary.
- One thing at a time, single changes, single topics, wait for feedback before proceeding.
- No assumptions, state assumptions explicitly, ask rather than guess about scope/scale/context. 
- Human runs tests and reports results — Never assume success, never run tests automatically, wait for reported outcomes.
- Resource consciousness, tokens and time are critical, avoid waste, no speculative approaches
- Preserve existing work, do not regenerate working code, do not modify comments or unrelated code

## Usage

1. Clone or download this repository
2. Modify the SKILL.md to fit your workflow.
3. Copy the skill folder to the appropriate location:
   - Claude Code: `~/.claude/skills/code-skillz/`
   - Codex: `~/.codex/skills/code-skillz/`
4. Invoke the skill:
   - Claude Code: `/code-skillz`
   - Codex: `use code-skillz` or `$code-skillz`”
   - Claude.ai (browser/app):

Go to Settings > Capabilities > Skills
Upload the skill as a ZIP file containing the folder
Toggle it on/off as needed