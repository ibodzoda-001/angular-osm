# angular-osm
Using osm in Angular project
1. Create `osm-view` component in your project.
2. Copy and paste `osm-view` component from repository to your project.
3. Install ngx-openlayers with `npm install ngx-openlayers --save`.
4. Call ans pass data to `osm-view` component and start using.

## Component parameters
Parameters, which you can pass to `osm-view` component.
```javascript
  @Input()
  changeLocation: boolean;

  @Input()
  width: string;
  @Input()
  height: string;

  @Input()
  latitude: number;
  @Input()
  longitude: number;

  @Input()
  latitudePointer: number;
  @Input()
  longitudePointer: number;

  @Input()
  showControlsZoom: boolean;
  @Input()
  titleZoomIn = 'Zoom in';
  @Input()
  titleZoomOut = 'Zoom out';
  @Input()
  showControlsCurrentLocation: boolean;
  @Input()
  titleCurrentLocation = 'Current location';

  @Input()
  showDebugInfo: boolean;
  @Input()
  opacity = 1;
  @Input()
  zoom = 14;

  @Output() onMapCoordinatesChange = new EventEmitter<any>();

  @Output()
  addressChanged = new EventEmitter<string>();
```
