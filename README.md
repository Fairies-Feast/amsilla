# This is the Amsilla Python Package
## Method usage:

1: `authUser()`

Used only in Byteint. Returns the user's name, or None. No params.

2: `postCall()`

Four params: auth code, location, action, context (unneeded except for comments and workspace).
Example: "my-auth-code", "@user/project", "comment", "hello".
Example with workspace: "my-auth-code", "@user/project", "edit","change code to this!".
If you want to change this API, comment on this repo.

3: `getCall()`

Three params: auth code, location,request.
Example: "my-auth-code", "@user/project", "comments".
Example with workspace: "my-auth-code", "@user/project","code".
If you want to change this API, comment on this repo.
