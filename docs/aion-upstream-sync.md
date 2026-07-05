# AION Upstream Sync

This fork is operated by AION as a local website-building and publishing capability.

- Fork remote: `https://github.com/jodysachse72-arch/Instatic.git`
- Upstream remote: `https://github.com/CoreBunch/Instatic.git`
- Local workspace: `C:\Users\Jody\Documents\AION-Capabilities\Instatic`
- Runtime owner: AION Nexus, via `server/instatic-runtime.js`

Operational notes:

- AION stores owner credentials and MCP connector bearer tokens only in ignored local data files.
- AION connects through Instatic's Streamable HTTP MCP endpoint at `/_instatic/mcp`.
- Browser-relayed page editing requires the live Instatic editor bridge at `/admin/site`.
- Upstream sync should use normal Git history preservation: fetch upstream, inspect, merge or rebase intentionally, then push to Jody's fork after proof.
