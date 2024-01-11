 ### About this sample

This sample application uses the ArcGIS Maps SDK for JavaScript ES modules (ESM), also referred to as [`@arcgis/core`](https://www.npmjs.com/package/@arcgis/core). It uses a lightweight framework called [Vite.js](https://vitejs.dev/) to compile the application locally.

### Requirements

Be sure your machine has Node.js, npm and a webserver for testing of production builds. Refer to the SDK's [ES Modules guide topic](https://developers.arcgis.com/javascript/latest/es-modules/#prerequisites) for more information.

### Install

To install sample and its dependencies, run `npm install`.

### Run the sample

Run the sample by using `npm run dev`. This will compile the application and launch it in a browser window.


### Use the API to Create Your First 2D Map
As mentioned earlier, modifying existing sample code is a common way to begin learning a new programming language or API.  Thankfully, Esri offers a "sandbox" environment for experimenting with the samples found in their SDK.  Let's use this sandbox to start our work with the API.

1. On the SDK home page(link is external), click on the Sample Code tab.
Accessing the Sample Code area of the SDK

There you should see a list of Get started... samples.

2. Click on the Intro to MapView (2D) link. Like the other Samples pages, you should see a map embedded at the top of the page. Beneath the map, you should see buttons labeled Explore in the sandbox, Open in CodePen, View live and Download ESM sample.
Click the Open in CodePen button. CodePen shows you the same map you just saw at the bottom of the page and the source code that produces that map on the top. The size of the "Preview" panel can be adjusted by dragging the horizontal bar separating that panel from the source code panels up or down. The power of CodePen is the ability to modify the source code and quickly see the result.

CodePen is built to encourage the separation of HTML, CSS, and JS code (a good development practice) with separate panels for each.  However, note that it's OK to include CSS and JS in with the HTML, which is what happens when you open an Esri sample in CodePen.  

Also note that it's possible to reconfigure CodePen such that the code panels are on the left or right rather than on the top.  (I prefer having them on the left and the Preview panel on the right.)  Making this change is done by clicking the Change View button (found next to the Settings button).

The sample is coded so that the map is centered over Scandinavia at a zoom level of 4. What if you wanted to display the United States instead? That’s easy!

4. Modify line 30 (or thereabouts - as the documentation does occasionally get updated) so that the MapView’s center property is set to a lon/lat array of [-95, 40].  You should see that the Preview panel automatically updates as you edit the code.  I find this to be annoying when working on map pages, so I go into Settings > Behavior, and toggle the Auto-Updating Preview setting to off.  When making this setting, you'll need to click the Run button to see the result of your code changes.

Now, let’s say you wanted to use a different basemap.

5. Change line 23 so that the Map’s basemap property is set to "terrain" and again click the Run button. As you can see, the CodePen sandbox makes it very convenient to “play around” with the code samples.


### More information

For more information on using the ArGIS API for JavaScript with ES modules: https://developers.arcgis.com/javascript/latest/es-modules/#additional-information. 

For more samples using a variety of frameworks and module bundlers: https://github.com/Esri/jsapi-resources/tree/main/esm-samples. 

For more information on using the ArGIS API for JavaScript with TypeScript: https://developers.arcgis.com/javascript/latest/typescript-setup/. 

To learn more about Vite.js: https://vitejs.dev/guide/why.html. 
