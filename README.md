# Microsoft Power BI visuals plus custom visuals by MAQ Software

The Microsoft Power BI visuals project provides high quality data visualizations that you can use to extend [Power BI](https://powerbi.microsoft.com/).  The project contains over 20 visualization types plus custom visuals by MAQ Software, the framework to run them, and the testing infrastructure that enables you to build high quality visualizations.  The framework provides all the interfaces you need to integrate fully with Power BI's selection, filtering, and other UI experiences.  The code is written in [TypeScript](http://www.typescriptlang.org/) so it's easier to build and debug. Everything compiles down to JavaScript and runs in modern web browsers.  The visuals are built using [D3](http://d3js.org/) but you can use your favorite technology like [WebGL](https://en.wikipedia.org/wiki/WebGL), [Canvas](https://en.wikipedia.org/wiki/Canvas_element), or [SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics). This gives you everything you need to build custom visualizations for Power BI.


# Custom Visuals

<br />
<br />

| [Circular Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/CircularGauge/src/visual.ts)   |       [Linear Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/LinearGauge/src/visual.ts)     |   [Brick Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/BrickChart/src/visual.ts)  |
|----------|---------|------|
|<img src="https://maqsoftware.com/img/PowerBI/Circular_Gauge.png" alt="Circular Gauge" height="268" width="268"><br />Illustrates progress toward <br />goals in either a pie or <br />donut chart format. One color <br />illustrates current progress, <br />the other displays the <br />target. The percentage <br />displayed on the report <br />tracks progress against the <br />target. Text size and ring <br />size are customizable. <br /><br /><br /><br /><br /><br /><br /><br />  | <img src="https://maqsoftware.com/img/PowerBI/Linear_Gauge.png" alt="Linear Gauge" height="268" width="268"><br /> Create at-a-glance <br />visualization to compare your <br />progress against identified <br />goals and warning zones. This <br />visual allows you to include <br />multiple data points. The <br />component provides the <br />ability to illustrate trend <br />details such as monthly or <br />year-to-date completion <br />rates. The pointer notes <br />targets, and the colored bar <br />shows the current progress <br />toward those goals. Best <br />suited for showing progress as <br />compared to a target. <br /><br /> | <img src="https://maqsoftware.com/img/PowerBI/Brick_Chart.png" alt="Brick Chart" height="268" width="268"><br />Consists of 100 squares that <br />are colored according to the <br />percentage breakdown of <br />datasets. Hovering your mouse <br />over a square brings up a <br />tooltip. The tooltip <br />indicates which dataset the <br />color represents and the <br />percentage value of the <br />category. An optional legend <br />above the chart identifies <br />which datasets correspond <br />with which colors. You may <br />tailor the legend's title, <br />size, and color. They may also <br />customize the chart's width <br />and height. |


<br />
<br />


| [Trading Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/TradingChart/src/visual.ts)   |      [Bowtie Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/BowtieChart/src/visual.ts)     |  [Horizontal Funnel](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/HorizontalFunnel/src/visual.ts) |
|----------|------------|------|
| <img src="https://maqsoftware.com/img/PowerBI/Stock_Chart.png" alt="Stock Chart" height="268" width="268"> <br /> Displays significant stock <br />price points as colored <br />vertical bars. Low and high <br />price values are represented <br />by grey bars. Open and close <br />price values are shown as <br />either red or green bars, <br />which are superimposed over <br />the low and high values. If a <br />stock's price drops, the bar <br />is red; if the price rises <br />the bar is green. Prices are <br />listed on the vertical axis <br />and time increments are <br />listed on the horizontal <br />axis. The ranges for prices <br />and time increments are <br />customizable. | <img src="https://maqsoftware.com/img/PowerBI/Bowtie_Chart.png" alt="Bowtie Chart" height="268" width="268"><br/>Displays the categorization of <br />an aggregated value by <br />branching out smooth <br />interpolated nodes. The <br />thickness of the branch <br />indicates the weight of the <br />category. You can display a <br />half bowtie or full bowtie by <br />providing the source category <br />or the source and destination <br />categories, respectively. <br /><br /><br /><br /><br /><br /><br /><br />  | <img src="https://maqsoftware.com/img/PowerBI/Horizontal_Funnel.png" alt="Horizontal Funnel" height="268" width="268"> <br /> Allows you to visualize <br />customizable primary measure <br />as colored bars. You can use <br />Horizontal Funnel to display <br />a variety of metrics <br />including sales stages, time, <br />or geographic locations. A <br />second customizable value is <br />displayed beneath the colored <br />bars, allowing users the <br />ability to track an <br />additional metric against the <br />primary measure. The <br />component includes the option <br />to create a tool tip, which <br />you may tailor to fit <br />specific needs. <br /><br /> |

<br />
<br />

| [Ring Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/RingChart/src/visual.ts)   |      [JSON Grid](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/JSONGrid/src/visual.ts)     |  [Thermometer](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/Thermometer/src/visual.ts) |
|----------|------------|------|
| <img src="https://maqsoftware.com/img/PowerBI/Ring_Chart.png" alt="Donut Chart" height="268" width="268"> <br/>Represents data as slices, <br />where sizes are relative to <br />data. The size of each slice <br />is determined by the slice <br />value relative to the sum of <br />the values of all slices. <br />Each data series that you <br />plot in the chart adds a ring <br />to the chart. The rings have <br />different colors for easy <br />representation of the data <br />slices in the chart. <br />Key features:<br/>1. Ability to turn on <br />animation to focus on <br />specific slices. The <br />animation visually pulls <br />slices out of the ring chart. <br />2. Dynamic indicator displayed <br />along with the summary at the <br />center of ring. Threshold <br />values define the color and <br />direction of the indicator. <br />3. Ability to display primary <br />and secondary measures in <br />legends with indicators. <br />4. Ability to showcase <br />multiple data fields in <br />tooltips. | <img src="https://maqsoftware.com/img/PowerBI/Grid.png" alt="Grid" height="268" width="268"> <br/>Easy to use control with <br />pagination, sorting, and GET <br />Rest API call functionality. <br />Grid allows you to add a <br />paginated grid to a report <br />and specify the default sort <br />column and sort order for the <br />grid. It also allows you to <br />call an API on any additional <br />column if further processing <br />needs to be done. <br />Want to have a grid with a <br />pagination feature? Want to <br />have a grid which supports <br />calling APIs? <br />If yes, you can use Grid Power <br />BI custom visual. <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />  | <img src="https://maqsoftware.com/img/PowerBI/Thermometer.png" alt="Thermometer" height="268" width="268"> <br/>Shows a graphical <br />representation of a value <br />against a threshold. Allows <br />you to configure threshold <br />values and render data per <br />the threshold. Thermometer is <br />a good way to represent data <br />when you have the actual <br />value and the target value <br />(maximum threshold). <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />|


<br />
<br />

| [Text Wrapper](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/TextWrapper/src/visual.ts) |     [KPI Column](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/KPIColumn/src/barChart.ts)     |    [KPI Grid](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/KPIGrid/src/visual.ts)  |
|--------|------------|------|
| <img src="https://maqsoftware.com/img/PowerBI/Text_Wrapper.png" alt="Text wrapper" height="268" width="268"> <br/>Wraps a static text string <br />(statement) along with a <br />dynamic text field value. The <br />dynamic field value updates <br />according to the selected <br />filter/slicer, keeping the <br />static text intact. The user <br />needs to provide the static <br />string, which will be <br />appended as ": <>" after <br />the dynamic field value in <br />the visual, resulting in the <br />final value in the <br />visual as: "<> : <>" <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /> |  <img src="https://maqsoftware.com/img/PowerBI/KPI_Column.png" alt="KPI Column" height="268" width="268"> <br/>Column chart where each column <br />behaves as an indicator when <br />compared with a line. Column <br />color updates dynamically <br />based on the difference in <br />column height and respective <br />target line value. Adding <br />common threshold value exists <br />for all columns. For upcoming <br />values, the same target line <br />can be used for forecasting <br />and the column is displayed <br />in a translucent color to <br />indicate forecasted values. <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /> | <img src="https://maqsoftware.com/img/PowerBI/KPI_Grid.png" alt="KPI Grid" height="268" width="268"> <br/>Display data in hierarchical <br />order, with options to <br />separate categories and <br />illustrate trends. <br />Effortlessly track <br />productivity and performance. <br />The grid displays key data in <br />hierarchical order. <br />Use arrows to illustrate KPI <br />trends over time, such as <br />year-to-year or <br />quarter-to-quarter. You <br />specify the time periods, <br />making it easy to gauge <br />performance according to <br />internal deadlines and <br />benchmarks. <br />KPI Grid includes the option <br />to place separators between <br />certain columns. Using this <br />feature, you can visually <br />draw out categories that you <br />would like to compare or <br />emphasize. <br />With KPI Grid's numerous <br />formatting choices, you can <br />customize your text, <br />background, and units. Tailor <br />the look and feel of your <br />visual by updating rows' <br />background colors or text <br />size and color. Easily call <br />attention to headers and <br />totals by creating first and <br />last rows that are visually <br />distinct from the rest of the <br />grid. |

<br />
<br />

| [Journey Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/JourneyChart/src/visual.ts)   |     [Dynamic Tooltip](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/DynamicTooltip/src/visual.ts)      |   [Rotating Tile](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/RotatingTile/src/visual.ts)  |
|----------|------------|------|
| <img src="https://maqsoftware.com/img/PowerBI/Journey_Chart.png" alt="Journey Chart" height="268" width="268"> <br/>Transforms dense statistical <br />data into clear networks of <br />categories and relationships. <br />Reveal connections in your <br />data with a storytelling <br />visual. In this intuitive <br />graph, nodes represent <br />categories and vertices <br />represent relationships <br />between categories. The <br />bigger the node or vertex, the <br />larger the value. <br />Journey Chart's customizable <br />node colors make it easy for <br />viewers to distinguish <br />between categories. Users can <br />also enable text labels and <br />tooltips for each node to <br />provide additional <br />information, such as a <br />category's title and value. <br />The color and size of text <br />labels are adjustable. The <br />option to enable a legend <br />gives you the opportunity to <br />clarify complex graphs that <br />describe many types of data <br />and categories. <br />You can use the visual for <br />numerous scenarios, including: <br />1. Explaining a process' flow <br />2. Uncovering underlying <br />patterns <br />3. Highlighting subcategories <br />stemming from a single source<br />4. Showing the connectedness <br />of key categories <br /> | <img src="https://maqsoftware.com/img/PowerBI/Dynamic_Tooltip.png" alt="Dynamic Tooltip" height="268" width="268"> <br/>Increase your audience's <br />understanding of your data by <br />adding tooltips to your <br />visuals. Most tooltips <br />display static information or <br />images. With this visual, you <br />can display data fetched from <br />a separate source. This <br />allows you to create a <br />tooltip that does not require <br />constant adjustment. When <br />your data changes, the tooltip <br />changes too. <br />Dynamic Tooltip also works <br />well with static statements. <br />If you would like to add some <br />helpful information for your <br />audience, simply enter your <br />text into the display field. <br />The decimal points, type of <br />display units, and the <br />tooltip's icon image are all <br />customizable. <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /> | <img src="https://maqsoftware.com/img/PowerBI/Rotating_Tile.png" alt="Rotating Tile" height="268" width="268"> <br/>Automatically flipping tile <br />with a set frequency that can <br />be used to display different <br />KPIs. Useful when multiple <br />KPIs or metrics need to be <br />displayed using minimal space <br />on report. <br />Each flip of the rotating tile <br />can have a new value based on <br />number of KPIs that needs to <br />be displayed. Based on the <br />space requirements of the <br />report, the tile can be <br />rotated either on horizontal <br />axis or vertical axis. For <br />better visibility and to <br />ensure the end user can <br />browse the tile data <br />conveniently, a timer can be <br />set for the flip delay. <br />Additionally, Rotating Tile <br />has an option to provide a 3D <br />effect. <br />Rotating Tile has size and <br />color formatting options for <br />label, title, text fonts, <br />background, and borders. <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /> |

<br />
<br /> 

| [Rotating Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/RotatingChart/src/barChart.ts)   |     [Quadrant Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/QuadrantChart/src/visual.ts)      |   [Cylindrical Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/CylindricalGauge/src/visual.ts)  |
|----------|------------|------|
| <img src="https://maqsoftware.com/img/PowerBI/Rotating_Chart.png" alt="Rotating Chart" height="268" width="268"> <br/>Automatically flipping chart <br />with a set frequency to <br />display different KPIs with <br />each flip. This horizontal <br />bar chart rotates on the <br />horizontal axis to showcase <br />multiple KPIs with each flip <br />or rotation. Rotating Chart <br />is useful when multiple KPIs <br />or metrics sliced by <br />categories are to be <br />displayed. It uses minimal <br />space, thus saving room on the <br />report or dashboard. <br />Each flip can have a new value <br />based on the number of KPIs <br />that need to be displayed. <br />For better visibility and to <br />ensure the end user can <br />browse the visual data <br />conveniently, a timer can be <br />set for the visual for the <br />flip or rotation delay. <br />Rotating Chart has size and <br />color formatting options for <br />label, title, text fonts, <br />background, and borders. <br /><br /><br /><br />  | <img src="https://maqsoftware.com/img/PowerBI/Quadrant_Chart.png" alt="Quadrant Chart" height="268" width="268"><br /> Represent data in separate <br />quadrants to show <br />distribution of data and <br />items that share common <br />traits. This visual is useful <br />for plotting data that <br />contains three measures using <br />an X-axis, a Y-axis, and a <br />bubble size that represents <br />the value of the third measure. <br />The formatting options below <br />are provided for the visual: <br />1. Set color of each bubble. <br />2. Legends setting: on/off, <br />position, title, color and <br />text size. <br />3. Formatting option for <br />quadrants and quadrant lines: <br />four Quadrant names, X-Axis <br />division line, Y-Axis <br />division line and <br />Dotted/solid. <br />4. Formatting option for <br />X-Axis: title, title text, <br />labels, display units and <br />decimal points. <br />5. Formatting option for <br />Y-Axis: title, title text, <br />labels, display units and <br />decimal points. | <img src="https://maqsoftware.com/img/PowerBI/Cylindrical_Gauge.png" alt="Rotating Chart" height="268" width="268"> <br/>Tracks current values against <br />a target with an intuitive 3D <br />cylinder visual. The <br />cylindrical gauge's fill line <br />gives users an easy way to <br />understand how actual values <br />weigh against a target <br />capacity. The tool is useful <br />for evaluating inventory, <br />fuel, or other repository levels.<br /> Features: <br />1. Actual value display. For <br />added clarity, the fill <br />line's actual value is listed <br />below the cylinder. <br />2. Tick marks. Users may <br />adjust or disable this <br />feature. By default, tick <br />values are enabled, with the <br />minimum set to 0 and the <br />maximum set to 100. <br />3. Max threshold definition. <br />Users may include a maximum <br />threshold to see whether the <br />actual value is over capacity. <br />4. Scroll bar. When height <br />restrictions limit how much <br />of the gauge is visible, a <br />vertical scroll bar allows <br />users to navigate up and down.|

<br />
<br />

| Dot Plot   |      [Funnel with Source](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/FunnelWithSource/src/Visual.ts)     |  [Histogram with points](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/HistogramXY/src/visual.ts) |
|----------|------------|------|
| <img src="https://maqsoftware.com/img/PowerBI/Dot_Plot.png" alt="Dot Plot Chart" height="268" width="268"> <br/>Displays distribution using <br />dots across multiple <br />categories. This statistical <br />chart consists of data points <br />(bubbles) plotted on an XY <br />axis, distributed over a <br />desired set of values. The <br />size of the bubble represents <br />magnitude; color represents <br />the type of category. Dot <br />Plot enables users to view <br />data through multiple parent <br />categories and child sub-categories. <br />Dot Plot supports selection, <br />partial highlighting, multi <br />selection, legends, tooltips, <br />displaying different color <br />bubbles for different <br />categories, and all other <br />default formatting options <br />available in Power BI. Users <br />can modify bubble size, <br />orientation of the chart, <br />X-axis and Y-axis text, <br />background and start the <br />axis from a specified value. | <img src="https://maqsoftware.com/img/PowerBI/Funnel_with_source.png" alt="Funnel with Source" height="268" width="268"> <br/>Funnel with Source, as the <br />name suggests, showcases the <br />funnel journey of any metric/ <br />data point. The visual can <br />help visualizing count of any <br />metric of interest over <br />various stages along with the <br />source of entry or entry <br />channel of the data point <br />through which it reaches the <br />funnel. For example, in the <br />case of sales journey data, <br />this visual displays the <br />channel through which any <br />lead enters the funnel and <br />then the corresponding <br />journey through the various <br />stages of sales cycle. We can <br />also filter data based on the <br />selection of channel and on <br />the selection of any stage of <br />the sales journey.<br />Cross visual filter is also <br />supported by this visual. <br /><br /><br />  | <img src="https://maqsoftware.com/img/PowerBI/Histogram.png" alt="Histogram" height="268" width="268"> <br/>Combines benefits of showing <br />point distribution along with <br />actual values. The following <br />formatting options are <br />provided in this visual: <br />1. Show or hide points in the <br />chart <br />2. Show or hide histogram bars <br />3. Show or hide X-axis <br />4. Show or hide Y-axis-right <br />5. Show or hide Y-axis-left <br />(Y-axis of histogram) <br />6. Show or hide grid lines <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />|


<br />
<br />

| [KPI Ticker](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/KPITicker/src/visual.ts)   |      [Venn Diagram](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/CustomVisuals/Published/VennDiagram/src/visual.ts)     |  Box and Whisker |
|----------|------------|------|
| <img src="https://maqsoftware.com/img/PowerBI/KPI_Ticker.png" alt="KPI Ticker" height="268" width="268"> <br/>Automatically flipping visual <br />that allows you to view <br />various metrics along with <br />trend indicators. KPI Ticker <br />allows you to configure a set <br />of metrics that will be shown <br />in rotation. It also allows <br />you to specify trend <br />indicators that show the <br />percentage or value drop or <br />increase. Suitable for <br />applications that focus on <br />key metrics and the metric <br />value increase or decrease. <br />Visually attractive with <br />ability to change colors of <br />tiles and trend indicators. <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /> | <img src="https://maqsoftware.com/img/PowerBI/Venn_Diagram.png" alt="Venn Diagram" height="268" width="268"> <br/>Venn diagram displays all <br />possible logical relations <br />between a collection of <br />datasets, each typically <br />represented as a circle. Each <br />circle (set) is a collection <br />of objects or array of data <br />that all have something in <br />common. When multiple circles <br />(sets) overlap, it is known <br />as the intersection - this is <br />where data that has all the <br />qualities that the <br />overlapping sets have. Each <br />circle can have their <br />distinguishing name and color <br />to differentiate from other <br />circle or sets. Labeling of <br />each circle helps in knowing <br />its individual or intersected <br />region's value. The same <br />information is also visible by <br />hovering on any of the <br />regions. <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />  | <img src="https://maqsoftware.com/img/PowerBI/Box_and_Whisker.png" alt="Box and Whisker" height="268" width="268"> <br/>Box and whisker charts are <br />most commonly used in <br />statistical analysis like <br />comparing medical trial <br />results or teachers' test <br />scores et. al. It consists of <br />two parts - the main body <br />called the Box and the thin <br />vertical lines coming out of <br />the Box called Whiskers. The <br />first quartile forms the <br />bottom and the third quartile <br />forms the top of the Box. The <br />Whiskers connect the minimum <br />and the maximum values to the <br />Box. In addition to showing <br />median, first and third <br />quartile and maximum and <br />minimum values, the Box and <br />Whisker Chart is also used to <br />depict Mean, Standard <br />Deviation and Quartile Deviation. <br />While other Power BI Box plots <br />have the capability to <br />display these statistics <br />data, Box Plot by MAQ <br />Software provides more <br />details and clarity of the <br />figures by providing more <br />user controls and <br />capabilities to suit the <br />exact needs of the use case <br />like ability to add parent <br />axis and flip visual <br />horizontally or vertically <br />based on reporting requirement. <br /> |


<br />
<br />

| Gantt Chart   |      Slope Chart  |  Dumbbell Chart |
|----------|------------|------|
| <img src="https://github.com/maqsoftware/PowerBI-visuals/blob/master/documents/Internal/GanttChart/Gantt300x300.png" alt="Gantt Chart" height="268" width="268"> <br/>Gantt Chart is used for <br />scheduling and management of <br />task. While an ordinary Gantt <br />Chart just displays the basic <br />details like task id or name <br />and their schedules, Gantt <br />Chart by MAQ Software <br />provides more details of the <br />task by providing a grid <br />where one can view more data <br />related to the task and can <br />display the hierarchy of data <br />category. Also, data can be <br />sorted based on any data point <br />of the task. <br />For example, take case of <br />project management, while <br />other visuals will just <br />provide project id/name, <br />start time, end time and <br />current status, this visual <br />can provide additional <br />details (data points) apart <br />from the mentioned such as <br />duration of project, owner of <br />the project along with KPIs <br />such as 'priority' etc. on a <br />grid as separate columns <br />inside the visual itself. <br />Apart from additional <br />information about the <br />project, this visual let the <br />user view project hierarchy <br />(i.e.) tasks under any <br />project and their progress. <br />User can sort the project/task <br />based on their data points as <br />present on the grid column. <br />The visual lets you configure <br />the detailing of information <br />as per requirement. Other <br />formatting features can <br />represent information in a <br />way that best tells the story <br />of your data. | <img src="https://github.com/maqsoftware/PowerBI-visuals/blob/master/documents/Internal/SlopeChart/Slope300x300.png" alt="Slope Chart" height="268" width="268"> <br/>Slope Chart allows users to <br />analyze trends in data at a <br />glance. This visual is useful <br />for comparing interactions <br />between two data points based <br />on time or other user-chosen <br />parameters. Slope Chart <br />places primary emphasis on <br />end points by focusing on the <br />difference between the start <br />and end values. <br /> Key features include:<br />1. The ability to display <br />trends across various <br />indicators. <br />2. Quick comparison of <br />indicator growth or loss <br />across categories. <br />3. Easy interaction with many <br />data points using the zoom <br />functionality. <br />4. Quick downloading of an <br />image of the chart with the <br />capture image widget. <br />R package dependencies (auto <br />installed): plotly and ggplot2 <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />  | <img src="https://github.com/maqsoftware/PowerBI-visuals/blob/master/documents/Internal/DumbbellChart/Dumbbell300x300.png" alt="Dumbbell chart" height="268" width="268"> <br/>Dumbbell Chart helps users <br />analyze changes in critical <br />data. This visual is an <br />excellent choice for <br />illustrating the change <br />between two data points and <br />comparing the distances <br />between them. Dumbbell Chart <br />gets its name thanks to its <br />resemblance to a gym weight. <br />The visual consists of a <br />dual-axis combination chart, <br />where one axis is marked by a <br />circle and the other is <br />marked by a line that spans <br />data points provided by the <br />user. <br /> Key features include: <br />1. The ability to display the <br />performance of multiple <br />indicators. <br />2. The ability to compare the <br />growth or loss of indicators <br />across various categories. <br />3. Easy interaction with many <br />data points using the zoom <br />functionality. <br />4. Quick downloading of an <br />image of the chart with the <br />capture image widget. <br />R package dependencies (auto <br />installed): plotly and ggplot2 <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />|


<br />
<br />

# PowerBI Visual Tools (pbiviz) - Installation

Before you can get started you'll need to install the tools. This should only take a few seconds.

## Dependencies

Before you can run (or install) the command line tools you must install NodeJS.

* NodeJS 4.0+ Required (5.0 recommended) - [Download NodeJS](https://nodejs.org)


## Installation
[![Npm Version](https://img.shields.io/npm/v/powerbi-visuals-tools.svg?style=flat)](https://www.npmjs.com/package/powerbi-visuals-tools)
[![Npm Downloads](https://img.shields.io/npm/dm/powerbi-visuals-tools.svg?style=flat)](https://www.npmjs.com/package/powerbi-visuals-tools)  
To install the command line tools simply run the following command

```bash
npm install -g powerbi-visuals-tools
```

To confirm it was installed correctly you can run the command without any paremeters which should display the help screen.

```bash
pbiviz
```

## Server certificate setup

To enable live preview visual assets need to be served on a trusted https server so before you can start you need to install an ssl certificate which will allow visual asssets to load in your web browser. This is a one time setup.

* [How to install the local SSL certificates](https://github.com/Microsoft/PowerBI-visuals/blob/master/tools/CertificateSetup.md) 

## Enable developer visual

To view/test your visual in PowerBI you need to enable the development visual and then you can add it to any report.

* [How to enable the developer visual in PowerBI](https://github.com/Microsoft/PowerBI-visuals/blob/master/tools/DebugVisualSetup.md)

# Running the visuals in this repository 
Select the visual you want to run. Navigate to the root of visual project (the directory containing `pbiviz.json`). Simply run the following commands

```bash
#This will install modules listed in package.json
npm install 

#This will install type definitions listed in typings.json
typings install 

#To run the visual
pbiviz start
```

That's it you are good to go. You can see that the visual is running.

### Copyrights

Copyright (c) 2017 Microsoft and MAQ Software

See the [LICENSE](/LICENSE) file for license rights and limitations (MIT).
