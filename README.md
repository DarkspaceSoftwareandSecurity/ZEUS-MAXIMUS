# ZEUS-MAXIMUS
![dark_angel_armor]
(https://github.com/user-attachments/assets/75fac46f-5fa9-4f26-93f9-50e2a9f32035)
Maximusv10 Feature Full Documentation
Author: Michael James Blenkinsop
Company: DarkSpace Software & Security LLC
Email: mickyblenk@gmail.com
Phone: +44 7710 669684
Website: darkspacesoftwareandsecurity.com
© 2024 DarkSpace Software & Security LLC. All rights reserved.
Table of Contents
    • 1. Introduction
    • 2. Installation
    • 3. Running the Setup Script (`setup.sh`)
    • 4. Using the Software
    • 5. Features and Functionalities
    • 6. License
    • 7. Author Information
Introduction
Maximus Feature is an all-in-one solution developed by DarkSpace Software & Security LLC for incident response, network monitoring, and forensic reporting. It combines real-time network monitoring, interactive reporting, and a fully functional web interface to assist in managing security incidents effectively.








Installation
Step 1: Clone the Project Repository
First, clone the repository that contains the setup.sh script:
git clone <repository_url>
Step 2: Run the Setup Script
Run the setup.sh script to set up the Django project, install dependencies, and configure everything:
bash setup.sh
Step 3: Redis Installation (Windows Users)
If you are on Windows, install Redis manually from https://github.com/microsoftarchive/redis/releases.
Step 4: Activate the Virtual Environment
After running the setup.sh, activate the Python virtual environment that was created during the setup:
For Unix-based systems (Linux/macOS):
source venv/bin/activate
For Windows:
source venv/Scripts/activate
Running the Setup Script (`setup.sh`)
The setup script automates the environment configuration. It will set up Django, install Python and Node.js dependencies, set up the network monitoring configurations, the frontend components, and Celery for background tasks.







Using the Software
Step 1: Run Django Backend Server
Activate the virtual environment and run the Django server:
python manage.py runserver
Step 2: Run Celery for Background Tasks
Make sure Redis is running before starting Celery:
celery -A myproject worker --loglevel=info
Step 3: Run the Frontend React Dashboard
Navigate to the frontend directory and start the development server for the React-based UI:
cd frontend
npm start
Step 4: Run the DAVINCI-STAR-OV-DAVID Data Analysis Script
Ensure the virtual environment is activated, then run:
python davinci_star_analysis.py
Features and Functionalities
    1. 1. DarkSpace Banner - Displays information about DarkSpace Software & Security.
    2. 2. Dependency Installation - Installs necessary Python and JavaScript dependencies.
    3. 3. Network Monitoring and Blocking - Uses raw socket connections to monitor network activity.
    4. 4. Packet Capture (PCAP) - Captures packets and saves them for analysis.
    5. 5. Capture Attacker's Image - Captures images using the webcam for physical security scenarios.
    6. 6. Forensic Report Generation - Creates DOCX and XLSX reports summarizing incidents.
    7. 7. Attack Pattern Graphical Display - Visualizes attack patterns using matplotlib.
    8. 8. Voice Command Interaction - Allows command-based interaction with the system.
    9. 9. Frontend Dashboard Interface - React-based dashboard for monitoring and incident management.
License
MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
Author Information
Author: Michael James Blenkinsop
Company: DarkSpace Software & Security LLC
Email: mickyblenk@gmail.com
Phone: +44 7710 669684
Website: darkspacesoftwareandsecurity.com
