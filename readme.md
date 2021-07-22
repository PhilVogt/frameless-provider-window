### Simple example showing how to remove the frame on a provider window 
1) Install http-server globally
```
npm install --global http-server
```
2) Run
```
http-server -p 1234 -c -1
```
3) Open another command terminal and run
```
openfin -l -c app.json
```
4) Notice that the Provider window is shown and the frame is hidden (the frame is hidden via the "fame" flag in the manifest file). The location of the window is also automatically saved/restored (this is controlled with the "saveWindowState" flag).
