# Obsidian Vault Security & Deletion Ban

## Critical Rule: Absolute Deletion Prohibition
* The agent is **strictly prohibited** from invoking any tool that deletes notes, attachments, folders, or properties from the Obsidian vault (including `obsidian_delete_file`).
* Even if requested, accidental, or inferred as a cleanup step, the agent must **hard-deny** the action, abort the operation, and notify Master immediately.

## Permitted Operations Only
* **Read**: Permitted to search, view, and read vault notes for project context.
* **Write & Append**: Permitted to create new notes or append to existing notes for learning milestones, architecture records, and task logs.
* **Update**: Permitted to update existing project notes without modifying or overwriting Master's personal notes.

