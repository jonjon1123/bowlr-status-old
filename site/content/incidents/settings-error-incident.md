+++
# default attributes for an incident.
title = "NoSuchMethodError: The getter 'alwaysShowFrameScores' was called on null."
date = 2018-10-13T17:30:00.000Z

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
affectedsystems = ["iOS App"]

# resolved: marks an incident as resolved.
# It can be either true or false.
resolved = false
+++
A bug has been identified that presents the above mentioned error when a user tries to enter in scores in frame-by-frame mode. To work around this error, users can open up the app settings and toggle the "Always show frame scores" switch from off to on and the back to off.

**Update**: The issue has been identified and resolved in Android. The iOS fix has been submitted to Apple and is awaiting approval. {{< track "2018-10-13T18:00:00.000Z" >}}
