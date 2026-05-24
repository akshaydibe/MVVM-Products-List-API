# Product Catalog - UIKit MVVM Architecture

A modern iOS Product Catalog application built using **UIKit** and the **MVVM (Model-View-ViewModel)** architecture pattern.  
This project demonstrates clean architecture principles, scalable networking, reusable components, and efficient UI updates using data binding.

The application fetches product data from a remote API, displays product listings with images, and supports both Light and Dark Mode.

---

# Screenshots

| Products Light Mode | Products Dark Mode |
|:-------------------:|:------------------:|
| <img width="300" alt="Products Light" src="https://github.com/user-attachments/assets/9d031ec6-5e22-4f7b-abb9-54e9c53c0eb5" /> | <img width="300" alt="Products Dark" src="https://github.com/user-attachments/assets/a4483242-8117-4c88-b99c-85410b65ce0d" /> |

---

# Features

- Product listing using remote API
- MVVM architecture implementation
- Data Binding using Closures
- Generic networking layer using URLSession
- Singleton-based API manager
- SOLID principles based structure
- JSON parsing using Decodable
- Image loading and caching using Kingfisher
- Reusable UITableViewCell with XIB
- Light & Dark mode support
- Clean and scalable folder structure
- Swift Package Manager integration

---

# Tech Stack

- UIKit
- Swift
- MVVM Architecture
- URLSession
- Swift Package Manager (SPM)
- Kingfisher
- JSONDecoder
- UITableView
- UIStackView
- XIBs
- Closures & Completion Handlers

---

# Architecture

This project follows the **MVVM (Model-View-ViewModel)** architecture pattern.

## Model
Responsible for handling API response models and decoding JSON data.

## View
Handles UI rendering using UIKit components like:
- UIViewController
- UITableView
- UITableViewCell
- UIStackView

## ViewModel
Acts as a bridge between View and Model:
- Handles business logic
- Performs API calls
- Prepares UI-ready data
- Uses data binding to update the View

---

# Networking Layer

The project uses a reusable and generic API layer built on top of `URLSession`.

### Includes:
- Generic API requests
- Decodable response parsing
- Error handling
- Completion handlers
- Scalable network architecture

---

# Data Binding

Data Binding is implemented using **Closures**, allowing the ViewModel to notify the View whenever data changes.

Benefits:
- Better separation of concerns
- Reactive UI updates
- Cleaner ViewController code

---

# Third Party Library

## Kingfisher

Used for:
- Asynchronous image downloading
- Image caching
- Smooth scrolling performance

Integrated using:
- Swift Package Manager (SPM)

---

# Concepts Covered

- MVVM Design Pattern
- SOLID Principles
- Singleton Design Pattern
- Generic Networking
- Memory Management
- Closures & Typealiases
- Completion Handlers
- Enums
- Inheritance
- Final Keyword
- Init Methods
- UITableView & XIBs
- Light & Dark Mode Support

---

# Project Structure

```bash
ProductCatalog
│
├── Model
├── View
├── ViewModel
├── NetworkManager
├── Utilities
├── Resources
└── SupportingFiles
```

---

# Requirements

- iOS 15.0+
- Xcode 16+
- Swift 5+

---

# Installation

1. Clone the repository

```bash
git clone https://github.com/akshaydibe/UIKit-MVVM-Product-Catalog.git
```

2. Open the project in Xcode

3. Resolve Swift Packages

4. Run the application

---

# Learning Outcomes

This project helps in understanding:
- Real-world MVVM implementation
- Clean architecture in UIKit
- Generic API integration
- Data Binding using Closures
- Scalable networking structure
- Reusable UIKit components

---

# Author

Akshay Dibe
