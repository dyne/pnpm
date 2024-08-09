# dyne/pnpm action

This action checks-out your repository, set-up node and pnpm, cache your dependencies and install them.

# Usage
```yaml
- uses: dyne/pnpm@main
  with:
    # Fetch depth (for actions/checkout)
    # Default: 1
    fetch-depth: ''

    # Checkout also submodules (for actions/checkout)
    # Default: false
    submodules: ''

    # Specify the node version you want to use (for actions/setup-node)
    # Default: current
    node-version: ''

    # Specify the pnpm version you want to use (for pnpm/action-setup)
    # Default: 9
    pnpm-version: ''

    # Specify where to run the install command
    # Default: .
    working-directory: ''
    
    # Installation script to run
    # Default: pnpm i
    install: ''

    # Build script to run, usually `pnpm build`
    # Default: ''
    build: ''
```
