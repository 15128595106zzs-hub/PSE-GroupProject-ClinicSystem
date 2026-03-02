# Test Record - Student Appointment Booking System Prototype

## 1. Introduction
This document records the interaction testing of the high-fidelity Figma prototype. Since this is a prototype, we focus on **User Flow Verification** and **Interaction Logic** rather than backend data validation.

## 2. Test Environment
* **Device:** Desktop Web Browser
* **Tool:** Figma Interactive Prototype
* **Date:** 2026-03-02

## 3. Test Cases & Results

| Test ID | Feature | Action (User Input) | Expected Result (System Response) | Status |
| :--- | :--- | :--- | :--- | :--- |
| **TC-01** | **User Authentication** | Click the "LOGIN" button on Screen 1. | System navigates to "Select Clinical Department" (Screen 2). | **Pass** |
| **TC-02** | **Dept Selection** | Click "General Medicine" on Screen 2. | System navigates to "Appointment Details" (Screen 3). | **Pass** |
| **TC-03** | **Availability Logic** | Observe the "02:00 PM" slot on Screen 3. | Slot is greyed out/disabled, reflecting "Slot Full" logic from Sequence Diagram. | **Pass** |
| **TC-04** | **Booking Process** | Click "CONFIRM BOOKING" on Screen 3. | System displays "Appointment Successful!" (Screen 4) with correct summary. | **Pass** |
| **TC-05** | **Navigation Loop** | Click "BACK TO DASHBOARD" on Screen 4. | System returns to the initial screen to allow new actions. | **Pass** |

## 4. Conclusion
The prototype successfully demonstrates all core functional paths defined in the **Sequence Diagram**. All interactive elements respond correctly to user input.
