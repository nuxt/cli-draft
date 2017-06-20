# nuxt-cli
CLI for Nuxt.js projects

## Commands

### Templates

```bash
# Create nuxt.js project
nuxt new <template-name> <folder-name?>

# List official templates
nuxt templates list
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

```bash
# List nuxt.js official modules
nuxt module list

# Add a nuxt.js module to the project
nuxt module add <module-name>

# Remove a nuxt module
nuxt module rm/remove <module-name>

# Add a new module locally (modules/<module-name>/index.js)
nuxt module new <module-name>

# Upgrade a nuxt module
nuxt module upgrade <module-name>
```

### Pages

```bash
# Add a page
nuxt page add <page-name>

# Remove a page
nuxt page rm/remove <page-name>
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
nuxt link <nuxt.js-dir>
```
