# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added

 - Label text for edges with routing
 - Node graph mutation (stroke, stroke-width, fill)
 - Added npm build scripts
 - Added userOptions on initialization
 - Added UMD library definition (full d3 at the moment)
 - Add options for different webcola options (flowLayout, jaccardLinkLength)
 - Add options for circles/rect graphs
 - Added edge color by edge type option
 - Add edges between visible nodes
 - Recenter graph (not very good)
 - Zoom and panning
 - Graph options callback for selecting nodes
 - Node color option function
 - Edge Routing
 - Initial Node d3 mutation - addNode
 - Predicate edge color option (with marker color change)
 - Dynamic node size
 - Remove node by hash
 - Stopped Graph Jumping (handleDisconnect to false)
 - Graph resize feature
 - addTriplet endpoint to the graphFactory

### Changed

 - AddNode can take an array of nodes