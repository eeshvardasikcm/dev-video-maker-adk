### Video Planner Roadmap (Core Sequence)

**I. Goal:**

* Develop a basic "planner" to define the sequential order and key narrative for a video composed of screenshots.

**II. Key Features:**

* Simple interface for inputting a sequence of screenshots.
* Ability to add a brief description/narrative for each screenshot.
* Clear indication of the planned order.

**III. Development Stages (Hackathon Focus) & Incremental Documentation:**

* **Phase 1: Basic UI for Ordering Screenshots.**
    * **Development:** Implement a user interface that allows for adding and reordering screenshots.
    * **Documentation (Make It Happen):**
        * **Short Notes Alongside Code:** Comment the logic behind the UI elements and the data structure used to store the order of screenshots.
        * **Quick Markdown Snippets:** Create a brief `.md` file (e.g., `phase1_ui.md`) outlining the chosen UI framework/library and the rationale for its selection.
        * **Focus on the "Why":** Briefly note why a particular ordering mechanism (e.g., drag-and-drop, numbered list) was chosen over alternatives.

* **Phase 2: Add Narrative Input for Each Screenshot.**
    * **Development:** Implement UI elements for adding a text description or narrative to each uploaded screenshot.
    * **Documentation (Make It Happen):**
        * **Short Notes Alongside Code:** Comment the code related to the narrative input fields and how this data is associated with each screenshot.
        * **Quick Markdown Snippets:** Update the `.md` file or create a new one (e.g., `phase2_narrative.md`) describing how the narrative data is structured and stored.
        * **Focus on the "Why":** Briefly explain the design choice for the narrative input method (e.g., simple text field vs. rich text editor).

* **Phase 3: Display the Planned Sequence and Narrative.**
    * **Development:** Implement a view that clearly displays the ordered sequence of screenshots along with their corresponding narratives.
    * **Documentation (Make It Happen):**
        * **Short Notes Alongside Code:** Comment the code responsible for rendering the ordered list and displaying the narrative for each item.
        * **Quick Markdown Snippets:** Update the `.md` files to include details on how the planned sequence is visually presented to the user. Consider a simple diagram in the `.md` if the display logic is complex.
        * **Focus on the "Why":** Briefly explain the design choices for the visual layout of the planned sequence and narrative.

* **Phase 4 (Stretch): Simple Export of the Plan.**
    * **Development:** Implement a basic mechanism to export the planned sequence and narratives (e.g., to a text file or JSON).
    * **Documentation (Make It Happen):**
        * **Short Notes Alongside Code:** Comment the code related to the export functionality and the chosen output format.
        * **Quick Markdown Snippets:** Create a brief `.md` file (e.g., `phase4_export.md`) describing the chosen export format and the rationale behind it.
        * **Focus on the "Why":** Briefly explain why a particular export format was selected for this initial version.

**IV. Why This Matters:**

* Provides a foundational tool for planning screenshot-based videos within the Hackathon timeframe.
* Establishes the core logic for future video creation features.
* **Benefits from Incremental Documentation:** By documenting design decisions at each stage, the codebase will be more understandable for future iterations and easier to maintain, even within the rapid Hackathon development.
