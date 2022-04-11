# Chart.js, Canvas

- Charts are far better for displaying data visually than tables

- To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page.

- The great things about Chart.js are that it’s simple to use and really very flexible.
<!-- www.webdesignerdepot.com -->

- You can get the latest version of Chart.js from npm , the GitHub releases , or use a Chart.js CDN . Detailed installation instructions can be found on the installation page. All that's required is the script included in your page along with a single <canvas> node to render the chart.

<!-- www.chartjs.org/ -->

- A <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes.

- The <canvas> element can be styled just like any normal image. These rules, however, don't affect the actual drawing on the canvas.

- Unlike the <img> element, the <canvas> element requires the closing tag (</canvas>).

<!-- https://developer.mozilla.org/ -->

- A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

  - First, you create the path.
  - Then you use drawing commands to draw into the path.
  - Once the path has been created, you can stroke or fill the path to render it.

- beginPath() : Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

- Path methods: Methods to set different paths for objects.

- closePath(): Adds a straight line to the path, going to the start of the current sub-path.

- stroke(): Draws the shape by stroking its outline.

- fill(): Draws a solid shape by filling the path's content area.

<!-- developer.mozilla.org -->

- If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

- fillStyle = color : Sets the style used when filling shapes.

- strokeStyle = color : Sets the style for shapes outlines.

- globalAlpha = transparencyValue : Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.

- Patterns: 
  - repeat: Tiles the image in both vertical and horizontal directions.

- repeat-x: Tiles the image horizontally but not vertically.

- repeat-y: Tiles the image vertically but not horizontally.

- no-repeat: Doesn't tile the image. It's used only once.

<!-- developer.mozilla.org -->

- Drawing text: The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth]): Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

- strokeText(text, x, y [, maxWidth]): Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

- Styling texts:
  - font = value: The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

- textAlign = value: Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

  - textBaseline = value: Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

  - direction = value: Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.

  <!-- developer.mozilla.org -->