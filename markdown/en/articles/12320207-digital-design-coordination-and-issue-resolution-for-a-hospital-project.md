# Digital Design Coordination and Issue Resolution for a Hospital Project

> Industry: Healthcare Construction / BIM (Building Information Modeling) Persona: David, a BIM Coordinator for a large general contractor.

**Scenario:** David is managing the digital construction model for a new hospital wing. This is a highly complex project involving dozens of specialized teams. The architectural, structural, and MEP (Mechanical, Electrical, Plumbing) models are constantly being updated by different consulting firms. David's primary responsibility is to federate (combine) these models in Catenda Hub to identify and resolve clashes _before_ they become expensive problems on the construction site.

During his weekly coordination check, he needs to investigate a potential critical issue flagged by the site manager: the support structure for a large MRI machine on the second floor may not align with the latest architectural and electrical plans.

**Solution using Catenda Hub:** David uses a precise workflow within Catenda Hub to manage this complex coordination task efficiently.

### **1. Centralizing the Data on the 'Models' Page:**

First, David navigates to the **Models page**. Here, he can see all the latest IFC models uploaded by the various teams, each with its revision number and status. He selects the relevant models for the area of concern:

- ARCH-Hospital-Wing-rev04.ifc
- STRUCT-MRI-Support-rev02.ifc
- MEP-Elec-Room204-rev05.ifc

He opens all three in the federated **3D Viewer**. The platform combines them into a single, navigable digital twin of that section of the hospital.

### **2. Identifying the Clash and Creating a 'Bookmark':**

Navigating through the 3D model, David immediately spots the problem. The structural steel supports for the MRI machine are penetrating a wall where the architects have now placed a main electrical switchgear room. Furthermore, the floor penetration for the machine's cooling pipes conflicts with a newly routed cable tray. To communicate this complex, multi-part issue clearly, a simple screenshot won't do. Instead, David uses the **Bookmarks** feature:

- He isolates only the clashing elements: the steel supports, the specific wall, the switchgear, and the cable tray.
- He uses a section cut to create a clear, unobstructed view of the collision point.
- He saves this precise state—including the camera angle, object visibility, and section cut—as a bookmark titled "**Clash: MRI Support vs. Elec Room 204**".

### **3. Creating and Assigning an Actionable Issue:**

With the bookmark created, David creates an **Issue** (or "Topic" in Catenda Hub). In the issue description, he writes: "@Architects, @Structural, @MEP - We have a critical clash between the MRI support structure and the revised electrical room layout. The attached bookmark shows the exact location and elements involved. Structural needs to confirm if the supports can be moved, and MEP needs to verify a new route for the cable tray. Please provide a solution by EOD Friday." He links the issue directly to the bookmark he just created.

### **4. Driving Collaborative Resolution:**

The lead architect, structural engineer, and MEP coordinator receive an instant notification. When they click the link in the issue, Catenda Hub opens the 3D model and takes them to the **exact view David saved in the bookmark**. There is no ambiguity or time wasted trying to find the problem. They use the issue's comment section to discuss solutions. The architect confirms the electrical room's position is fixed. The structural engineer runs a quick analysis and proposes a revised support design, attaching a sketch. The MEP coordinator confirms they can re-route the cable tray.

### **Outcome and Benefits:**

By leveraging the Models and Bookmarks pages, David transformed a potentially chaotic and costly problem into a structured, traceable, and quickly resolved issue.

- **Absolute Clarity:** The bookmark provided a "single source of truth" for the problem, eliminating any misinterpretation that could arise from emails or phone calls.
- **Significant Time Savings:** The project stakeholders resolved the issue in a few hours of digital collaboration, saving days or even weeks compared to traditional methods of sending files back and forth.
- **Cost Avoidance:** Identifying this clash digitally prevented the massive costs of on-site demolition, rework, and project delays that would have occurred if the steel had been erected in the wrong place.

### **Improved Accountability:**

The entire discovery, communication, and resolution process is documented in a single issue, creating a clear audit trail for the project record.
