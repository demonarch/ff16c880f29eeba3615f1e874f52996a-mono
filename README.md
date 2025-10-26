# ff16c880f29eeba3615f1e874f52996a-mono

This is a monorepo containing both frontend and backend components as git submodules.

## Repository Links

- **Monorepo**: [ff16c880f29eeba3615f1e874f52996a-mono](https://github.com/demonarch/ff16c880f29eeba3615f1e874f52996a-mono)
- **Backend**: [ff16c880f29eeba3615f1e874f52996a-be](https://github.com/demonarch/ff16c880f29eeba3615f1e874f52996a-be)
- **Frontend**: [ff16c880f29eeba3615f1e874f52996a-fe](https://github.com/demonarch/ff16c880f29eeba3615f1e874f52996a-fe)

## Local Deployment

### Clone the Repository with Submodules

To get started with local development, clone this repository and its submodules:

```bash
# Clone the monorepo with submodules
git clone --recurse-submodules https://github.com/demonarch/ff16c880f29eeba3615f1e874f52996a-mono.git

# Navigate to the project directory
cd ff16c880f29eeba3615f1e874f52996a-mono
```

If you've already cloned the repository without the submodules, you can initialize and update them:

```bash
# Initialize submodules
git submodule init

# Update submodules
git submodule update
```

### Component-Specific Deployment

For detailed instructions on how to deploy and run each component:

- **Backend**: See the [backend README](modules/backend/README.md) for setup and deployment instructions.
- **Frontend**: See the [frontend README](modules/frontend/README.md) for setup and deployment instructions.

## Project Structure

```
ff16c880f29eeba3615f1e874f52996a-mono/
├── modules/
│   ├── backend/  # Python backend
│   └── frontend/ # Next.js frontend
```
