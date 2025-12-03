
Smart Irrigation System – Web Simulation Interface
==================================================
🎓 Semester 3 Project – Design Thinking & Methodology
Course: Design Thinking & Methodology (DTM)
Team: 6 Members (Group Project)

💡 Project Overview
This project, titled “Smart Irrigation System – Web Simulation Interface”, is a complete 
frontend-only web application that simulates how a smart irrigation system works.

The system is developed using HTML, CSS, JavaScript and is designed in a way that 
real sensors and hardware can be connected to it in the future. 
However, this project currently runs as a **full simulation**, demonstrating the logic, 
automation flow, and interface of a real smart irrigation system.

The interface allows users to monitor environmental parameters like soil moisture, tank level,
temperature, rainfall, power status, and also control irrigation valves manually or 
automatically — all through a clean and responsive UI.

The system structure supports:
Home Status Dashboard → Controls → Crop Care Advisor → Sensors Panel 
→ History & Analytics → System Test Lab → Help Section

⚙️ Working Principle (Simulation-Based)
1. Sensor values (soil moisture, temperature, rain, tank level, etc.) are simulated and 
   updated inside the web application.
2. The UI processes these values and displays the following:
   - Soil dryness
   - Rain condition
   - Tank water level
   - Power and battery status
   - Weather indicators
3. In Automatic Mode:
   - If soil becomes dry → Irrigation turns ON
   - If rain is detected → Irrigation pauses instantly
   - If tank becomes low → Tank refill pump activates (simulation)
4. In Manual Mode:
   - User can trigger each irrigation zone manually.
5. The Test Lab allows users to simulate conditions such as:
   - Dry Soil
   - Rain
   - Empty Tank
   The system visually shows how decisions are made (Sensors → Logic → Outputs).

🔩 Modules / Pages in the Web App
- 🏠 Home Dashboard  
- 🎛️ Controls (Manual / Automatic)  
- 🌱 Crop Care Advisor (Pests, Fertilizers, Growth Stages)  
- 📡 Sensors & Infrastructure  
- 📈 History Logs + Line Charts  
- 🧪 System Test Lab (Decision Flow Simulator)  
- ❓ Help & Support Panel  

💻 Technologies Used
- HTML5  
- CSS3  
- Tailwind CSS  
- JavaScript (Vanilla JS)  
- Chart.js  
- FontAwesome Icons  

⚠️ Note
This project has **no physical hardware** connected to it, 
but the structure is designed to support actual IoT hardware in the future through 
API endpoints or real-time communication (REST/MQTT/WebSocket).

🔌 Application Flow (Simulation)
Sensor Values → Logic Engine → UI Update → Automatic/Manual Irrigation Response


🧠 Learning Outcomes
- Learned to design a complex multi-page UI using HTML, CSS, and Tailwind
- Gained experience in JavaScript-based data simulation
- Understood UI/UX flow planning and user-centric design
- Implemented charts using Chart.js for data visualization
- Learned to structure a frontend system to support future IoT integration
- Improved problem-solving and teamwork skills
- Explored dark mode UI and responsive design concepts

🏁 Conclusion
The “Smart Irrigation System – Web Simulation Interface” project demonstrates how 
a complete irrigation monitoring and control system can be represented through a 
web-based simulation.  
