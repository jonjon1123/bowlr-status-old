+++
# default attributes for an incident.
title = "Sample Title"
date = 2018-10-14T19:47:42.000Z

# severity: represents the impact of
# your system due to the current incident.
# This is the list of supported severities:
#
# - under-maintenance
# - degraded-performance
# - partial-outage
# - major-outage
severity = "degraded-performance"

# affectedsystems: is a list of systems affected
# by the incident.
# Example:
# affectedsystems = ["Android App", "iOS App", "Website"]
affectedsystems = ["Android App", "iOS App"]

# resolved: marks an incident as resolved.
# It can be either true or false.
resolved = false
+++
The error has been noticed and will be resolved.

**Update**: We've identified the issue. {{< track "2018-10-14T20:00:00.000Z" >}}

**Update 2**: We've identified the issue again. {{< track "2018-10-14T21:00:00.000Z" >}}
