# About
Web based implementation of my previous project that uses OpenCV's face recognition, modified to work on web

## Developer Notes:
  - Link to desktop app: https://github.com/akshay-sngh/face-recognition
  - This application only processes the face recognition responses on the server side and doesn't send the response back to the client.
  - Apologies in advance for dumping everything in the single master branch, didn't know what I was doing

## Changes from the GUI implementation:
  1. Add HTML front-end where users log in to the portal
  2. Add forms that allow users to add their details and submit their photo
  3. Create flask back-end to retrieves pixels and predicts the face
  4. Record the response in SQLite Database
  5. Display the recorded response real-time in the web portal

# Directory and files description
  - trainSet: Unprocessed images
  - dataSet: Images that have undergone preprocessing and used by the classifieer
  - recognizerData: YAML files used by OpenCV's recognizer
  - fonts: CSS fonts
  - EmployeeBase.db: Attendance store
