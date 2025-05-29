Make a good and structured folder system in this folder to keep your files organized.

Example folder structure for organizing your images and animation sources:

Images/
├── UI/
│   ├── buttons/
│   ├── icons/
│   └── ...
├── Pets/
│   ├── cats/
│   │   ├── cat_1/
│   │   │   ├── size_default/
│   │   │   │   ├── cat_1_icon.png
│   │   │   │   ├── cat_1_idle.png
│   │   │   │   ├── cat_1_sprites.aseprite   # All cat_1 default size animations in one .aseprite file
│   │   │   │   └── ...
│   │   │   ├── size_closeup/
│   │   │   │   ├── cat_1_closeup.png
│   │   │   │   ├── cat_1_closeup_sprites.aseprite   # All closeup animations in one .aseprite file
│   │   │   │   └── ...
│   │   │   └── ...
│   │   └── ...
│   ├── dogs/
│   │   └── ...
│   └── ...
├── Scenes/
│   ├── home.png
│   ├── hotel.png
│   └── ...
├── Map/
│   ├── world-map.png
│   └── ...
└── ...