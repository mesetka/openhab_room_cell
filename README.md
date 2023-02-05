# openhab_room_cell
A widget to show room's temperature, humidity, lightlevel, co2, lights and so on.
My version of cell widget for rooms of my house, small cells will popup a bigger widget on click, giving more options and controls (from the smaller widget only light controls will popup if you’ll manage to click exactly on lightbulb button - that is made for faster access to the most used control).
Smaller widget will pass all options it has to the bigger one, so despite of the fact that smaller version doesn’t show all items which are passed to it, you’ll still need to fill in all those items you want to see in popup.
Widget is designed to fit dark and bright color themes, changing it’s colors depending of user theme, and is designed to provide clear view on background image, so it’s full off css shadows, and maybe if you don’t need/don’t like all those shadows, you should delete them in widget code to get a bit more of performance.
Widget’s remote control is designed for Samsung TV, using Samsung TV’s binding, so if your TV is different, you will not get all those keys working.
