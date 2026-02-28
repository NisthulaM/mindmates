<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# [Project Name] 🎯

## Basic Details

### Team Name: MindMates

### Team Members
- Member 1: Khushi - TKM College Of Engineering
- Member 2: Nisthula M - TKM College of Engineering

### Hosted Project Link
[mention your project hosted link here]

### Project Description
SafeHer is a full-stack web application designed to enhance personal safety through intelligent route analysis and community-driven area reporting. It integrates Google Maps, real-time safety reviews, to help users navigate safer path
### The Problem statement
Many individuals, especially women, face uncertainty and safety risks while navigating unfamiliar areas. Traditional map applications focus only on shortest or fastest routes, without considering real-time safety conditions or community-reported risks

### The Solution
SafeHer combines real-time location tracking, community safety reports, and intelligent route analysis to dynamically assess and color-code routes based on safety levels. By integrating user-submitted reviews and automated route evaluation, the platform helps users make safer travel decisions proactively.

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: javascript,HTML5,CSS
- Frameworks used: React Js,Node Js,Express js
- Libraries used: Google maps API,React routern DOM, Mongoose DB,JSon,bcrypt,dotenv,Lucid React
- Tools used: VS code,Git &Github,MongoDB Atlas,nodemon,google cloud console

**For Hardware:**
- Main components: laptop/desktop system,internet connectivity
- Specifications: Min 8GB RAM,Node.Js,web browser
- Tools required: code editor,Git installed,Node Js installed, MongoDB Atlas,Google cloud Account

---

## Features

List the key features of your project:
- User Authentication & Authorization: SafeHer provides secure user registration and login using JWT-based authentication. Passwords are securely hashed before storage. Protected routes ensure that only authenticated users can access core features like safety reporting and route analysis.
- Real-Time Safe Map Integration:The application integrates Google Maps to display real-time user location. Users can generate routes to a selected destination, and the system visually displays these routes directly on the map interface.

- Dynamic Safety-Based Route Coloring:Routes dynamically change color based on community-reported safety data,The system analyzes reported unsafe coordinates along the route path to determine safety level.
- Area Safety Reporting System: The application uses browser geolocation APIs to detect the user’s current coordinates. Reverse geocoding converts latitude and longitude into a human-readable address automatically.
-Trusted Contacts Management:Users can securely add and manage trusted contacts. These contacts are stored in the database and can be extended for emergency notifications or SOS alerts.
-Live Safety Zones Display:The Safe Map page displays nearby safety zones with safety scores, lighting conditions, crowd density, and alert indicators to provide users with situational awareness.
-Emergency & SOS Framework:The backend supports emergency logging and can be extended to trigger real-time alerts, notifications, or location sharing with trusted contacts.
-Community-Driven Safety Intelligence:The system relies on collective user input to create a dynamic safety ecosystem. Community-reported incidents influence route recommendations and visual safety indicators.
---

## Implementation

### For Software:

#### Installation
```bash
npm install,google@map_api install,npm install express

```

#### Run
```bash
npm start,npm run dev
```

### For Hardware:

#### Components Required


#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

https://drive.google.com/drive/folders/1rM8HFWpklty3aVO1VNpoluwI5E3u1JNA?usp=drive_link[home]
The home page that including navigations and showcasing feature cards

https://drive.google.com/drive/folders/1rM8HFWpklty3aVO1VNpoluwI5E3u1JNA?usp=drive_link[safemap]
Shows realtime map and routes according to safety measure .This page also deals with the review section from the user.

https://drive.google.com/drive/folders/1rM8HFWpklty3aVO1VNpoluwI5E3u1JNA?usp=drive_link[features]
gives access to dedicated feature pages

#### Diagrams

**System Architecture:**

*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

https://drive.google.com/drive/folders/1rM8HFWpklty3aVO1VNpoluwI5E3u1JNA?usp=drive_link
SafeHer follows a three-tier architecture consisting of the Presentation Layer (Frontend), Application Layer (Backend), and Data Layer (Database). Each layer has a specific responsibility and communicates securely with the others.

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation
google maps API

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** gets feasible reach to the maps
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
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

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

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
https://drive.google.com/drive/folders/1rM8HFWpklty3aVO1VNpoluwI5E3u1JNA?usp=drive_link
it covers the features such as safemap,emergency sos,company review,trusted networks.

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

chatgpt-openAI

**Tool Used:**  GitHub Copilot, ChatGPT

**Purpose:** [What you used it for]

- Debugging assistance for async functions
- Code review and optimization suggestions

**Key Prompts Used:**
- Give steps how to use google API
- Debug this async function that's causing error
- Optimize this database query

**Percentage of AI-generated code:** 

**Human Contributions:**
- Flowchart design and planning
- Custom idea implementatio
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- Khushi: Frontend, Backend
- Nisthula: Backend connection, API

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
