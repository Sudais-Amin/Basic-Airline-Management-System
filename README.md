# Basic-Airline-Management-System
# ✈️ Flight Management System

A console-based Flight Management System built in C++ that allows passengers to view and book flights, and employees to manage flight information.

## 📋 Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### Passenger Features
- 🔍 View all available flights
- 🎫 Book flight tickets
- 📄 Automatic ticket generation (saved as text file)
- 💺 Real-time seat availability tracking

### Employee Features
- ➕ Add new flights to the system
- 🗑️ Delete existing flights
- 👀 View all flights in the database
- 🔐 Secure login system

### System Features
- 💾 Persistent data storage using file I/O
- 📊 Flight information includes: ID, departure, destination, date, time, class, price, and seat availability
- 🎟️ Automated ticket generation with booking details

## 🛠️ Technologies Used

- **Language:** C++
- **Concepts:** 
  - File I/O (ifstream/ofstream)
  - Structures (struct)
  - Arrays
  - Functions
  - Data persistence

## 📥 Installation

### Prerequisites
- C++ compiler (GCC, MinGW, or Visual Studio)
- Windows OS (for `system("cls")` functionality)

### Steps

1. Clone the repository:
```bash
git clone https://github.com/yourusername/flight-management-system.git
```

2. Navigate to the project directory:
```bash
cd flight-management-system
```

3. Compile the program:
```bash
g++ flight_management.cpp -o flight_system
```

4. Run the executable:
```bash
./flight_system
```

## 🚀 Usage

### Main Menu
When you run the program, you'll see three options:
1. **Passenger** - Access passenger features
2. **Employee** - Access employee features (requires password)
3. **Exit** - Close the program

### Employee Login
- Default password: `amin` (case-insensitive)
- *Note: In production, this should be replaced with secure authentication*

### Booking a Flight
1. Select "Passenger" from main menu
2. Choose "Display All Flights" to see available options
3. Select "Book Flight"
4. Enter the Flight ID
5. Enter your name
6. A ticket file will be generated automatically

### Managing Flights (Employee)
1. Select "Employee" and enter password
2. Choose from:
   - Add new flight with all details
   - Delete flight by ID
   - View all flights

## 📁 Project Structure

```
flight-management-system/
│
├── flight_management.cpp    # Main source code
├── flights.txt              # Database file (auto-generated)
├── Ticket_*.txt            # Generated ticket files
└── README.md               # Project documentation
```

## 🔮 Future Enhancements

- [ ] Implement proper authentication system
- [ ] Add passenger database
- [ ] Search and filter flights by destination/date
- [ ] Generate unique booking IDs
- [ ] Add input validation and error handling
- [ ] Cross-platform compatibility (Linux/Mac support)
- [ ] Refactor to use classes (OOP approach)
- [ ] Use dynamic memory (vectors instead of arrays)
- [ ] Add payment processing simulation
- [ ] Generate PDF tickets instead of text files

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Your Name**
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/Sudaisamin)
- GitHub: [@yourusername](https://github.com/Sudais-Amin)
- Email: connect.sudais@outlook.com

## 🙏 Acknowledgments

- Built as a learning project to demonstrate C++ fundamentals
- Thanks to the C++ community for documentation and resources

---

⭐ If you found this project helpful, please consider giving it a star!

**Note:** This is an educational project demonstrating basic C++ concepts. For production use, additional security measures and error handling would be required.
