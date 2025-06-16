# iqs - Image Quick Sorter

Image Quick Sorter is a small GTK4 tool for injesting media into a year/month folder structure based on capture date and time. To sort media of different formats and with different date information, this tool allows date ambiguity to be quickly sorted for each media injested using keyboard shortcuts.

## Development Goals

- [ ] Create GTK4 layout in XML and form template application
- [ ] Create filesystem picker for input and output folders
- [ ] Create sqlite temp database for storing thumbnails and filesystem locations
- [ ] Create media injester to populate database
- [ ] Create media previewer
- [ ] Capture keyboard shortcuts and tie them to processing actions on images
- [ ] Create action queue (allow backspace to modify what the last image date selected was)
- [ ] Create summary screen for all images
