# VTSC - Vision Turn Speed Control
Uses the predicted driving path from the model to limit speed when entering
and during curves.

# Branch
[pfeifer-vtsc](https://github.com/pfeiferj/openpilot/tree/pfeifer-vtsc)

# Acknowledgments
* Refactor of the [move-fast](https://github.com/move-fast/openpilot) vtsc
implementation.
* [Sunnypilot](https://github.com/sunnyhaibin/sunnypilot) was also used as a
reference.

# Status
Experimental

This is my initial implementation of a refactor of the move-fast vision turn
controller. My first test drives show promise for the experience compared to
the existing implementation. Still needs tuning of the acceleration targets as
well as some cleanup and visual indicators of its status in the ui.

# Comment Blocks Text
PFEIFER - VTSC

# Why two patch files?
Currently the plan is for the changes in the first patch file to be merged
upstream into openpilot. Once merged that would make the second patch the only
code needed for the VTSC implementation. If the upstream PR gets rejected I
will merge the two patch files into a single patch instead.

# Upstream PR
The first patch in this folder is in [this](https://github.com/commaai/openpilot/pull/27741) upstream PR.