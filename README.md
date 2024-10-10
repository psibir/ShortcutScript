# ShortcutScript
Flowchart for iOS Shortcuts

Overview of Rules and Syntax

	1.	Title:
		Format: **Title**: [Your Shortcut Title]
		Purpose: Clearly states the name of the shortcut.
	2.	Description:
		Format: **Description**: [Brief explanation of the shortcut]
		Purpose: Provides a concise overview of what the shortcut does.
	3.	Inputs:
		Format: **Inputs**: [List of required inputs]
		Purpose: Identifies any inputs necessary for the shortcut to function.
	4.	Actions:
		Format:

**Actions**:
1. [Action 1]
2. [Action 2]
   - Input: [Input details for Action 2]


	•	Purpose: Details the sequence of steps the shortcut performs.

	5.	Outputs:
	•	Format: **Outputs**: [List of outputs or interactions with the user]
	•	Purpose: Describes what the shortcut produces or how it interacts with the user.

Example
```
**Title**: Read Current Weather

**Description**: This shortcut fetches the current weather for your location and reads it aloud.

**Inputs**:
- Current Location (automatically retrieved)

**Actions**:
1. Get Current Location
2. Get Weather Forecast
   - Input: Current Location
3. Speak Text
   - Input: Weather Forecast

**Outputs**:
- Spoken weather report
```

