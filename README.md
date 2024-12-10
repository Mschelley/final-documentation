Interactive Campus Map with Lost and Found Feature
Introduction
The Interactive Campus Map is designed to allow users to explore different locations across a campus. It provides a visual representation of campus areas on a map and enables users to interact with markers, view location details, and navigate easily through the campus. The Lost and Found feature is integrated, allowing users to report lost and found items associated with specific campus locations. Users can view submissions and help others locate lost belongings.

Key Features
Campus Map Interaction
Map Navigation: The map is interactive, and users can zoom in, zoom out, and move the map to explore various campus locations.
Location Markers: Markers are placed on the map representing important locations such as buildings, offices, and other notable spots on the campus.
Location Popups: Each location marker has a popup that provides more detailed information about that location, including a brief description and images (where available).
Dynamic Centering: Users can click on buttons corresponding to different campus locations to automatically center the map on that location.
Lost and Found Feature
Item Reporting: Users can report items they have lost or found. Each report contains details such as item description, location, time of loss, and whether the item is lost or found.
Item Display: Submitted items are displayed in a dedicated section for lost and found items. Users can filter through these reports to find items relevant to their search.
Item Categorization: Items are categorized as “Lost” or “Found,” making it easier for users to identify and view appropriate reports.
Location-based Reporting: Lost and found items are associated with specific campus locations, and users can see which location the item was lost or found at.

User Interface (UI) Components
Campus Map
The campus map is the central component of the application. It allows users to:

Navigate the campus by dragging or zooming the map.
Click on location markers to view more details about each location.
Click on location-specific buttons to center the map on specific areas of the campus.
Location Buttons
Each campus building or notable location has an associated button that, when clicked, automatically pans the map to the respective location. This helps users quickly navigate to areas of interest.

Lost and Found Form
The Lost and Found form is used by users to submit reports of lost or found items. The form asks for:

Item Description: A brief description of the item (e.g., color, type).
Location: The campus location where the item was lost or found.
Time: The date and time the item was lost or found.
Item Type: Whether the item is "Lost" or "Found."
Lost and Found Display
Items reported as lost or found are displayed in two distinct lists:

Lost Items: Items that have been reported as lost by users.
Found Items: Items that have been reported as found by users.
Each entry in the list includes the item description, location, and time, providing clear details for users.

Responsive Design
The user interface is responsive, ensuring that the map and form elements adjust properly on different screen sizes, making the application easy to use on both desktop and mobile devices.

Workflow Overview
Interacting with the Campus Map
Exploring Locations: Users can explore the campus map by zooming in and out and dragging the map to view various locations.
Viewing Location Details: When a user clicks on a location marker, a popup appears showing detailed information about that location, including the building name, description, and an image (if available).
Quick Navigation: Users can quickly navigate to a specific location by clicking the corresponding button for that location, which automatically recenters the map on the location.
Using the Lost and Found Feature
Submitting a Lost or Found Item: Users can fill out the Lost and Found form to report an item they have lost or found. The form includes fields for item description, location, time, and whether the item is lost or found.
Viewing Lost and Found Items: Once submitted, the items are displayed in the corresponding "Lost Items" or "Found Items" sections. Each entry shows key details about the item and its location, helping users locate items that may have been lost or found in their vicinity.
Categorizing Items: The items are categorized and listed accordingly, ensuring that users can easily distinguish between lost and found items.

System Design and Architecture
Map Management
The map is built using Leaflet.js, a lightweight JavaScript library for interactive maps. The map is initialized with a default view and tile layer (using OpenStreetMap). Location markers are added dynamically based on the data provided, with each marker having an associated popup that displays detailed information.

Lost and Found Item Management
Lost and found items are stored in a list format, with each item associated with its location, description, and time of reporting. These items are categorized as "Lost" or "Found" and are displayed accordingly. When a user submits an item, it is validated and added to the relevant list.

User Interaction and Flow
The user experience is designed to be intuitive. The map allows for both free exploration and quick navigation to specific locations through buttons.
The Lost and Found feature ensures that reporting and browsing items is straightforward, with categories and easy-to-read lists.

Technical Details
Leaflet.js for Mapping
Leaflet is used to render the campus map. It provides features like:

Custom Markers: The ability to place custom markers on the map at specified locations.
Popups: Displaying additional information when a user clicks on a marker.
Tile Layer: OpenStreetMap tiles are used as the base layer for the map.
Form Handling
The Lost and Found form uses standard HTML form elements, with JavaScript responsible for validating the input and dynamically displaying submitted items in the relevant lists. Items are stored in the UI but could be expanded to be stored in a database for persistence.

Responsive Design and Accessibility
The application is designed to be mobile-friendly, adjusting the layout for smaller screens and providing a seamless user experience across different devices. The form and map are fully responsive, allowing users to interact with them comfortably whether they are using a smartphone, tablet, or desktop computer.

Additionally, the application follows accessibility best practices to ensure that users with disabilities can navigate the map and submit Lost and Found reports with ease. This includes:

Keyboard Navigation: All buttons and form elements are accessible via keyboard.
Screen Reader Compatibility: Text labels and descriptions are designed to work well with screen readers.

Conclusion
This Interactive Campus Map with the Lost and Found feature serves as a practical tool for campus navigation and community assistance. The map provides an engaging way for users to explore campus locations, while the Lost and Found feature facilitates the reporting and retrieval of lost or found items. The design is user-friendly, responsive, and built with accessibility in mind, making it an effective solution for both students and staff on campus.

