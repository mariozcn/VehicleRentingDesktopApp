# 🚗 Vehicle Renting Desktop App

A simple Windows Forms (.NET) application for managing vehicle rentals — developed in C#. This app allows users to add, view, rent, and remove cars and motorcycles using a user-friendly GUI.

## 📦 Executable

This app is built as a standalone `.exe` file. No installation or Visual Studio required.

- Download the executable from the [Releases](https://github.com/mariozcn/VehicleRentingDesktopApp/releases) section
- Double-click to run the app on Windows.

> ⚠️ .NET Framework may be required if not already installed on your system.

---

## ✨ Features

- ✅ Add cars and motorcycles with details (brand, model, year, capacity, etc.)
- ✅ Rent and return a vehicle by license plate
- ✅ Remove vehicles
- ✅ View all current vehicles in the system

---


## 🛠 Technologies Used

- C#
- .NET Framework (Windows Forms)
- Visual Studio (for development)
- Object-Oriented Programming principles

---

## 📂 Project Structure

```plaintext
├── Forms/
│   ├── AddVehicleForm.cs
│   ├── RentVehicleForm.cs
│   ├── RemoveVehicleForm.cs
├── Models/
│   ├── Vehicle.cs
│   ├── Car.cs
│   ├── Motorcycle.cs
├── bin/Debug/VehicleRentingDesktopApp.exe
├── Program.cs
├── README.md
