### Developer Video Creator Roadmap (Manual Decision-Driven Indexing)

**I. Goal:**

* Develop a manual-entry UI tool for developers to index and document the sequential decisions and rationales made during the creation of a developer-focused video composed of screenshots, where the order of screenshots is determined by the manual capture process.

**II. Key Features:**

* Simple, manual UI for associating a captured screenshot (via file selection or similar) with a specific point in the video creation process.
* Primary focus: Intuitive UI elements for immediately recording the decision, context, and rationale associated with the *current* screenshot through manual text input.
* Clear, manual indexing of decisions linked to the sequence of captured screenshots as they are added.
* Emphasis on a natural, manual workflow for documenting the "why" at the point of creation.

**III. Development Stages (Hackathon Focus) & Incremental Documentation:**

* **Phase 1: Manual Screenshot Association and Decision Entry UI.**
    * **Development:** Implement a user-friendly UI where a developer can manually select or input a reference to a captured screenshot. Alongside this, provide a prominent text input area for immediately typing in the decision, context, and rationale for that specific visual.
    * **Documentation (Make It Happen - Manual UI):**
        * **Short Notes Alongside Code:** Comment the UI elements and the underlying data structures that store the screenshot association and the manually entered decision text. Explain how the link between the screenshot and the decision is established.
        * **Quick Markdown Snippets:** Create a `.md` file (e.g., `phase1_manual_ui.md`) detailing the design and implementation of the manual input UI for screenshots and decisions. Include mockups or descriptions of the UI elements.
        * **Focus on the "Why" (of the UI):** Document the rationale behind the chosen UI elements and workflow to ensure a natural and intuitive manual entry experience for developers.

* **Phase 2: Sequential Display of Screenshots and Decisions (Manual Order).**
    * **Development:** Implement a view that displays the sequence of manually added screenshots (perhaps as thumbnails or a list) along with the corresponding decision/rationale entered for each one, in the order they were manually added.
    * **Documentation (Make It Happen - Manual Display):**
        * **Short Notes Alongside Code:** Comment the code responsible for displaying the manually ordered list of screenshots and their associated decision text.
        * **Quick Markdown Snippets:** Update the `.md` file or create a new one (e.g., `phase2_manual_display.md`) describing how the manually entered sequence and decisions are presented in the UI.
        * **Focus on the "Why" (of the Display):** Document the design choices for the visual layout of the manual sequence and decisions to ensure clarity for the developer reviewing their process.

* **Phase 3: Simple Export of Manual Decision Log.**
    * **Development:** Implement a basic mechanism to export the manually entered log of screenshots (as file paths or names) and their corresponding decisions in the order they were manually recorded (e.g., to a plain text file or a structured format like CSV).
    * **Documentation (Make It Happen - Manual Export):**
        * **Short Notes Alongside Code:** Comment the export functionality, detailing how the manual entry order of screenshots and decisions is preserved in the output file.
        * **Quick Markdown Snippets:** Create a `.md` file (e.g., `phase3_manual_export.md`) describing the chosen export format and the rationale for its simplicity, aligning with the manual entry approach.
        * **Focus on the "Why" (of the Format):** Explain why this specific export format was chosen to best represent the manually captured sequence and reasoning.

* **Phase 4 (Stretch): Basic Manual Reordering (If Time Permits).**
    * **Development:** If time allows, explore a simple manual UI element (e.g., up/down buttons or a basic drag-and-drop within the displayed list) to allow the developer to manually adjust the order of screenshots and their associated decisions *after* their initial manual entry.
    * **Documentation (Make It Happen - Manual Reordering):** Document the UI implementation for manual reordering and how it updates the underlying data structure while keeping the decisions linked to their screenshots.

**IV. Why This Matters:**

* Directly aligns with a manual entry UI approach, focusing on a natural and intuitive experience for developers documenting their video creation process.
* Prioritizes the immediate capture of the "why" behind each visual element through manual input.
* Provides a straightforward, manually constructed log of the development flow and reasoning.
