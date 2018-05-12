# cryptofunding

The service provides an opportunity for users to raise funds for the implementation of their projects.


- `total()` - Returns count of projects.

- `create(projectJson)` - Creates a new project.

- `get(limit, offset)` - Returns projects.

- `getById(id)` - Returns the project with the specified Id.

- `getByWallet(wallet)` - Returns the project created by the owner of the wallet.

- `addToFavorites(projectId)` - Adds a project with the specified Id to favorites.

- `removeFromFavorites(projectId)` - Remove a project with the specified Id to favorites.

- `getFavorites()` - Returns the user's favorite projects.

- `getSupported()` - Gets the projects that the user has supported.

- `support(projectId)` - Support the project.
