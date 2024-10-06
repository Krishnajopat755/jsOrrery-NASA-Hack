# jsOrrery

jsOrrery is a Solar System / orbital mechanics simulation, or orrery, that I wrote in WebGL and Javascript. The main feature of jsOrrery is that the planets positions are accurate in regards to the date you set, and it has the consequence that you can observe things that happen in the real Solar System.

project deployed at : https://js-orrery-nasa-hack.vercel.app/
linkedin : https://www.linkedin.com/in/krishna-jopat-7036ab314/

# Usage

The directory named `dist` contains the built app. The html file is an example of jsOrrery placed in a page. Basically, you link jsOrrery's js and css files in your HTML file and call the app.

As soon as jsOrrery is loaded, it calls a function `window.onJsOrreryLoaded` if it exists, with JSOrrery class as param. JSOrrery is also accessible through the global `window.jsOrrery` variable. To init the app, you just create a new instance.

```
const jsOrrery = new JSOrrery();
```

## Options

If you want to customize how jsOrrery behaves, you can pass a config object to its init method.

## Building the app

You can also use webpack to display the app in a local environment with `npm start`. To build the js, you can run webpack directly in the terminal, for example `env NODE_ENV=production webpack`.

# Resources

1. https://eyes.nasa.gov/apps/asteroids/#/home

2. https://nasa.github.io/mission-viz/X3Dom/20150611_WebBasedMissionVisualizationSystem.pdf

3. https://nasa.github.io/mission-viz/X3Dom/InnerSolarSystem.html

4. https://nasa.github.io/mission-viz/OntologyDrivenOrrery/An_Orrery_in_ThreeJS.html

5. https://nasa.github.io/mission-viz/RMarkdown/ontology_based_orrery_generated_from_R_code.html

6. https://nasa.github.io/mission-viz/RMarkdown/Elliptical_Orbit_Design.html

7. https://github.com/nasa/mission-viz

8. https://data.nasa.gov/Space-Science/Near-Earth-Comets-Orbital-Elements-API/ysqn-vd8v/about_data

9. https://ssd.jpl.nasa.gov/tools/sbdb_query.html

10. https://ssd.jpl.nasa.gov/planets/approx_pos.html




