 
# Antwar

You probably don't want this yet.  I'm currently just goofing with ideas.

## Development
(from the voxelize README)

Before starting, make sure to install the following:

- [rust](https://www.rust-lang.org/tools/install)
- [node.js](https://nodejs.org/en/download/)
- [cargo-watch](https://crates.io/crates/cargo-watch)
- [protoc](https://grpc.io/docs/protoc-installation/)

```bash
# clone the repository
git clone --recurse-submodules https://github.com/geeksville/antwar.git
cd antwar

# download dependencies
yarn

# generate protocol buffers
yarn run proto

# in a separate terminal, run built in documentation server, accessible on port 8080
yarn run docs

# start development
yarn run dev

# in a separate terminal, start both frontend/backend demo
yarn run demo

```

visit http://localhost:3000