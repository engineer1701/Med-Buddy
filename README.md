<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>
<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/d7510fb8-1880-4005-a3e2-d8462c1a94cc" />

# [Med-Buddy] 🎯

## Basic Details

### Team Name: [HackHer Duo]

### Team Members
- Member 1: [Anusree C V] - [Muthoot Institute of Technology and Science]
- Member 2: [Ashwini Shaji] - [Muthoot Institute of Technology and Science]

### Hosted Project Link
[https://engineer1701.github.io/Med-Buddy/demo.html]

### Project Description
[Med Buddy is a web application that helps users manage their daily medications. It offers reminders, tracks adherence, and supports voice input. The app features an appealing interface that includes notifications and progress tracking to ensure users take their medicine on time and correctly.]

### The Problem statement
[Many individuals, especially the elderly and those taking multiple medicines, tend to forget to take their medications on time or even take the wrong doses. This can result in health problems, missed appointments, or emergencies. Med Buddy solves this issue by offering reminders, tracking, and a user-friendly system to help individuals take their medications correctly and on time.]

### The Solution
[In the current fast-paced lifestyle, many individuals, especially the elderly, have a tendency to forget to take their medications on time, resulting in missed doses, health issues, or getting confused between different medications. The manual or memory-based process of tracking medications is not only unreliable but also stressful for patients and caregivers alike.

 Med Buddy is an intelligent and easy-to-use medicine reminder web application that can help address this issue by assisting users in the following ways:
 1. Track and record medicines along with their dosage and schedule easily.
 2. Reminders to take medicines on time.
 3. Assist senior users with a simplified and accessible interface.
 
 The aim of this project is to ensure that there are minimal missed doses, strict adherence to medication schedules, and peace of mind for users and caregivers.
]

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: [HTML , CSS , JavaScript]
- Frameworks used: [None (pure web app)]
- Libraries used: [Web Speech API]
- Tools used: [Git , GitHub , Browser , Code editor]

## Features

List the key features of your project:
-Smart Medicine Reminders  : [Never miss a dose with timely notifications.]
- Voice & Browser Alerts: [Get spoken reminders and pop-up notifications.]
- Daily Adherence Tracker : [ Track your medicine intake and stay on schedule.]
- Add Medicines via Voice: [Quickly add medicines using speech commands.]
- Elderly-Friendly Mode: [ Larger text and simplified interface for easy use.]
- Animated & Engaging UI : [ Interactive visuals like floating orbs and sparkles.]
-  SOS Emergency Button: [Instantly notify emergency contacts when needed.]
- Dashboard Overview : [View all medicines, reminders, and status in one place.]

## Implementation

### For Software:

#### Installation
```bash
[None]
```

#### Run
```bash
[Run commands - index.html]
```

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

![images/Screenshot 2026-02-21 090709.png](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![images/Screenshot 2026-02-21 090723.png](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![images/Screenshot 2026-02-21 090736.png](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

![c:\Users\Admin\OneDrive\Pictures\Screenshots\Screenshot 2026-02-21 091549.png](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*


#### Diagrams

**System Architecture:**

!![c:\Users\Admin\OneDrive\Pictures\Screenshots\Screenshot 2026-02-21 092306.png](<Screenshot 2026-02-21 092306.png>)[](docs/architecture.png)
*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

![c:\Users\Admin\OneDrive\Pictures\Screenshots\Screenshot 2026-02-21 092252.png](docs/workflow.png)
*Add caption explaining your workflow*

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

!![c:\Users\Admin\OneDrive\Pictures\Screenshots\Screenshot 2026-02-21 092155.png](<Screenshot 2026-02-21 092155.png>)[](Add photo of your team here)

![c:\Users\Admin\OneDrive\Pictures\Screenshots\Screenshot 2026-02-21 092043.png](Add photo of your components here)
*List out all components shown*

![c:\Users\Admin\OneDrive\Pictures\Screenshots\Screenshot 2026-02-21 092030.png](Add photo of your components here)
*List out all components shown*

![c:\Users\Admin\OneDrive\Pictures\Screenshots\Screenshot 2026-02-21 091933.png](Add photos of build process here)
*Explain the build steps*

![images/Screenshot 2026-02-21 090736.pngl](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

#### API Documentation

**Base URL:** `https://engineer1701.github.io/Med-Buddy/demo.html`

##### Endpoints

**GET /api/endpoint**
- **Description:** Retrieves the list of added medicines and their schedule
- **Parameters:**
  - `userId` (string): Unique identifier for the user
  - `date` (string): Optional date to filter medicines
- **Response:**
```json
{
  "status": "success",
  "data": [
    {
      "medicineName": "Paracetamol",
      "dosage": "500mg",
      "time": "08:00 AM",
      "frequency": "Daily"
    }
  ]
}

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
{
  "userId": "12345",
  "medicineName": "Paracetamol",
  "dosage": "500mg",
  "time": "08:00 AM",
  "frequency": "Daily"
}
- **Response:**
{
  "status": "success",
  "message": "Medicine added successfully"
}

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![<img width="1080" height="524" alt="Screenshot 2026-02-21 101054" src="https://github.com/user-attachments/assets/54a59368-f625-4a32-86cc-5a98cc7387af" />
](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[https://drive.google.com/file/d/1T_zF0dMAKzKPNcxjQCetWqos62qSw9ls/view?usp=drive_link]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** ChatGPT
**Purpose:** Helped in generating code snippets, debugging JavaScript, and API endpoint structuring

**Key Prompts Used:**
- "Create a medicine reminder system using Web Speech API"
- "Write JavaScript function to track daily medicine adherence"
- "Generate REST API endpoints for CRUD operations on medicines"

**Percentage of AI-generated code:** [Approximately 25-28%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- Anusree C V: Frontend UI/UX design, Dashboard layout, Voice input integration
- Ashwini Shaji: Backend logic, API integration, Reminder notifications, Adherence tracking

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
