# Package.json Bundler Fix

This PR fixes `package.json` to point `"main"` and `"style"` fields to `easemotion.min.css` so bundlers (Vite, webpack, Parcel) use the pre-built flat file instead of resolving @import chains individually.

## Fix Applied
- `"main": "easemotion.min.css"`
- `"style": "easemotion.min.css"`

Closes #9874
