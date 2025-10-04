Lord Cedric D. Ramos, Full Stack Web Dev with AI Agentic SPUP

✅ Node.js installed (screenshot of 'node --version' command)
<img width="1061" height="56" alt="image" src="https://github.com/user-attachments/assets/fc815a98-0b27-4a3e-a14f-dbbf514ae9f6" />

✅ Git installed (screenshot of 'git --version' command)

<img width="374" height="73" alt="image" src="https://github.com/user-attachments/assets/5bf85fe1-fd48-44aa-974e-996c8faa86e1" />

✅ VS Code Insider running with GitHub Copilot enabled (screenshot)
<img width="2557" height="1599" alt="image" src="https://github.com/user-attachments/assets/866b4da1-17f9-4eab-bc22-6e85f13ba074" />

✅ Claude Desktop open with all 4 MCP servers connected (screenshot)
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/c43d1f26-7990-485a-9fee-758b744a03a6" />
<img width="336" height="455" alt="image" src="https://github.com/user-attachments/assets/0178c117-b194-46f5-93ac-a16d0735af06" />

MCP Server Purpose & Functionality

Rolldice
Purpose: A tiny service that returns a random dice roll (1–6) for testing orchestration and deterministic interaction patterns.
Functionality: Accepts an MCP request (usually over TCP or HTTP depending on implementation) and returns a structured response, e.g. { "roll": 4 }. Useful for exercising request/response flows and validating agent composition.

Bootcamp AI Agent
Purpose: A local agent service used in the workshop to demo agent behaviors, planning, and multi-step task execution.
Functionality: Exposes endpoints or MCP actions for tasks like “explain this code”, “generate tests”, or “run a small simulation.” Often returns structured results and logs so you can inspect internal reasoning or decisions.

Calendar Booking
Purpose: Simulated calendar service for scheduling, conflict-checking, and returning available time slots.
Functionality: Accepts booking requests and returns structured availability or booking confirmations (date/time/ID). Useful for testing stateful interactions and idempotency (e.g., retries shouldn’t double-book).

GitHub (MCP)
Purpose: An MCP connector to GitHub enabling agents to create issues, PRs or commits programmatically and to read repo state.
Functionality: Exposes actions like createIssue, listCommits, or createCommit. Requires authentication (PAT or OAuth) and returns structured responses including resource IDs and HTTP status codes.

During setup and verification I encountered no problems: all required tools were installed and all four MCP servers connected successfully.
