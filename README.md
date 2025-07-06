## Open Borders - Immigration Guide App

## Overview

Open Borders is a user-centric mobile application built to help individuals navigate complex
immigration processes with ease. Designed as a free resource, it offers essential tools like expert
consultancy scheduling, structured guidance through sequential questions, real-time news updates,
and multilingual support. Whether using the app in guest mode or via secure login, users gain access
to reliable information and assistance tailored to US immigration.

> **Disclaimer**: This repository contains a clone of the original project created for showcasing my
> contributions. Due to intellectual property agreements, the actual code and project are not
> available publicly. This repo is intended to demonstrate my work on the project.

## Features

### 1. Guest Mode & Account Management

- **Guest Access**: Users can explore key features without signing in.
- **Secure Login**: Email and Google authentication options for personalized access.

### 2. Consultancy Scheduling

- **Schedule a Session**: Users can book consultations with immigration experts.
- **Multiple Payment Options**: Supports Stripe and Google Pay for secure payments.

### 3. Guided Q&A Flow

- **Step-by-Step Questions**: Users can answer a guided series of questions to get personalized
  immigration information.
- **Interactive Flow**: Helps users identify their best immigration path or visa option based on
  their answers.

### 4. News Section

- **Real-Time Immigration News**: Provides up-to-date news related to US immigration laws, policies,
  and updates.

### 5. Multilingual & Accessible

- **Global Accessibility**: Designed to serve users worldwide, offering relevant information in
  multiple languages.

## Technologies Used

- **Kotlin**: Primary language used for native Android development.
- **Firebase Authentication**: For secure email and Google sign-in.
- **MVVM Architecture**: Clean separation of UI, business logic, and data layers.
- **Stripe & Google Pay**: Integrated payment systems for secure transactions.
- **Retrofit**: For communicating with backend APIs.
- **Room Database**: For local data storage and offline support.
- **Koin**: For dependency injection.
- **Coroutines**: To manage state and background tasks efficiently.

## App Architecture

The app follows the **MVVM architecture** for maintainability and scalability:

- **Model**: Handles local and remote data.
- **ViewModel**: Manages logic and prepares data for the UI.
- **View**: Displays data and captures user interactions.
- **Repository**: Connects ViewModel to data sources (APIs, Room DB, etc.).

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/open-borders.git
cd open-borders
