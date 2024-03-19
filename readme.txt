game.js - Dawson's Game Framework
Vaild for version 1.0

- Basic setup - 
You must include the JS script that came with this in the ZIP file in a script tag. This has to be done before the code you have written to work with the engine.
Canvas width and height must be set using HTML parameters not CSS.
Images used with the game must be in the HTML with an ID. This can be made invisible using CSS and the framework will still work.
All GameObjects must extend the GameObject class. DO NOT OVERWRITE THE CONSTRUCTOR.
The only thing required to be called for the game engine to run one frame is 'EngineLoop();'. Call this using an interval.
