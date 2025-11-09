# Community Watch & Vehicle Tracker

This is a web-based mapping application for community and rapid response groups to track vehicles, watch members, and designated patrol areas in real-time.

## Features

- **Interactive Map Interface**: Built with Leaflet.js for smooth map interactions
- **Vehicle Tracking**: Track and log suspicious vehicles with license plates, descriptions, and timestamps
- **Watch Member Management**: Monitor watch members on duty (vehicles, bikes, or on foot) with shift times
- **Watch Areas**: Draw custom polygons or rectangles to define patrol zones
- **Advanced Filtering**: Filter markers by name, license plate, time windows, and watch areas
- **Quick Reference Plates**: Maintain a searchable list of plates of interest
- **Data Export**: Export all marker data to JSON format
- **Cross Street Search**: Quickly locate and zoom to specific intersections
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## Getting Started

### Prerequisites

No installation required! This is a standalone HTML file that runs entirely in your web browser.

### Usage

1. Download the `Community Defense - Patrol Tracker.html` file
2. Open it in any web browser
3. It can be used immediately

**Note**: All data is stored in your browser's memory only

## How to Use

### Adding Markers

**Watch Members**
1. Open the "Watch Members" section
2. Select type (Vehicle, Bike, or On Foot)
3. Enter name and other details
4. Set shift times if needed
5. Click on the map or enter an address
6. Click "Add Watch Member"

**Suspicious Vehicles**
1. Open the "Suspicious Vehicles" section
2. Enter vehicle description and license plate
3. Click on the map to set location
4. Click "Add Suspicious Vehicle"

**Watch Areas**
1. Open the "Watch Area" section
2. Enter area name and choose a border color
3. Click "Draw New Area"
4. Click points on the map to create a polygon
5. Double-click to finish

### Filtering

Use the filter section to:
- Search by name or license plate (partial matches work)
- Filter by specific watch area
- Filter by time window (shows watch members on duty during that hour)
- Search for cross streets and zoom to them

### Data Management

- **Export Data**: Click "Export All Data" to download a JSON file with all markers
- **Clear All**: Use "Clear All Markers" to remove all data (requires confirmation)
- **Quick Reference Plates**: Maintain a list of plates to quickly check against

## Technical Details

- Built with pure HTML, CSS, and JavaScript
- Uses Leaflet.js for mapping
- Uses Nominatim for geocoding
- No backend required - runs entirely client-side
- Data persists only in browser memory (cleared on page refresh)

## Browser Compatibility

Works with all modern browsers:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

This project is provided as-is for community use.

## Support

For questions or issues, please open an issue on GitHub.

## From Chicago

This tool was made for and by people in Chicago. Stand together and protect yourself.
