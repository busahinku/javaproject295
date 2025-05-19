
![Logo](https://i.hizliresim.com/bbzrm6c.png)


# SirLewis&Hamilton

SirLewis&Hamilton is a real-world Java Application for Healthcare environment. It is not just an ordinary hospital, it also covers local healthcare businesses and helps them to grow with finding new patients. "The Way Your Healthy Life" is the only mission of this start-up.

With the help of Object-Oriented Programming We've created this Healthcare Appointment and Management System.

## Features

### User Management
- Multiple User Roles (Founder, Doctor, Patient, Pharmacist, Assistant...)
- Not secure :( authentication system :(( We do not know any security stuff.
- Profile management with restricted properties :D
- Private and Hospital Doctor support 

### Appointment System
- Static scheduling system with time slot management
- Appointment creation and management for patients
- Support for both hospital and private practice appointments
- Automated cost calculation based on private doctors consulation/private fee.

### Medical Records
- Comprehensive patient medical history can be created by doctors.
- Basic prescription management.
- Lab results and diagnoses recording

### Room Management
- Different room types (Radiology, MR, Donating...)
- Patient room assignment
- Equipment management for different rooms

### Inventory Management
- Medication tracking
- Analyzing medical inventory and Stock monitoring

### Billing System
- Automated cost calculation
- Insurance integration (its functionality will be added next updates)
- Financial reporting

## User Roles

### Founder
- Department and Hospital management
- Doctor hiring and firint
- Financial reporting

### Doctor (Hospital & Private)
- Patient management
- Appointment scheduling
- Medical record updates
- Prescription writing
- Room assignment
- Private practice management (for private doctors)
- New feature will be added with next updates: Say Hi to your Tarot Doctor.

### Patient
- Appointment creating
- Medical record access
- Review system
- Billing management

### Pharmacist
- Inventory management
- Prescription fulfillment
- Medication dispensing
- Stock monitoring

### Assistant
- Doctor support
- Appointment coordination
- Patient assistance

## Technical Details

### Prerequisites
- Java Development Kit
- Any Java IDE (Eclipse, IntelliJ IDEA, etc.) I've used IntelliJ IDEA

### Project Structure
```
src/
├── Main.java                 # Main application entry point
└── objects/                  # Core business objects
    ├── Person.java           # Base class for all users
    ├── Doctor.java           # Doctor class
    ├── Patient.java          # Patient class
    ├── Pharmacist.java       # Pharmacist class
    ├── Assistant.java        # Assistant class
    ├── Founder.java          # Founder class
    ├── Appointment.java      # Appointment management
    ├── MedicalRecord.java    # Medical records
    ├── Prescription.java     # Prescription management
    ├── Room.java             # Room management
    ├── Inventory.java        # Inventory management
    ├── Department.java       # Department management
    └── StaticSchedule.java   # Appointment scheduling
```

### Key Components

#### StaticSchedule
- Manages appointment time slots (I still do not know how time slot works. It is good function in LDT though)
- Handles weekday scheduling (Monday-Friday)
- Time slots from 9:00 to 17:00
- 30-minute appointment intervals

#### Appointment System
- Unique appointment IDs from 0 to infinity
- Status tracking (Scheduled, Completed, Canceled)
- Cost calculation
- Payment tracking

#### Room Management
- Multiple room types
- Capacity tracking
- Equipment management
- Patient assignment

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/busahinku/javaproject295
```

2. Open the project in your IDE

3. Run the Main.java file to start the application

4. Use the following default credentials for testing:
   - Founder: username: "founder", password: "founder"
   - Doctor: username: "doctor", password: "doctor"
   - Patient: username: "patient", password: "patient"
   - Pharmacist: username: "pharmacist", password: "pharmacist"
   - Assistant: username: "assistant", password: "assistant"

5. Then use functions of these users to use application.

## Security Features

- There is no security stuff :( Your data can be stolen by hackers. Please do not forget the change it.

## Reporting

- Monthly financial reports
- Department performance metrics
- Patient statistics

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b unnecessaryFeature`)
3. Commit your changes (`git commit -m 'some major changes: -1283192831831928312931831 line changed.'`)
4. Push to the branch (`git push origin unnecessaryFeature`)
5. Open a Pull Request (IDK how to accept though.)

##  License

We do not have any license type but you can think this is commercial-free. This section seems cool when I see in different projects, so I'll add this section :))

## Authors

- Burak Sahin Kucuk
- Burak Sahin Kucuk
- Burak Sahin Kucuk
- Berat Ozkan
- Berat Ozkan
- Furkan Karakurt
- Fuad İbrahimli
- Emre Kale

## Acknowledgments

- Thanks to all contributors 
- Inspired by real-world healthcare management needs. I love you Eren Bali, I wish you've never come back to the Udemy.

## Support

For support, email support@sirlewis-hamilton.com (this does not exist.) or just call me from 0530 000 0000.

bye,
