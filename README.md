# Cristian Cristea's Curriculum Vitae (Résumé)

- **Phone**: [+40 770 779 947](tel:+40770779947)
- **Email**: [cristiancristea00@gmail.com](mailto:cristiancristea00@gmail.com)
- **Location**: Bucharest, Romania
- **LinkedIn**: [cristiancristea00](https://linkedin.com/in/cristiancristea00)
- **GitHub**: [cristiancristea00](https://github.com/cristiancristea00)


# Summary

I’m an embedded software engineer with nearly three years of hands-on experience designing, developing, and testing firmware for microcontrollers and SoCs across diverse platforms (PIC, AVR, and ARM). My work has focused on integrating robust software solutions with hardware to deliver reliable, high-performance systems, from prototype through production. Proficient in C, C++, and Python, I’ve built pipelines involving CI/CD, automated testing, and containerization (Docker, Jenkins) to ensure quality and accelerate development. I’m especially passionate about IoT and machine learning applications in embedded contexts, always eager to leverage cutting-edge technologies to solve real-world challenges. With a strong background in Agile methodologies, I thrive in collaborative settings that foster continuous improvement. I’m excited to keep learning, growing, and building innovative embedded solutions that make a tangible impact.

# Skills

- **Languages**: Native proficiency in Romanian | Full professional proficiency in English | I'm learning French
- **Programming**: C, C++ and Python | AVR, PIC, and ARM Assembly | MATLAB, Rust, TypeScript, and Java
- **Development**: Linux | CMake and Make | Jenkins and Docker | Git and GitHub/GitLab/Bitbucket
- **Python**: NumPy, SciPy, SymPy, Pandas, Seaborn, Matplotlib, OpenCV, scikit-image, scikit-learn, and TensorFlow
- **Others**: LaTeX | Doxygen and Markdown | System Verilog and SPICE
- **Interests**: Embedded Systems | Internet of Things | Machine Learning | Photography
# Experience

## Microchip Technology

*Embedded Software Engineer — Full-time — Hybrid*

**Period:** Aug 2023 to present

**Location:** Bucharest, Romania

- Collaborated with cross-functional teams across multiple countries to design, integrate, and validate embedded system solutions, fostering efficient communication and successful project delivery.
- Designed and validated embedded systems for PIC/AVR microcontrollers, focusing on integration and functional testing to meet system reliability goals.
- Designed and implemented a pipeline system using Jenkins and Docker to perform unit testing, mocking and coverage metrics extraction within an emulation environment for embedded solution projects.
- Developed and updated low-level peripheral drivers for PIC and AVR microcontrollers, implementing unit tests using [Unity](https://www.throwtheswitch.org/unity) and mocks using [CMock](https://github.com/ThrowTheSwitch/CMock) to ensure driver reliability and functionality.
- Created and tested GUI-based code generation tools for new peripherals using TypeScript for development and FreeMarker for templates, leveraging an internal framework.
- Authored and helped with Application Notes and Technical Brief documents, including developing associated coding examples and hardware demos.
- Utilized DITA-based Tridion Docs to create structured documentation, ensuring consistency and compliance with Microchip’s technical writing standards.

## Microchip Technology

*Intern Embedded Applications — Internship — On-site*

**Period:** Jul 2022 to Aug 2023

**Location:** Bucharest, Romania

- Mastered embedded systems fundamentals, including microcontroller programming, interrupts, and communication protocols (UART, I2C, SPI), enabling swift integration into ongoing projects.
- Developed an [Environmental Station](https://github.com/cristiancristea00/environmental-station) embedded project during a mandatory university apprenticeship, integrating sensor data acquisition, processing, and real-time monitoring.
- Gained initial experience with Agile software development methodology through the Scrum process, acquiring a practical understanding of iterative development and team collaboration.
- Familiarised myself with Agile-oriented tools from Atlassian, including Jira, Bitbucket, and Confluence, as well as the DevOps tool Jenkins.
- Contributed to the creation and updating of code examples while undergoing ramp-up training in TypeScript.

## CAMPUS Research Institute

*Research Intern — Internship — On-site*

**Period:** Jul 2020 to Sep 2020

**Location:** Bucharest, Romania

- Generated an artificial dataset of facial images with individuals wearing medical masks correctly or incorrectly, leveraging facial landmarks.
- Engineered and trained a neural network model using transfer learning, optimising it for real-time inference of mask compliance.
- Developed a Python-based application using rospy to integrate the neural network with the [TIAGo](https://pal-robotics.com/robot/tiago) from PAL Robotics.
- Designed and implemented an algorithm to accurately extract and analyse body temperature readings from a thermographic camera feed.

# Projects

## Sensor Board


**Location:** [GitHub](https://github.com/cristiancristea00/sensor-board)

- Designed a custom PCB featuring an STM32 microcontroller with multiple sensors interfaced via SPI, I2C, and ADC connections, leveraging KiCad for schematic capture and PCB layout.
- Developed the project from the ground up, following industry practices and tutorials to gain hands-on experience in PCB design, component selection, and schematic validation.
- Prepared the board for manufacturing and testing, ensuring design readiness for real-world deployment and validation of sensor data acquisition.

## Environmental Station


**Location:** [GitHub](https://github.com/cristiancristea00/environmental-station)

- Developed an IoT-style system to monitor environmental parameters, including temperature, pressure, and humidity, using two AVR-based 8-bit microcontrollers.
- Designed and implemented a communication protocol between the sensor and base boards, leveraging Bluetooth modules with UART and a CRC-based data redundancy check.
- Integrated environmental sensors via I2C and an OLED display via SPI, focusing on efficient real-time data acquisition and visualization.

## Ultrasonic Range Detection


**Location:** [GitHub](https://github.com/microchip-pic-avr-examples/pic18f56q71-ultrasonic-range-detection-mplab-mcc)

- Designed and implemented an ultrasonic range detection system using Core Independent Peripherals (CIP) on the PIC18-Q71 microcontroller family to minimize CPU resource utilization.
- Configured alternating PWM signals to drive a transmitter and employed a Peak Detector, Comparator, and Universal Timer (UTMR) for precise signal acquisition and time-of-flight measurement, enabling accurate distance calculations.
- Built and tested a functional prototype on a demo protoboard with standalone ultrasonic transducers, showcasing real-world application and hardware integration.

## Tic-Tac-Toe


**Location:** [GitHub](https://github.com/cristiancristea00/tic-tac-toe)

- Developed a Tic-Tac-Toe game using the Raspberry Pi Pico, integrating an LCD screen for gameplay, a matrix keypad for user input, and a multiplexed seven-segment display for scorekeeping.
- Implemented three difficulty levels using the minimax algorithm for AI decision-making and a pseudo-random number generator to add variability, allowing for both single-player and two-player modes.
- Leveraged the RP2040’s dual-core architecture to offload user input handling, game menu control, LCD backlight management, and display brightness adjustments to the second core for optimised performance.

# Education

## Faculty of Electronics, Telecommunications and Information Technology — National University of Science and Technology POLITEHNICA Bucharest

*M.Sc. in Advanced Computing in Embedded Systems*

**Period:** Sep 2023 to present

**Location:** Bucharest, Romania

- Thesis: "Cutting-edge algorithm for detecting humans in side-by-side thermal and visible spectrum images"
- Achieved strong academic performance in courses such as Microcontrollers and Embedded Systems, Digital System Design, Distributed and High-Performance Computing, and Parallel Programming.
- Gained hands-on expertise in Reconfigurable Computing, emphasizing FPGA implementations, and deepened knowledge in Performance Analysis and Optimization and Software Development Process and Testing.
- Expanded technical foundation with studies in Functional Verification, Computer Vision, Machine Learning, Operating Systems, and Compilers.

## Faculty of Electronics, Telecommunications and Information Technology — National University of Science and Technology POLITEHNICA Bucharest

*B.Sc. in Information Engineering*

**Period:** Sep 2019 to Jul 2023

**Location:** Bucharest, Romania

- Thesis: "Degraded colour images inpainting system using deep learning techniques"
- Excelled in core computer science courses, including Computer Programming, Data Structures, Algorithms, and Object-Oriented Programming, with a strong focus on Microprocessor Architecture and Microcontrollers.
- Acquired hands-on experience in Circuit Synthesis and Testing using Verilog, complemented by a solid understanding of Digital Circuit Design principles.
- Built the foundation in Analog Circuit Design, including simulation and analysis using SPICE programs.
- Engaged in diverse coursework spanning Machine Learning, Image Processing and Analysis, Distributed and Parallel Computing, Database Systems, Digital and Statistical Signal Processing, Information Theory, Communication Systems, and Computer Networks.
- Developed advanced mathematical skills, including Statistics, Probability, Linear Algebra, Multivariable Calculus, and Differential Equations.

# Certifications

### [CCNA: Introduction to Networks](https://www.credly.com/badges/f765af4e-e1df-4644-8a9c-4a8ab9fedc42) 
**Issued by Cisco**

Acquired in **2021**


### [Google IT Automation with Python Professional Certificate](https://www.credly.com/badges/740a37a0-4a40-4a36-abe1-679ad53e4146) 
**Issued by Coursera**

Acquired in **2020**


### [Google IT Support Professional Certificate](https://www.credly.com/badges/0c20b39b-18c1-4498-8e57-1aedb3f36904) 
**Issued by Coursera**

Acquired in **2020**


### [TensorFlow: Data and Deployment Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/XHAD9DTRYTMG) 
**Issued by Coursera**

Acquired in **2020**


### [TensorFlow Developer Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/certificate/Z79E5B7CY76C) 
**Issued by Coursera**

Acquired in **2020**


### [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/BRJV9TAX7QUA) 
**Issued by Coursera**

Acquired in **2020**


### [Cambridge C1 Advanced](https://1drv.ms/b/s!Art6DR7ET63umGTH3dIUsOB616G7?e=Df5XSN) 
**Issued by Cambridge English**

Acquired in **2018**


### [International Computer Drivers License](https://bd.ecdl.org.ro/ecdlvcard/certification.aspx?pcode=2431704NgVYIX7Ecq9P3KujF1UR0pG) 
**Issued by ICDL**

Acquired in **2018**


