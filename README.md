# ZoomToExtent

ZoomToExtent does exactly what it says. It allows a user to draw the extent on their map in which they want to zoom to.

I got the idea, and majority of the code, of how to do it from the MapExtent project you can find here: https://github.com/ERS-Long/MapExtent

Viwer Configuration Settings:
```javascript
			ZoomToExtent: {
				include: true,
				id: 'ZoomToExtent',
				type: 'titlePane',
				canFloat: true,
				path: 'gis/dijit/ZoomToExtent',
				title: 'Zoom To Extent',
				position: 18,
				options: {
					map: true
				}
			},
```

 First Click on the zoom to extent button:
  
 ![Screenshot](./appscreenshots/ZoomToExtent.ButtonClick.png)
  
  Then select the area you want to zoom the map to
  
 ![Screenshot](./appscreenshots/ZoomToExtent.SelectArea.png)
  
  The map should now be zoomed to your desired extent
  
 ![Screenshot](./appscreenshots/ZoomToExtent.ZoomedPicture.png)
