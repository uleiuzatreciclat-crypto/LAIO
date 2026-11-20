
# LAIO — Technical Architecture

## 1. Overview

LAIO is a modular desktop productivity suite built around a shared application shell.

The initial development target is Linux.

## 2. Technology Stack

| Layer | Technology |
|---|---|
| Desktop framework | Tauri 2 |
| Backend | Rust |
| Frontend | React |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Database | SQLite |
| Document editor | Tiptap |
| Audio processing | GStreamer |
| Image processing | libvips |

## 3. Application Modules

### LAIO Write
Document creation, editing and exporting.

### LAIO Audio
Audio recording, editing and processing.

### LAIO Image
Image editing, drawing and exporting.

### LAIO Vault
Encrypted password storage and secure notes.

## 4. Shared Core

The shared core provides:
- Application settings
- File management
- Database access
- Module communication
- User preferences
- Theme management

## 5. Security

- Local-first data storage.
- No custom cryptographic algorithms.
- Secure credential storage.
- Explicit permissions for sensitive operations.
- Vault isolation from unrelated modules.

## 6. Development Philosophy

- Modular architecture.
- Open-source development.
- Privacy by default.
- Minimal resource consumption.
- Community-driven contributions.

## 7. Platform Strategy

Linux is the initial target. Cross-platform compatibility is a long-term objective.
