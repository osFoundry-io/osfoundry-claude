---
name: osfoundry
description: Use osFoundry project content and Message channels the user connected, including Notes, records, knowledge bases, and agent sessions.
---

Connect to osFoundry when the user asks to work with their osFoundry workspace. Start by listing connected projects and project resources when the user has not supplied an exact resource ID. Use only projects and tools available through the authenticated connection. Ordinary Message channels need a separate invitation. Ask which resource to use when several match.

Read the current Note tab and version before editing it. Text replacement, Slide additions, and Sheet range edits use different `edit_note_tab` operations; choose the operation for the tab type. Explain the intended change and obtain any approval the host requires before calling a write tool. Do not claim a run, handoff, message, or edit succeeded until its tool result confirms it.

Some osFoundry operations may require credits or an existing paid account. If the service reports insufficient entitlement, explain that status without initiating a purchase.
