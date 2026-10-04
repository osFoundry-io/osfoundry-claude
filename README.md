# osFoundry for Claude

Connect Claude to one osFoundry workspace, then add the connection to the projects where it may work. Supported synced project content includes Note tabs, knowledge bases, records, cloud Rooms, and GitNest repositories. Ordinary Message channels need a separate invitation. Note tabs can contain text, Slides, or Sheets. Some actions can post messages, edit tabs, request session runs, or propose handoffs when current project access, source roles, and session seats allow them.

Sign in to osFoundry when Claude prompts you, choose one workspace, and add the connection to a project from the key icon → Connected. Start by asking Claude to list the projects available to it. The plugin contains no account credentials.

The connector uses `https://api.osfoundry.io/api/v1/external-mcp` and the plugin contains no credentials. Some osFoundry operations require credits or an existing paid account. The plugin does not process payments or sell credits. OS LLC publishes this bundle under the MIT license.

For a public directory listing, submit the remote MCP server as a connector and this bundle as a plugin from the same Claude organization. The bundle must be hosted in a GitHub repository for the plugin listing; the connector listing uses the server URL. Test sign-in and the tools in Claude before submitting.
