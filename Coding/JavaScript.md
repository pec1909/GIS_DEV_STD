# Java Script Standards

implemented [StandardJS](https://standardjs.com/) because it’s simple and allows the team to focus on developing code, not worrying about standards.

The following are the ‘The Rules’ in place out of the box

2 spaces – for indentation
Single quotes for strings – except to avoid escaping
No unused variables – this one catches tons of bugs!
No semicolons – It’s fine. Really!
Never start a line with (, [, or `
This is the only gotcha with omitting semicolons – automatically checked for you!
Space after keywords if (condition) { … }
Space after function name function name (arg) { … }
Always use === instead of == – but obj == null is allowed to check null || undefined.
Always handle the node.js err function parameter
Always prefix browser globals with window – except document and navigator are okay
Prevents accidental use of poorly-named browser globals like open, length, event, and name.
This was taken directly from StandardJS website but make sure you read more for a complete list of all the rules.
