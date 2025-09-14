📘 Marvellous Study Tracker App

A console-based Java application to help students systematically log, track, summarize, and export their study sessions.

This project demonstrates practical usage of Java Collections, File I/O, and Object-Oriented Design in a utility-driven application.

🚀 Features

* Insert Study Log
  Record study sessions with auto-generated date, subject, duration, and description.

* Display Logs
  View all study logs currently stored in memory.

* Summary by Date
  Calculate & display total study hours grouped by date.

* Summary by Subject
  Calculate & display total study hours grouped by subject.

* Export to CSV
  Save all logs into a CSV file (MarvellousStudy.csv) for offline tracking.

* User-Friendly Console Menu
  Menu-driven interface with switch-case navigation for ease of use.

🛠️ Technologies Used

* Language: Java

* Packages & APIs:

  java.util.* → Data structures (ArrayList, TreeMap), user input via Scanner

  java.time.LocalDate → Auto-captures current date for logs

  java.io.* → File handling and CSV export

📂 Project Structure
Classes & Responsibilities

🔹 StudyLog

   Represents a single study session.

   Attributes: LocalDate date, String subject, double duration, String description

   Methods: Constructor, getters, toString()

🔹 StudyTracker

   Manages all logs in memory.

   Attributes: ArrayList<StudyLog> database

   Methods: InsertLog(), DisplayLog(), SummaryByDate(), SummaryBySubject(), ExportCSV()

🔹 StudyTrackerApp (Main Class)

   Contains main() method

   Handles menu-driven interface and user input

📦 How to Run

* Clone the repository:
  git clone https://github.com/<AdityaBhonde>/Study-Tracker-App.git
  cd Study-Tracker-App
  
* Compile the project:
  javac StudyTackerApp.java
  
* Run the application:
  java StudyTackerApp.java  

   
   
  
  
