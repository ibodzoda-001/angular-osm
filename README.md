# angular-osm
Using osm in Angular project
1. Create `osm-view` component in your project.
2. Copy and paste `osm-view` component from repository to your project.
3. Install ngx-openlayers with `npm install ngx-openlayers --save`.
4. Call ans pass data to `osm-view` component and start using.

## Component parameters
Parameters, which you can pass to `osm-view` component.

| Property       | Type                | Description |
| ------------- |:------------------:| :------------------:|
| `changeLocation`    | `boolean`    | 
| `width`    | `string` |
| `height`  | `string`         |
| `latitude` | `number` |
| `longitude` | `number` |
| `latitude` | `number` |
| `longitudePointer` | `number` |
| `showControlsZoom` | `boolean` |
| `titleZoomIn` | `string = 'Zoom in'` |
| `titleZoomOut` | `string = 'Zoom out'` |
| `showControlsCurrentLocation` | `boolean` |
| `titleCurrentLocation` | `string = 'Current location'` |
| `showDebugInfo` | `boolean` |
| `opacity` | `number` | 
| `zoom` | `number` | 
 
 
Parameters, which can be emitted from component.
| Property       | Type                | Description |
| ------------- |:------------------:|:------------------:|
| `onMapCoordinatesChange`    | `any`    | 
| `addressChanged`  | `string`         |

