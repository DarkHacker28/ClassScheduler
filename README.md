# ClassScheduler
 ClassScheduler is a C++ project designed to efficiently manage and schedule classes using advanced algorithms and libraries. This project ensures optimal class allocation and conflict resolution, making it a perfect fit for educational institutions or training programs.


🚀 Features :
Conflict Detection: Automatically detects and resolves scheduling conflicts.
Flexible Input: Accepts customizable inputs for class timings, instructors, and room availability.
Optimized Scheduling: Uses efficient algorithms to create schedules that maximize resource utilization.
User-Friendly Interface: Provides clear outputs for easy interpretation of schedules.

🛠️ Technologies :
Programming Language: C++

Libraries Used:
Standard Template Library (STL): Utilized for efficient data management with vectors, maps, and priority queues.
Boost Library: For advanced features like graph algorithms (if used).
Additional libraries based on project requirements.

📂 Project Structure :
main.cpp: The entry point of the program.
scheduler.cpp & scheduler.h: Core scheduling logic and utility functions.
input_parser.cpp: Handles user input and file parsing.
output_generator.cpp: Formats and displays the final schedule.

🧑‍💻 Getting Started : 
Prerequisites
C++17 or later.
A compatible compiler (e.g., GCC, Clang, or MSVC).
Libraries: Boost (optional, based on features).
Building the Project

Clone the repository:
1. git clone https://github.com/yourusername/ClassScheduler.git  

2. cd ClassScheduler

Compile the project:
g++ -std=c++17 -o ClassScheduler main.cpp scheduler.cpp input_parser.cpp output_generator.cpp 

Run the program:
./ClassScheduler  

📝 Usage
Provide your input data in the specified format (e.g., JSON or CSV) to schedule classes. The output will display the finalized schedule along with any conflict resolutions.

