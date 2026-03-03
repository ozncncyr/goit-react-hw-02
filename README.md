# Sip Happens Café Feedback App

This is a simple React application built with Vite for collecting and displaying
user feedback for a fictional café, "Sip Happens Café". Users can rate the
service as Good, Neutral, or Bad, and view statistics about the feedback.

## Features

- Interactive feedback buttons: Good, Neutral, Bad
- Real-time statistics: total feedback count and percentage of positive feedback
- Local storage persistence: feedback data is saved between sessions
- Option to reset feedback statistics
- Responsive and minimal UI

## Technologies Used

- React 19
- Vite
- CSS Modules
- Local Storage API

## Getting Started

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/ozncncyr/goit-react-hw-02.git
   ```
2. Navigate to the project directory:
   ```
   cd goit-react-hw-02
   ```
3. Install dependencies:
   ```
   npm install
   ```

### Running the App

Start the development server:

```
npm run dev
```

Open your browser and go to `http://localhost:5173` (or the port shown in your
terminal).

### Building for Production

To build the app for production:

```
npm run build
```

## Project Structure

- `src/App.jsx`: Main application logic and state management
- `src/components/Description/Description.jsx`: App description and instructions
- `src/components/Feedback/Feedback.jsx`: Displays feedback statistics
- `src/components/Notification/Notification.jsx`: Shown when no feedback is
  present
- `src/components/Options/Options.jsx`: Feedback and reset buttons

## License

This project is for educational purposes.
