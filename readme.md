# Cursor System Prompt Repository

This repository contains system prompts used by Cursor, an AI-powered code editor. The system prompts define how the AI assistant in Cursor behaves and interacts with users when writing and editing code.

## Repository Contents

The repository currently contains three main system prompt files:

- **agent.md**: Defines the behavior of the AI agent that autonomously solves coding tasks and can use various tools to read files, search through code, make edits, run terminal commands, and more.

- **ask.md**: Contains the system prompt for the question-answering mode of Cursor's AI assistant, focusing on responding to user queries about code without necessarily making edits.

- **mannus.md**: Provides a more basic system prompt for the AI assistant with limited tool access, mainly focused on communication and making code change suggestions without direct file manipulation.

## Purpose

These system prompts are the foundation of how Cursor's AI assistant understands its role and capabilities when helping users with coding tasks. They define:

- How the AI should communicate with users
- What tools the AI can access and how to use them
- How to search and read files in a codebase
- Guidelines for making code changes
- Rules for summarizing conversations

The system prompts help create a consistent, helpful, and effective AI coding assistant experience within the Cursor editor.

## Version

This repository contains system prompts for Cursor version 0.49.6.
