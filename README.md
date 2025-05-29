# Slot Probability Tracker

A sophisticated GUI application for tracking and analyzing probabilities between start and end slots in a game or system. This tool helps visualize patterns and probabilities between different slot combinations.

## Features

- **Interactive GUI**: Modern, user-friendly interface with a sleek dark theme
- **Slot Tracking**: Track start and end positions for 8 different slots:
  1. Melon
  2. Orange
  3. Apple
  4. Lettuce
  5. Fish
  6. Burger
  7. Shrimp
  8. Chicken
- **Data Analysis**:
  - Real-time probability calculations
  - Percentage tracking for both start and end positions
  - Historical data visualization
  - Top 5 most common end positions for each start position
- **Data Management**:
  - Automatic data saving to CSV
  - Data export functionality
  - Data reset option
- **Visual Features**:
  - Interactive charts and graphs
 

## Requirements

- Python 3.x
- Required packages (install using `pip install -r requirements.txt`):
  - Pillow >= 9.5.0
  - matplotlib >= 3.7.0
  - numpy >= 1.24.0

## Usage

1. Run the program:
   ```bash
   python3 improved_tracker.py
   ```

2. Using the Interface:
   - Select a start slot by clicking on one of the slot buttons
   - Select an end slot by clicking on another slot button
   - Click "Register Round" to record the combination
   - View statistics in the report section
   - Use the "Analysis" button to see detailed probability charts
   - Export data using the "Export Data" button when needed

3. Data Storage:
   - All data is automatically saved to `data.csv`
   - The file is created automatically on first run
   - Data persists between sessions

## Features in Detail

### Main Interface
- Modern dark theme with golden accents
- Clear slot selection buttons
- Real-time statistics display
- Easy-to-use round registration

### Analysis Window
- Detailed probability charts
- Top 5 most common end positions for each start position
- Visual representation of slot relationships
- Interactive data exploration

### Data Management
- Automatic CSV storage
- Data export functionality
- Option to reset data if needed
- Persistent storage between sessions

## Contributing

Feel free to submit issues and enhancement requests!
