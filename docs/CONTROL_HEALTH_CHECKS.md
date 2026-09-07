# Control Health Checks

Use the dashboard and service endpoints to verify the main operational controls:

- Confirm ingestion and validation complete before preprocessing starts.
- Check schema, freshness, and data-quality results before feature generation.
- Confirm model evaluation and registry state before serving or deployment.
- Review drift, latency, and service health signals after a release.

Record failed checks with the affected workflow, timestamp, and service response so an incident can be reproduced.