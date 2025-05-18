### Video Planner Roadmap (Core Sequence - Decision-Centric)

**I. Goal:**

* Develop a basic "planner" focused on indexing sequential decisions and their impact on the implementation process for a video composed of screenshots.

**II. Key Features:**

* Mechanism to input a sequence of screenshots (basic placeholder or file reference).
* Primary focus: Ability to record a decision/rationale associated with *each* screenshot in the sequence.
* Clear indication of the planned order of screenshots.
* Emphasis on documenting the *why* behind the sequential decisions.

**III. Development Stages (Hackathon Focus) & Incremental Documentation:**

* **Phase 1: Basic Sequential Input and Decision Recording.**
    * **Development:** Implement a simple way to define a sequence of screenshots (e.g., by name or placeholder). For *each* screenshot, provide a direct input field for recording the decision or rationale that led to its inclusion and placement in the sequence.
    * **Documentation (Make It Happen):**
        * **Short Notes Alongside Code:** Thoroughly comment the data structures used to store the sequence of screenshots and their associated decisions. Explain how the link between the screenshot and the decision is maintained.
        * **Quick Markdown Snippets:** Create a `.md` file (e.g., `phase1_decision_model.md`) detailing the schema or data model used to represent the screenshot sequence and the decision for each step.
        * **Focus on the "Why":** Explicitly document the reasoning behind the chosen data model for linking decisions to the sequence.

* **Phase 2: Displaying the Decision-Indexed Sequence.**
    * **Development:** Implement a view that clearly displays the ordered sequence of screenshots, with the corresponding decision/rationale visible for each step.
    * **Documentation (Make It Happen):**
        * **Short Notes Alongside Code:** Comment the code responsible for retrieving and displaying the ordered sequence and the associated decisions.
        * **Quick Markdown Snippets:** Update the `.md` file or create a new one (e.g., `phase2_decision_display.md`) describing how the decisions are presented in relation to the screenshot sequence.
        * **Focus on the "Why":** Document the design choices for how the decisions are visually presented to ensure clarity and understanding of the sequential logic.

* **Phase 3: Simple Export of Decisions and Sequence.**
    * **Development:** Implement a basic mechanism to export the ordered sequence of screenshots along with the recorded decisions (e.g., to a structured text file or JSON).
    * **Documentation (Make It Happen):**
        * **Short Notes Alongside Code:** Comment the export functionality, clearly indicating how the screenshot sequence and the associated decisions are structured in the output format.
        * **Quick Markdown Snippets:** Create a `.md` file (e.g., `phase3_decision_export.md`) detailing the chosen export format and the rationale for including both the sequence and the decisions.
        * **Focus on the "Why":** Explain why this specific export format was chosen for capturing both the sequence and the underlying decisions.

* **Phase 4 (Stretch): Basic UI for Ordering (If Time Permits).**
    * **Development:** If time allows, implement a basic UI to visually reorder the screenshots, ensuring that the associated decisions move with their respective screenshots.
    * **Documentation (Make It Happen):** Document the UI implementation and how it interacts with the underlying data structure that links screenshots and decisions.

**IV. Why This Matters:**

* Prioritizes the critical aspect of indexing sequential decisions and their impact on the implementation process, which is key for understanding the video's creation logic.
* Establishes a strong foundation for future UI enhancements and more complex video creation features, grounded in well-documented sequential reasoning.
* The focus on documenting the "why" behind each step directly aligns with the need to capture the implementation process.
