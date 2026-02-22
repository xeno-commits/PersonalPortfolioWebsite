Project: Personal Portfolio Website

Stage 1 – Functional Upgrade & Contact Integration
Initial State
  Static HTML/CSS portfolio layout
  Non-functional buttons (div elements used for UI only)
  Single email input field (no form handling)
  No external links wired up


Goals
  Convert UI elements into functional navigation links
  Implement secure contact form
  Preserve original visual design
  Maintain responsiveness
  Use Git feature branch workflow


Implementation Details
Navigation Refactor
  Replaced <div class="btn"> elements with semantic <a> tags
  Added target="_blank" and rel="noopener noreferrer" for external links
  Preserved styling by updating .btn CSS rules
  Resolved link color inheritance issue by explicitly setting color: black

Contact Form Upgrade
  Replaced single email input with structured <form>
  Added:
    Name field (required)
    Email field (required)
    Message textarea
Integrated Formspree endpoint for secure email handling
Ensured responsive scaling across breakpoints
Tested required field validation and delivery confirmation


Git Workflow
  Created feature branch: feature/contact-and-links
  Committed functional upgrades
  Merged into main
  Resolved remote push rejection by pulling with rebase
  Successfully updated remote main branch


Problems Encountered
  Anchor tag styling override caused text color change
    Resolved by explicitly setting .btn { color: black; }
  Push rejected due to remote being ahead
    Resolved using git pull --rebase origin main
Branch mismatch initially caused confusion about missing changes


Lessons Learned
  Importance of semantic HTML when converting UI elements
  Understanding how CSS inheritance affects anchor elements
  Proper Git merge and remote synchronization workflow
  Importance of pre-commit testing before merging to main
