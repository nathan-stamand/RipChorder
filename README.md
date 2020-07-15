# README

Welcome to RipChorder! This app makes it easy to hear chord progressions and make quick demos of songs when you don't have access to your instrument (or don't play one at all). Simply click 'New' to create a song, fill in the details for it (key, mode, title, etc.), and click the chords you want to add to your feeds. Feeds max out at 8 chords, 4 feeds. To remove a chord from a feed, simply click it and it will be removed. The next chord you add will be added to your next available feed space. To add custom chords, click the + button in the chord section, fill in the chord's details, and click 'Add Chord' to add a button for the chord. Click Save button to save your song's changes, and Clear to return to the instructions. Happy writing!

Ruby version: ruby 2.6.1p33

System dependencies: rails 6.0.3, fast_jsonAPI, rack-cors, Tone.js, jquery, Scribbletune.js

Database creation: type 'rails db:migrate' in ripchorder-backend terminal.

Database initialization: type 'rails s' in ripchorder-backend terminal to run the backend server.

Deployment instructions: Create/initialize database in ripchorder-backend. Navigate to ripchorder-frontend and type 'open index.html' in terminal, hit enter. This should open the webpage for Ripchorder. Follow the instructions at the orange section near the top of the page to use app.
