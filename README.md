# TheCMO for Claude

Install this plugin in Claude and sign in to the bundled TheCMO connector with
the Google email invited to TheCMO. Then ask for marketing work in ordinary
language. The bundled skill guides relevant requests through the TheCMO connector
and tells Claude to use its own available research and browser tools for
website design and visual review. TheCMO stores business context, journey
state, methods, and drafts. Sign-in and separate provider authorization are
required for private data.

In Claude Desktop, you can also open a local TheCMO Business Folder. Its
`BUSINESS.md` identifies the business and its `outputs/` holds local files;
TheCMO keeps the saved work state.

For a continuation request, the skill checks saved businesses and work before
looking for a local website folder. If the host cannot reach TheCMO, it should
say so rather than invent a business. Automatic routing and browser review
still require a real host test; package validation alone does not prove them.

The MIT license covers only this public plugin package. It does not include
TheCMO's hosted service, private methods, or any member business records.

Support: cmo@thecmo.ai
