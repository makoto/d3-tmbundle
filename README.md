# D3.js Bundle for TextMate

This is a TextMate bundle for [D3.js](http://d3js.org)

<iframe width="420" height="315" src="http://www.youtube.com/embed/91zG4003m_0" frameborder="0" allowfullscreen></iframe>

- [Demo](http://www.youtube.com/embed/91zG4003m_0)

## Authors

* Makoto Inoue

## License

This bundle is under MIT.

* [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)


## Install

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/makoto/d3-tmbundle.git "JavaScript D3.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

## Snippets

### Generic Patterns

- viewport = Initial setup to append svg with width and height
- scales   = Adds scaling
- [join](http://bost.ocks.org/mike/join/)
- line/rect/circle
- color
- axis

### API

The snippet structure follows [the API page](https://github.com/mbostock/d3/wiki/API-Reference) as much as possible.

#### Selections
- select/selectAll

#### Transitions
- transitions

#### Importing External files

- json


### Quantitative Scale

- linear

### Ordinal Scale

- category

### SVG

- axis

## Template

- html = Boilerplate example with barchart 

## ToDo

Should I add all of them or only frequently used ones?

### Selections

- [event](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_event)
- [mouse](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_mouse)
- [touches](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_touches)

### Transitions

- [ease](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_ease)
- [timer](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_timer)
- [interpolate](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolate)

### Working with Arrays|Arrays

* d3.ascending|Arrays#wiki-d3_ascending - compare two values for sorting.
* d3.descending|Arrays#wiki-d3_descending - compare two values for sorting.
* d3.min|Arrays#wiki-d3_min - find the minimum value in an array.
* d3.max|Arrays#wiki-d3_max - find the maximum value in an array.
* d3.extent|Arrays#wiki-d3_extent - find the minimum and maximum value in an array.
* d3.sum|Arrays#wiki-d3_sum - compute the sum of an array of numbers.
* d3.mean|Arrays#wiki-d3_mean - compute the arithmetic mean of an array of numbers.
* d3.median|Arrays#wiki-d3_median - compute the median of an array of numbers (the 0.5-quantile).
* d3.quantile|Arrays#wiki-d3_quantile - compute a quantile for a sorted array of numbers.
* d3.bisect|Arrays#wiki-d3_bisect - search for a value in a sorted array.
* d3.bisectRight|Arrays#wiki-d3_bisectRight - search for a value in a sorted array.
* d3.bisectLeft|Arrays#wiki-d3_bisectLeft - search for a value in a sorted array.
* d3.first|Arrays#wiki-d3_first - find the lowest element in an array.
* d3.last|Arrays#wiki-d3_last - find the highest element in an array.
* d3.permute|Arrays#wiki-d3_permute - reorder an array of elements according to an array of indexes.
* d3.zip|Arrays#wiki-d3_zip - transpose a variable number of arrays.
* d3.transpose|Arrays#wiki-d3_transpose - transpose an array of arrays.
* d3.keys|Arrays#wiki-d3_keys - list the keys of an associative array.
* d3.values|Arrays#wiki-d3_values - list the values of an associated array.
* d3.entries|Arrays#wiki-d3_entries - list the key-value entries of an associative array.
* d3.split|Arrays#wiki-d3_split - split an array into multiple arrays.
* d3.merge|Arrays#wiki-d3_merge - merge multiple arrays into one array.
* d3.range|Arrays#wiki-d3_range - generate a range of numeric values.
* d3.nest|Arrays#wiki-d3_nest - group array elements hierarchically.
* nest.key|Arrays#wiki-nest_key - add a level to the nest hierarchy.
* nest.sortKeys|Arrays#wiki-nest_sortKeys - sort the current nest level by key.
* nest.sortValues|Arrays#wiki-nest_sortValues - sort the leaf nest level by value.
* nest.rollup|Arrays#wiki-nest_rollup - specify a rollup function for leaf values.
* nest.map|Arrays#wiki-nest_map - evaluate the nest operator, returning an associative array.
* nest.entries|Arrays#wiki-nest_entries - evaluate the nest operator, returning an array of key-values tuples.

### Math

* d3.random.normal|Math#wiki-random_normal - generate a random number with a normal distribution.
* d3.transform|Math#wiki-transform - compute the standard form of a 2D matrix transform.

### Loading External Resources|Requests

* d3.xhr|Requests#wiki-d3_xhr - request a resource using XMLHttpRequest.
* d3.text|Requests#wiki-d3_text - request a text file.
* d3.html|Requests#wiki-d3_html - request an HTML document fragment.
* d3.xml|Requests#wiki-d3_xml - request an XML document fragment.

### String Formatting|Formatting

* d3.format|Formatting#wiki-d3_format - format a number as a string.
* d3.requote|Formatting#wiki-d3_requote - quote a string for use in a regular expression.
* d3.round|Formatting#wiki-d3_round - rounds a value to some digits after the decimal point.

### CSV Formatting (d3.csv)|CSV

* d3.csv|CSV#wiki-csv - request a comma-separated values (CSV) file.
* d3.csv.parse|CSV#wiki-parse - parse a CSV string into objects using the header row.
* d3.csv.parseRows|CSV#wiki-parseRows - parse a CSV string into tuples, ignoring the header row.
* d3.csv.format|CSV#wiki-format - format an array of tuples into a CSV string.

### Colors

* d3.rgb|Colors#wiki-d3_rgb - specify a color in RGB space.
* rgb.brighter|Colors#wiki-rgb_brighter - increase RGB channels by some exponential factor (gamma).
* rgb.darker|Colors#wiki-rgb_darker - decrease RGB channels by some exponential factor (gamma).
* rgb.hsl|Colors#wiki-rgb_hsl - convert from RGB to HSL.
* rgb.toString|Colors#wiki-rgb_toString - convert an RGB color to a string.
* d3.hsl|Colors#wiki-d3_hsl - specify a color in HSL space.
* hsl.brighter|Colors#wiki-hsl_brighter - increase lightness by some exponential factor (gamma).
* hsl.darker|Colors#wiki-hsl_darker - decrease lightness by some exponential factor (gamma).
* hsl.rgb|Colors#wiki-hsl_rgb - convert from HSL to RGB.
* hsl.toString|Colors#wiki-hsl_toString - convert an HSL color to a string.

### Namespaces

* d3.ns.prefix|Namespaces#wiki-prefix - access or extend known XML namespaces.
* d3.ns.qualify|Namespaces#wiki-qualify - qualify a prefixed name, such as "xlink:href".

### Internals

* d3.functor|Internals#wiki-d3_functor - create a function that returns a constant.
* d3.rebind|Internals#wiki-d3_rebind - rebind an inherited getter/setter method to a subclass.
* d3.dispatch|Internals#wiki-d3_dispatch - create custom event dispatchers.
* dispatch.on|Internals#wiki-dispatch_on - register an event listener.
* dispatch|Internals#wiki-_dispatch - dispatch an event to registered listeners.

## Scales

### Quantitative|Quantitative-Scales#wiki-quantitative

* d3.scale.linear|Quantitative-Scales#wiki-linear - construct a linear quantitative scale.
* linear|Quantitative-Scales#wiki-_linear - get the range value corresponding to a given domain value.
* linear.invert|Quantitative-Scales#wiki-linear_invert - get the domain value corresponding to a given range value.
* linear.domain|Quantitative-Scales#wiki-linear_domain - get or set the scale's input domain.
* linear.range|Quantitative-Scales#wiki-linear_range - get or set the scale's output range.
* linear.rangeRound|Quantitative-Scales#wiki-linear_rangeRound - set the scale's output range, and enable rounding.
* linear.interpolate|Quantitative-Scales#wiki-linear_interpolate - get or set the scale's output interpolator.
* linear.clamp|Quantitative-Scales#wiki-linear_clamp - enable or disable clamping of the output range.
* linear.nice|Quantitative-Scales#wiki-linear_nice - extend the scale domain to nice round numbers.
* linear.ticks|Quantitative-Scales#wiki-linear_ticks - get representative values from the input domain.
* linear.tickFormat|Quantitative-Scales#wiki-linear_tickFormat - get a formatter for displaying tick values.
* linear.copy|Quantitative-Scales#wiki-linear_copy - create a new scale from an existing scale.
* d3.scale.sqrt|Quantitative-Scales#wiki-sqrt - construct a quantitative scale with a square root transform.
* d3.scale.pow|Quantitative-Scales#wiki-pow - construct a quantitative scale with an exponential transform.
* pow|Quantitative-Scales#wiki-_pow - get the range value corresponding to a given domain value.
* pow.invert|Quantitative-Scales#wiki-pow_invert - get the domain value corresponding to a given range value.
* pow.domain|Quantitative-Scales#wiki-pow_domain - get or set the scale's input domain.
* pow.range|Quantitative-Scales#wiki-pow_range - get or set the scale's output range.
* pow.rangeRound|Quantitative-Scales#wiki-pow_rangeRound - set the scale's output range, and enable rounding.
* pow.interpolate|Quantitative-Scales#wiki-pow_interpolate - get or set the scale's output interpolator.
* pow.clamp|Quantitative-Scales#wiki-pow_clamp - enable or disable clamping of the output range.
* pow.nice|Quantitative-Scales#wiki-pow_nice - extend the scale domain to nice round numbers.
* pow.ticks|Quantitative-Scales#wiki-pow_ticks - get representative values from the input domain.
* pow.tickFormat|Quantitative-Scales#wiki-pow_tickFormat - get a formatter for displaying tick values.
* pow.exponent|Quantitative-Scales#wiki-pow_exponent - get or set the exponent power.
* pow.copy|Quantitative-Scales#wiki-pow_copy - create a new scale from an existing scale.
* d3.scale.log|Quantitative-Scales#wiki-log - construct a quantitative scale with an logarithmic transform.
* log|Quantitative-Scales#wiki-_log - get the range value corresponding to a given domain value.
* log.invert|Quantitative-Scales#wiki-log_invert - get the domain value corresponding to a given range value.
* log.domain|Quantitative-Scales#wiki-log_domain - get or set the scale's input domain.
* log.range|Quantitative-Scales#wiki-log_range - get or set the scale's output range.
* log.rangeRound|Quantitative-Scales#wiki-log_rangeRound - set the scale's output range, and enable rounding.
* log.interpolate|Quantitative-Scales#wiki-log_interpolate - get or set the scale's output interpolator.
* log.clamp|Quantitative-Scales#wiki-log_clamp - enable or disable clamping of the output range.
* log.nice|Quantitative-Scales#wiki-log_nice - extend the scale domain to nice powers of ten.
* log.ticks|Quantitative-Scales#wiki-log_ticks - get representative values from the input domain.
* log.tickFormat|Quantitative-Scales#wiki-log_tickFormat - get a formatter for displaying tick values.
* log.copy|Quantitative-Scales#wiki-log_copy - create a new scale from an existing scale.
* d3.scale.quantize|Quantitative-Scales#wiki-quantize - construct a linear quantitative scale with a discrete output range.
* quantize|Quantitative-Scales#wiki-_quantize - get the range value corresponding to a given domain value.
* quantize.domain|Quantitative-Scales#wiki-quantize_domain - get or set the scale's input domain.
* quantize.range|Quantitative-Scales#wiki-quantize_range - get or set the scale's output range (as discrete values).
* quantize.copy|Quantitative-Scales#wiki-quantize_copy - create a new scale from an existing scale.
* d3.scale.quantile|Quantitative-Scales#wiki-quantile - construct a quantitative scale mapping to quantiles.
* quantile|Quantitative-Scales#wiki-_quantile - get the range value corresponding to a given domain value.
* quantile.domain|Quantitative-Scales#wiki-quantile_domain - get or set the scale's input domain (as discrete values).
* quantile.range|Quantitative-Scales#wiki-quantile_range - get or set the scale's output range (as discrete values).
* quantile.quantiles|Quantitative-Scales#wiki-quantile_quantiles - get the scale's quantile bin thresholds.
* quantile.copy|Quantitative-Scales#wiki-quantile_copy - create a new scale from an existing scale.
* d3.scale.identity|Quantitative-Scales#wiki-identity - construct a linear identity scale.
* identity|Quantitative-Scales#wiki-_identity - the identity function.
* identity.invert|Quantitative-Scales#wiki-_identity - equivalent to identity; the identity function.
* identity.domain|Quantitative-Scales#wiki-identity_domain - get or set the scale's domain and range.
* identity.range|Quantitative-Scales#wiki-identity_domain - equivalent to identity.domain.
* identity.ticks|Quantitative-Scales#wiki-identity_ticks - get representative values from the domain.
* identity.tickFormat|Quantitative-Scales#wiki-identity_tickFormat - get a formatter for displaying tick values.
* identity.copy|Quantitative-Scales#wiki-identity_copy - create a new scale from an existing scale.

### Ordinal|Ordinal-Scales#wiki-ordinal

* d3.scale.ordinal|Ordinal-Scales#wiki-ordinal - construct an ordinal scale.
* ordinal|Ordinal-Scales#wiki-_ordinal - get the range value corresponding to a given domain value.
* ordinal.domain|Ordinal-Scales#wiki-ordinal_domain - get or set the scale's input domain.
* ordinal.range|Ordinal-Scales#wiki-ordinal_range - get or set the scale's output range.
* ordinal.rangePoints|Ordinal-Scales#wiki-ordinal_rangePoints - divide a continuous output range for discrete points.
* ordinal.rangeBands|Ordinal-Scales#wiki-ordinal_rangeBands - divide a continuous output range for discrete bands.
* ordinal.rangeRoundBands|Ordinal-Scales#wiki-ordinal_rangeRoundBands - divide a continuous output range for discrete bands.
* ordinal.rangeBand|Ordinal-Scales#wiki-ordinal_rangeBand - get the discrete range band width.
* ordinal.rangeExtent|Ordinal-Scales#wiki-ordinal_rangeExtent - get the minimum and maximum values of the output range.
* ordinal.copy|Ordinal-Scales#wiki-ordinal_copy - create a new scale from an existing scale.

## [d3.svg (SVG)](SVG)

### Shapes|SVG-Shapes

* d3.svg.line|SVG-Shapes#wiki-line - create a new line generator.
* line|SVG-Shapes#wiki-_line - generate a piecewise linear curve, as in a line chart.
* line.x|SVG-Shapes#wiki-line_x - get or set the *x*-coordinate accessor.
* line.y|SVG-Shapes#wiki-line_y - get or set the *y*-coordinate accessor.
* line.interpolate|SVG-Shapes#wiki-line_interpolate - get or set the interpolation mode.
* line.tension|SVG-Shapes#wiki-line_tension - get or set the cardinal spline tension.
* [line.defined](SVG-Shapes#wiki-line_defined) - control whether the line is defined at a given point.
* d3.svg.line.radial|SVG-Shapes#wiki-line_radial - create a new radial line generator.
* line|SVG-Shapes#wiki-_line_radial - generate a piecewise linear curve, as in a polar line chart.
* line.radius|SVG-Shapes#wiki-line_radial_radius - get or set the *radius* accessor.
* line.angle|SVG-Shapes#wiki-line_radial_angle - get or set the *angle* accessor.
* [line.defined](SVG-Shapes#wiki-line_radial_defined) - control whether the line is defined at a given point.
* d3.svg.area|SVG-Shapes#wiki-area - create a new area generator.
* area|SVG-Shapes#wiki-_area - generate a piecewise linear area, as in an area chart.
* area.x|SVG-Shapes#wiki-area_x - get or set the *x*-coordinate accessors.
* area.x0|SVG-Shapes#wiki-area_x0 - get or set the *x0*-coordinate (baseline) accessor.
* area.x1|SVG-Shapes#wiki-area_x1 - get or set the *x1*-coordinate (topline) accessor.
* area.y|SVG-Shapes#wiki-area_y - get or set the *y*-coordinate accessors.
* area.y0|SVG-Shapes#wiki-area_y0 - get or set the *y0*-coordinate (baseline) accessor.
* area.y1|SVG-Shapes#wiki-area_y1 - get or set the *y1*-coordinate (topline) accessor.
* area.interpolate|SVG-Shapes#wiki-area_interpolate - get or set the interpolation mode.
* area.tension|SVG-Shapes#wiki-area_tension - get or set the cardinal spline tension.
* [area.defined](SVG-Shapes#wiki-area_defined) - control whether the area is defined at a given point.
* d3.svg.area.radial|SVG-Shapes#wiki-area_radial - create a new area generator.
* area|SVG-Shapes#wiki-_area_radial - generate a piecewise linear area, as in a polar area chart.
* area.radius|SVG-Shapes#wiki-area_radial_radius - get or set the *radius* accessors.
* area.innerRadius|SVG-Shapes#wiki-area_radial_innerRadius - get or set the inner *radius* (baseline) accessor.
* area.outerRadius|SVG-Shapes#wiki-area_radial_outerRadius - get or set the outer *radius* (topline) accessor.
* area.angle|SVG-Shapes#wiki-area_radial_angle - get or set the *angle* accessors.
* area.startAngle|SVG-Shapes#wiki-area_radial_startAngle - get or set the *angle* (baseline) accessor.
* area.endAngle|SVG-Shapes#wiki-area_radial_endAngle - get or set the *angle* (topline) accessor.
* [area.defined](SVG-Shapes#wiki-area_radial_defined) - control whether the area is defined at a given point.
* d3.svg.arc|SVG-Shapes#wiki-arc - create a new arc generator.
* arc|SVG-Shapes#wiki-_arc - generate a solid arc, as in a pie or donut chart.
* arc.innerRadius|SVG-Shapes#wiki-arc_innerRadius - get or set the inner radius accessor.
* arc.outerRadius|SVG-Shapes#wiki-arc_outerRadius - get or set the outer radius accessor.
* arc.startAngle|SVG-Shapes#wiki-arc_startAngle - get or set the start angle accessor.
* arc.endAngle|SVG-Shapes#wiki-arc_endAngle - get or set the end angle accessor.
* arc.centroid|SVG-Shapes#wiki-arc_centroid - compute the arc centroid.
* d3.svg.symbol|SVG-Shapes#wiki-symbol - create a new symbol generator.
* symbol|SVG-Shapes#wiki-_symbol - generate categorical symbols, as in a scatterplot.
* symbol.type|SVG-Shapes#wiki-symbol_type - get or set the symbol type accessor.
* symbol.size|SVG-Shapes#wiki-symbol_size - get or set the symbol size (in square pixels) accessor.
* d3.svg.chord|SVG-Shapes#wiki-chord - create a new chord generator.
* chord|SVG-Shapes#wiki-_chord - generate a quadratic Bézier connecting two arcs, as in a chord diagram.
* chord.radius|SVG-Shapes#wiki-chord_radius - get or set the arc radius accessor.
* chord.startAngle|SVG-Shapes#wiki-chord_startAngle - get or set the arc start angle accessor.
* chord.endAngle|SVG-Shapes#wiki-chord_endAngle - get or set the arc end angle accessor.
* chord.source|SVG-Shapes#wiki-chord_source - get or set the source arc accessor.
* chord.target|SVG-Shapes#wiki-chord_target - get or set the target arc accessor.
* d3.svg.diagonal|SVG-Shapes#wiki-diagonal - create a new diagonal generator.
* diagonal|SVG-Shapes#wiki-_diagonal - generate a two-dimensional Bézier connector, as in a node-link diagram.
* diagonal.source|SVG-Shapes#wiki-diagonal_source - get or set the source point accessor.
* diagonal.target|SVG-Shapes#wiki-diagonal_target - get or set the target point accessor.
* diagonal.projection|SVG-Shapes#wiki-diagonal_projection - get or set an optional point transform.
* d3.svg.diagonal.radial|SVG-Shapes#wiki-diagonal_radial - create a new diagonal generator.
* diagonal|SVG-Shapes#wiki-_diagonal_radial - generate a two-dimensional Bézier connector, as in a node-link diagram.


### Controls|SVG-Controls

* d3.svg.brush|SVG-Controls#wiki-brush
* brush|SVG-Controls#wiki-_brush
* brush.x|SVG-Controls#wiki-brush_x
* brush.y|SVG-Controls#wiki-brush_y
* brush.extent|SVG-Controls#wiki-brush_extent
* brush.clear|SVG-Controls#wiki-brush_clear
* brush.empty|SVG-Controls#wiki-brush_empty
* brush.on|SVG-Controls#wiki-brush_on

## [d3.time (Time)](Time)

### Time Formatting

* d3.time.format|Time-Formatting#wiki-format - create a new local time formatter for a given specifier.
* format|Time-Formatting#wiki-_format - format a date into a string.
* format.parse|Time-Formatting#wiki-parse - parse a string into a date.
* d3.time.format.utc|Time-Formatting#wiki-format_utc - create a new UTC time formatter for a given specifier.
* d3.time.format.iso|Time-Formatting#wiki-format_iso - the ISO 8601 UTC time formatter.

### Time Scales

* d3.time.scale|Time-Scales#wiki-scale - construct a linear time scale.
* scale|Time-Scales#wiki-_scale - get the range value corresponding to a given domain value.
* scale.invert|Time-Scales#wiki-invert - get the domain value corresponding to a given range value.
* scale.domain|Time-Scales#wiki-domain - get or set the scale's input domain.
* scale.range|Time-Scales#wiki-range - get or set the scale's output range.
* scale.rangeRound|Time-Scales#wiki-rangeRound - set the scale's output range, and enable rounding.
* scale.interpolate|Time-Scales#wiki-interpolate - get or set the scale's output interpolator.
* scale.clamp|Time-Scales#wiki-clamp - enable or disable clamping of the output range.
* scale.ticks|Time-Scales#wiki-ticks - get representative values from the input domain.
* scale.tickFormat|Time-Scales#wiki-tickFormat - get a formatter for displaying tick values.
* scale.copy|Time-Scales#wiki-copy - create a new scale from an existing scale.

### Time Intervals

* d3.time.interval|Time-Intervals#wiki-interval - a time interval in local time.
* interval|Time-Intervals#wiki-_interval - alias for interval.floor.
* interval.range|Time-Intervals#wiki-interval_range - returns dates within the specified range.
* interval.floor|Time-Intervals#wiki-interval_floor - rounds down to the nearest interval.
* interval.round|Time-Intervals#wiki-interval_round - rounds up or down to the nearest interval.
* interval.ceil|Time-Intervals#wiki-interval_ceil - rounds up to the nearest interval.
* interval.offset|Time-Intervals#wiki-interval_offset - returns a date offset by some interval.
* interval.utc|Time-Intervals#wiki-interval_utc - returns the UTC-equivalent time interval.
* d3.time.day|Time-Intervals#wiki-day - every day (12:00 AM).
* d3.time.days|Time-Intervals#wiki-day - alias for day.range.
* d3.time.hour|Time-Intervals#wiki-hour - every hour (e.g., 1:00 AM).
* d3.time.hours|Time-Intervals#wiki-hours - alias for hour.range.
* d3.time.minute|Time-Intervals#wiki-minute - every minute (e.g., 1:02 AM).
* d3.time.minutes|Time-Intervals#wiki-minutes - alias for minute.range.
* d3.time.month|Time-Intervals#wiki-month - every month (e.g., February 1, 12:00 AM).
* d3.time.months|Time-Intervals#wiki-months - alias for month.range.
* d3.time.second|Time-Intervals#wiki-second - every second (e.g., 1:02:03 AM).
* d3.time.seconds|Time-Intervals#wiki-seconds - alias for second.range.
* d3.time.sunday|Time-Intervals#wiki-sunday - every Sunday (e.g., February 5, 12:00 AM).
* d3.time.sundays|Time-Intervals#wiki-sundays - alias for sunday.range.
* d3.time.monday|Time-Intervals#wiki-monday - every Monday (e.g., February 5, 12:00 AM).
* d3.time.mondays|Time-Intervals#wiki-mondays - alias for monday.range.
* d3.time.tuesday|Time-Intervals#wiki-tuesday - every Tuesday (e.g., February 5, 12:00 AM).
* d3.time.tuesdays|Time-Intervals#wiki-tuesdays - alias for tuesday.range.
* d3.time.wednesday|Time-Intervals#wiki-wednesday - every Wednesday (e.g., February 5, 12:00 AM).
* d3.time.wednesdays|Time-Intervals#wiki-wednesdays - alias for wednesday.range.
* d3.time.thursday|Time-Intervals#wiki-thursday - every Thursday (e.g., February 5, 12:00 AM).
* d3.time.thursdays|Time-Intervals#wiki-thursdays - alias for thursday.range.
* d3.time.friday|Time-Intervals#wiki-friday - every Friday (e.g., February 5, 12:00 AM).
* d3.time.fridays|Time-Intervals#wiki-fridays - alias for friday.range.
* d3.time.saturday|Time-Intervals#wiki-saturday - every Saturday (e.g., February 5, 12:00 AM).
* d3.time.saturdays|Time-Intervals#wiki-saturdays - alias for saturday.range.
* d3.time.week|Time-Intervals#wiki-week - alias for sunday.
* d3.time.weeks|Time-Intervals#wiki-weeks - alias for sunday.range.
* d3.time.year|Time-Intervals#wiki-year - every year (e.g., January 1, 12:00 AM).
* d3.time.years|Time-Intervals#wiki-years - alias for year.range.

## [d3.layout (Layouts)](Layouts)

### Bundle|Bundle-Layout

* d3.layout.bundle|Bundle-Layout#wiki-bundle - construct a new default bundle layout.
* bundle|Bundle-Layout#wiki-_bundle - apply Holten's *hierarchical bundling* algorithm to edges.

### Chord|Chord-Layout

* d3.layout.chord|Chord-Layout#wiki-chord - produce a chord diagram from a matrix of relationships.
* chord.matrix|Chord-Layout#wiki-matrix - get or set the matrix data backing the layout.
* chord.padding|Chord-Layout#wiki-padding - get or set the angular padding between chord segments.
* chord.sortGroups|Chord-Layout#wiki-sortGroups - get or set the comparator function for groups.
* chord.sortSubgroups|Chord-Layout#wiki-sortSubgroups - get or set the comparator function for subgroups.
* chord.sortChords|Chord-Layout#wiki-sortChords - get or set the comparator function for chords (z-order).
* chord.chords|Chord-Layout#wiki-chords - retrieve the computed chord angles.
* chord.groups|Chord-Layout#wiki-groups - retrieve the computed group angles.

### Cluster|Cluster-Layout

* d3.layout.cluster|Cluster-Layout#wiki-cluster - cluster entities into a dendrogram.
* cluster.sort|Cluster-Layout#wiki-sort - get or set the comparator function for sibling nodes.
* cluster.children|Cluster-Layout#wiki-children - get or set the accessor function for child nodes.
* cluster.nodes|Cluster-Layout#wiki-nodes - compute the cluster layout and return the array of nodes.
* cluster.links|Cluster-Layout#wiki-links - compute the parent-child links between tree nodes.
* cluster.separation|Cluster-Layout#wiki-separation - get or set the spacing function between neighboring nodes.
* cluster.size|Cluster-Layout#wiki-size - get or set the layout size in *x* and *y*.

### Force|Force-Layout

* d3.layout.force|Force-Layout#wiki-force - position linked nodes using physical simulation.
* force.on|Force-Layout#wiki-on - listen to updates in the computed layout positions.
* force.nodes|Force-Layout#wiki-nodes - get or set the array of nodes to layout.
* force.links|Force-Layout#wiki-links - get or set the array of links between nodes.
* force.size|Force-Layout#wiki-size - get or set the layout size in *x* and *y*.
* force.linkDistance|Force-Layout#wiki-linkDistance - get or set the link distance.
* force.linkStrength|Force-Layout#wiki-linkStrength - get or set the link strength.
* force.friction|Force-Layout#wiki-friction - get or set the friction coefficient.
* force.charge|Force-Layout#wiki-charge - get or set the charge strength.
* force.gravity|Force-Layout#wiki-gravity - get or set the gravity strength.
* force.theta|Force-Layout#wiki-theta - get or set the accuracy of the charge interaction.
* force.start|Force-Layout#wiki-start - start or restart the simulation when the nodes change.
* force.resume|Force-Layout#wiki-resume - reheat the cooling parameter and restart simulation.
* force.stop|Force-Layout#wiki-stop - immediately terminate the simulation.
* force.alpha|Force-Layout#wiki-alpha - get or set the layout's cooling parameter.
* force.tick|Force-Layout#wiki-tick - run the layout simulation one step.
* force.drag|Force-Layout#wiki-drag - bind a behavior to nodes to allow interactive dragging.

### Hierarchy|Hierarchy-Layout

* d3.layout.hierarchy|Hierarchy-Layout#wiki-hierarchy - derive a custom hierarchical layout implementation.
* hierarchy.sort|Hierarchy-Layout#wiki-sort - get or set the comparator function for sibling nodes.
* hierarchy.children|Hierarchy-Layout#wiki-children - get or set the accessor function for child nodes.
* hierarchy.nodes|Hierarchy-Layout#wiki-nodes - compute the layout and return the array of nodes.
* hierarchy.links|Hierarchy-Layout#wiki-links - compute the parent-child links between tree nodes.
* hierarchy.value|Hierarchy-Layout#wiki-value - get or set the value accessor function.
* hierarchy.revalue|Hierarchy-Layout#wiki-revalue - recompute the hierarchy values.

### Histogram|Histogram-Layout

* d3.layout.histogram|Histogram-Layout#wiki-histogram - construct a new default histogram layout.
* histogram|Histogram-Layout#wiki-_histogram - compute the distribution of data using quantized bins.
* histogram.value|Histogram-Layout#wiki-value - get or set the value accessor function.
* histogram.range|Histogram-Layout#wiki-range - get or set the considered value range.
* histogram.bins|Histogram-Layout#wiki-bins - specify how values are organized into bins.
* histogram.frequency|Histogram-Layout#wiki-frequency - compute the distribution as counts or probabilities.

### Pack|Pack-Layout

* d3.layout.pack|Pack-Layout#wiki-pack - produce a hierarchical layout using recursive circle-packing.
* pack.sort|Pack-Layout#wiki-sort - control the order in which sibling nodes are traversed.
* pack.children|Pack-Layout#wiki-children - get or set the children accessor function.
* pack.nodes|Pack-Layout#wiki-nodes - compute the pack layout and return the array of nodes.
* pack.links|Pack-Layout#wiki-links - compute the parent-child links between tree nodes.
* pack.value|Pack-Layout#wiki-value - get or set the value accessor used to size circles.
* pack.size|Pack-Layout#wiki-size - specify the layout size in *x* and *y*.

### Partition|Partition-Layout

* d3.layout.partition|Partition-Layout#wiki-partition - recursively partition a node tree into a sunburst or icicle.
* partition.sort|Partition-Layout#wiki-sort - control the order in which sibling nodes are traversed.
* partition.children|Partition-Layout#wiki-children - get or set the children accessor function.
* partition.nodes|Partition-Layout#wiki-nodes - compute the partition layout and return the array of nodes.
* partition.links|Partition-Layout#wiki-links - compute the parent-child links between tree nodes.
* partition.value|Partition-Layout#wiki-value - get or set the value accessor used to size circles.
* partition.size|Partition-Layout#wiki-size - specify the layout size in *x* and *y*.

### Pie|Pie-Layout

* d3.layout.pie|Pie-Layout#wiki-pie - construct a new default pie layout.
* pie|Pie-Layout#wiki-_pie - compute the start and end angles for arcs in a pie or donut chart.
* pie.value|Pie-Layout#wiki-value - get or set the value accessor function.
* pie.sort|Pie-Layout#wiki-sort - control the clockwise order of pie slices.
* pie.startAngle|Pie-Layout#wiki-startAngle - get or set the overall start angle of the pie.
* pie.endAngle|Pie-Layout#wiki-endAngle - get or set the overall end angle of the pie.

### Stack|Stack-Layout

* d3.layout.stack|Stack-Layout#wiki-stack - construct a new default stack layout.
* stack|Stack-Layout#wiki-_stack - compute the baseline for each series in a stacked bar or area chart.
* stack.values|Stack-Layout#wiki-values - get or set the values accessor function per series.
* stack.order|Stack-Layout#wiki-order - control the order in which series are stacked.
* stack.offset|Stack-Layout#wiki-offset - specify the overall baseline algorithm.
* stack.x|Stack-Layout#wiki-x - get or set the *x*-dimension accessor function.
* stack.y|Stack-Layout#wiki-y - get or set the *y*-dimension accessor function.
* stack.out|Stack-Layout#wiki-out - get or set the output function for storing the baseline.

### Tree|Tree-Layout

* d3.layout.tree|Tree-Layout#wiki-tree - position a tree of nodes tidily.
* tree.sort|Tree-Layout#wiki-sort - control the order in which sibling nodes are traversed.
* tree.children|Tree-Layout#wiki-children - get or set the children accessor function.
* tree.nodes|Tree-Layout#wiki-nodes - compute the tree layout and return the array of nodes.
* tree.links|Tree-Layout#wiki-links - compute the parent-child links between tree nodes.
* tree.separation|Tree-Layout#wiki-separation - get or set the spacing function between neighboring nodes.
* tree.size|Tree-Layout#wiki-size - specify the layout size in *x* and *y*.

### Treemap|Treemap-Layout

* d3.layout.treemap|Treemap-Layout#wiki-treemap - use recursive spatial subdivision to display a tree of nodes.
* treemap.sort|Treemap-Layout#wiki-sort - control the order in which sibling nodes are traversed.
* treemap.children|Treemap-Layout#wiki-children - get or set the children accessor function.
* treemap.nodes|Treemap-Layout#wiki-nodes - compute the treemap layout and return the array of nodes.
* treemap.links|Treemap-Layout#wiki-links - compute the parent-child links between tree nodes.
* treemap.value|Treemap-Layout#wiki-value - get or set the value accessor used to size treemap cells.
* treemap.size|Treemap-Layout#wiki-size - specify the layout size in *x* and *y*.
* treemap.round|Treemap-Layout#wiki-round - enable or disable rounding to exact pixels.
* treemap.sticky|Treemap-Layout#wiki-sticky - make the layout sticky for stable updates.

## d3.geo (Geography)|Geo

### Paths|Geo-Paths

* d3.geo.path|Geo-Paths#wiki-path - create a new geographic path generator.
* path|Geo-Paths#wiki-_path - generate the path data string for a given geographic feature.
* path.pointRadius|Geo-Paths#wiki-pointRadius - get or set the radius to display point features.
* path.projection|Geo-Paths#wiki-projection - get or set the geographic projection.
* path.area|Geo-Paths#wiki-area - compute the projected area of a given feature.
* path.centroid|Geo-Paths#wiki-centroid - compute the projected centroid of a given feature.
* d3.geo.bounds|Geo-Paths#wiki-bounds - compute the latitude-longitude bounding box for a given feature.
* d3.geo.greatArc|Geo-Paths#wiki-greatArc - approximate the shortest path between two points.
* greatArc|Geo-Paths#wiki-_greatArc - generate a GeoJSON LineStream.
* greatArc.distance|Geo-Paths#wiki-greatArc_distance - computes the great circle distance, in radians.
* greatArc.source|Geo-Paths#wiki-greatArc_source - specify a source accessor.
* greatArc.target|Geo-Paths#wiki-greatArc_target - specify a target accessor.
* greatArc.precision|Geo-Paths#wiki-greatArc_precision - specify the precision of the piecewise arc.
* d3.geo.greatCircle|Geo-Paths#wiki-circle - an alias for * d3.geo.circle|Geo-Paths#wiki-circle.
* d3.geo.circle|Geo-Paths#wiki-circle - clip features to a circle with arbitrary radius and origin.
* circle.origin|Geo-Paths#wiki-circle_origin - specify the origin in latitude and longitude.
* circle.angle|Geo-Paths#wiki-circle_angle - specify the angular radius in degrees.
* circle.precision|Geo-Paths#wiki-circle_precision - specify the precision of the piecewise circle.
* circle.clip|Geo-Paths#wiki-circle_clip - clip the given GeoJSON object.

### Projections|Geo-Projections

* d3.geo.mercator|Geo-Projections#wiki-mercator - construct a new spherical Mercator projection.
* mercator|Geo-Projections#wiki-_mercator - project the specified position.
* mercator.scale|Geo-Projections#wiki-mercator_scale - get or set the projection's scale factor.
* mercator.translate|Geo-Projections#wiki-mercator_translate - get or set the projection's translate offset.
* d3.geo.albers|Geo-Projections#wiki-albers - construct a new Albers equal-area conic projection.
* albers|Geo-Projections#wiki-_albers - project the specified position.
* albers.origin|Geo-Projections#wiki-albers_origin - get or set the projection's origin.
* albers.parallels|Geo-Projections#wiki-albers_parallels - get or set the projection's two standard parallels.
* albers.scale|Geo-Projections#wiki-albers_scale - get or set the projection's scale factor.
* albers.translate|Geo-Projections#wiki-albers_translate - get or set the projection's translate offset.
* d3.geo.albersUsa|Geo-Projections#wiki-albersUsa - construct a new composite Albers projection for the United States.
* albersUsa|Geo-Projections#wiki-_albersUsa - project the specified position.
* albersUsa.scale|Geo-Projections#wiki-albersUsa_scale - get or set the projection's scale factor.
* albersUsa.translate|Geo-Projections#wiki-albersUsa_translate - get or set the projection's translate offset.
* d3.geo.azimuthal|Geo-Projections#wiki-azimuthal - construct a new Azimuthal (orthographic or stereographic) projection.
* azimuthal|Geo-Projections#wiki-_azimuthal - project the specified position.
* azimuthal.mode|Geo-Projections#wiki-azimuthal_mode - get or set the projection's mode (orthographic or stereographic).
* azimuthal.origin|Geo-Projections#wiki-azimuthal_origin - get or set the projection's origin.
* azimuthal.scale|Geo-Projections#wiki-azimuthal_scale - get or set the projection's scale factor.
* azimuthal.translate|Geo-Projections#wiki-azimuthal_translate - get or set the projection's translate offset.

## d3.geom (Geometry)|Geom

### Voronoi|Voronoi-Geom

* d3.geom.voronoi|Voronoi-Geom#wiki-voronoi
* d3.geom.delaunay|Voronoi-Geom#wiki-delaunay

### Quadtree|Quadtree-Geom

* d3.geom.quadtree|Quadtree-Geom#wiki-quadtree
* quadtree.visit|Quadtree-Geom#wiki-visit

### Polygon|Polygon-Geom

* d3.geom.polygon|Polygon-Geom#wiki-polygon
* polygon.area|Polygon-Geom#wiki-area
* polygon.centroid|Polygon-Geom#wiki-centroid
* polygon.clip|Polygon-Geom#wiki-clip

### Hull|Hull-Geom

* d3.geom.hull|Hull-Geom#wiki-hull

### Contour|Contour-Geom

* d3.geom.contour|Contour-Geom#wiki-contour

## d3.behavior (Behaviors)|Behaviors

### Drag|Drag-Behavior

* d3.behavior.drag|Drag-Behavior#wiki-drag
* drag.on|Drag-Behavior#wiki-on

### Zoom|Zoom-Behavior

* d3.behavior.zoom|Zoom-Behavior#wiki-zoom
* zoom.on|Zoom-Behavior#wiki-on
* zoom.extent|Zoom-Behavior#wiki-extent