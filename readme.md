# jQuery Chart plugin
## Versionnumber 1.0.0 (2015-10-26) 
Mini jQuery Chart plugin, that replaces Tables with html - canvas - DonutChart

## Features
* Table-Rows can will be sorted
* Chart-legend label size can be modified
* Chart-legend will positions automatic bottom or right
* Chart-border can be deactivated
* Chart-label can be deactivated
* Chart-plugin is chainable

## Roadmap / Future Features
* update Documentation
* Chart-legend can be deactivated
* flexible / configurable table-structure
* refactor clean / code
* other charts / types

## Known Bugs
* Legend gets cut-off 

## System Requirement & Prerequisits
jQuery Version 1.11.3

## Usage

### Setup
add script to plugin
    
	<script type="text/javascript" src="js/jquery.chart.js"></script>

### SourceControl Link & Information
git@github.com:akumagamo/jquery-plugin-chart.git

### Base Code Example

	$(".donutgraph").dountGraph();
	// Tested on Win7 with Chrome 46+

See ```demo.html``` for an working example.

## Documentation

### File / Folder Structure 
     +-+- jquery-plugin-chart
	   +-+- js
	   | +- jquery.chart.js
	   +- demo.html
       +- readme.md (this document)
	   +- LICENSE 
	  
### Options / Tables structure
* width
* height
* legendSizePadding
* legendSize
* label
* hasBorder
* item
    * sortOrder
    * value
    * color
    * description



