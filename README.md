# Campaign Logic Validator
Static analysis tool that validates campaign SQL and segmentation logic to identify risks before deployment.

## Why
Marketing campaigns often rely on complex queries and filters. Small mistakes can cause:
- overly broad audiences
- performance issues
- unintended sends

This tool helps catch those risks before release.

## Features (MVP)
- Paste SQL or filter logic
- Validate against safety rules
- Highlight potential risks and warnings
- Runs fully client-side (no data stored)

## Tech Stack
- JavaScript
- Static analysis (rule-based)
- Client-side only
