# mein-erster-agent

This repository contains a basic Make.com scenario blueprint for creating a Google Calendar event from Vapi webhook data.

## Scenario Overview

1. Webhook module receives appointment data via HTTP POST from Vapi.
2. Parse JSON module extracts timestamp, name and notes.
3. Google Calendar module uses the parsed data to create a new calendar event.

See `make_scenario_blueprint.json` for the placeholder setup.
