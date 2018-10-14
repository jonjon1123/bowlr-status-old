+++
# default attributes for an incident.
title = "{{ replace .TranslationBaseName "- NoSuchMethodError: The getter 'alwaysShowFrameScores' was called on null." | title }}"
date = {{ .Date }}

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
