# LinkedIn UI Redesign: Connect Button Visibility

## Problem Summary
When trying to connect with someone on LinkedIn (especially mobile or third-degree connections), the **"Connect"** button is often hidden behind a **"More"** dropdown. This adds friction to a critical user journey—connecting with people after an event or meeting. 

The design slows users down and causes some to miss the opportunity to personalize their invite with a note, which can reduce the likelihood of connection acceptance.

## Critical User Journey
**Goal:** A user meets someone at an event and wants to connect on LinkedIn while the interaction is still fresh.  
**Steps:**
1. Search for the person.
2. Open their profile.
3. Attempt to send a connection request.

Currently, step 3 is unintuitive because the **Connect** option is hidden in a dropdown, and the **Add Note** option appears in a secondary modal.

## Proposed UI Improvements

### 1. Make "Connect" Visible by Default
Move the **Connect** button out of the dropdown and place it next to **Follow** and **Message**—making it immediately accessible.  
**Why:** Reduces clicks, improves accessibility of a core function, and aligns with user expectations for fast interactions.

### 2. Display "Add Note" Inline
Instead of opening a separate modal, show the "Add Note" field directly below the Connect button once clicked.  
**Why:** This encourages users to personalize their invite, increasing the success rate of connections.

## Files Included
- `screenshots/`:  
  - `hidden-connect.png`: Profile view where Connect is hidden in the dropdown.  
  - `connect-visible-in-dropdown.png`: Shows the Connect option inside the More dropdown.

- `solution/`:  
  - `paper-prototype-1.png`: Shows Connect moved out of the dropdown.  
  - `paper-prototype-2.png`: Shows Add Note directly below Connect button.

---

```bash
📎 Link to this GitHub repo:
https://github.com/paulinaNunez802/linkedin-ui-redesign.git
