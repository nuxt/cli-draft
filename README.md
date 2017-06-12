# nuxt-cli
CLI for Nuxt.js projects

## Commands

### Templates

```bash
# Create nuxt.js project
nuxt init <template-name> <folder-name>

# List official templates
nuxt list templates
```

### Project
```bash
# Start in development mode
nuxt dev

# Build for production
nuxt build

# Start in production mode
nuxt start

# Generate a server-rendered static website
nuxt generate
```

### Modules

```
# List nuxt.js official modules
nuxt list modules

# Add a nuxt.js module to the project
nuxt add <module-name>

# Remove a nuxt module
nuxt remove <module-name>

# Upgrade a nuxt module
nuxt upgrade <module-name>
```

### Utils

```bash
# Analyze bundles
nuxt analyze

# Benchmark project
nuxt benchmarks

# Upgrade nuxt.js dependency
nuxt upgrade

# Test project (proposal)
nuxt test

# Link nuxt.js to project (development of nuxt.js)
nuxt link <nuxt.js-repo>
```
