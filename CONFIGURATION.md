# Configuration

Environment-specific connection values have been removed from the source.

Create a `.env` file based on `.env.example` and replace the placeholder values with your SharePoint details:

- `SHAREPOINT_SITE_URL` – URL of the SharePoint list.
- `SHAREPOINT_CONNECTION_ID` – connection instance identifier for the SharePoint connector.
- `POWERAPPS_ENVIRONMENT_ID` – PowerApps environment identifier.

During deployment, substitute these values into `CanvasManifest.json` and `sharepoint-connection.json`.
