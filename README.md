# Skip's Chore Data

This repository stores actual chore instances created using the Chore Dispatcher system.

## Purpose

- Store real chores and their progress
- Track work items through the 9-stage workflow
- Maintain history of completed tasks

## Data Format

- **Active chores**: `chores.jsonl` - Chores currently in progress (not WORK_DONE)
- **Completed chores**: `completed_chores.jsonl` - Chores that have reached WORK_DONE status

Chores are stored in JSON Lines format for easy streaming and appending.
