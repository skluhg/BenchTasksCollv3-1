# Final Pool of Implemented Tasks

This directory contains the tasks that are implemented (their implementation satisfies the requirements from tasks/examples), tracked on our Notion page Task Tracker.

Relative path in the project: tasks/finalpool.

Each subdirectory is one task with the standard structure:
docs/task.md, docs/agent_system_prompt.md, docs/user_system_prompt.md (optional), evaluation/main.py, preprocess/main.py (optional), initial_workspace/, groundtruth_workspace/.

Note: 5 directories here (currency-converter, insights-engine, audit-logger, resource-monitor, client-portal) are still marked **implementing** on the Task Tracker, because their `docs/agent_system_prompt.md` / `docs/task.md` contain Chinese text and therefore violate the "must be non-empty and all English (no Chinese)" requirement from `tasks/examples`. They are kept in this pool for reference until the respective developers fix the docs.
