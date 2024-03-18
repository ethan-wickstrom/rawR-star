# *raw*R-star

## Introduction

## Installation

## Usage

## Contributing

## Directory Structure

```markdown
.
├── Cargo.lock
├── Cargo.toml
├── README.md
├── .gitignore
├── src/
│   ├── lib.rs
│   ├── main.rs
│   ├── errors/
│   ├── models/
│   ├── services/
│   ├── traits/
│   ├── utils/
│   └── bin/
├── benches/
├── examples/
└── tests/
```

- `Cargo.toml` and `Cargo.lock` are the manifest and lock files, respectively.
- `README.md` is the file you are currently reading.
- `.gitignore` is the file that tells git which files to ignore.
- The `src` directory is where the source code goes.
  - `lib.rs` is the default library file.
  - `main.rs` is the default executable file.
  - `/models`: Contains data structures (structs, enums) that represent domain entities.
  - `/services`: Business logic that operates on models.
  - `/utils`: Utility functions and helpers that don’t fit directly into models or services.
  - `/traits`: Traits that are used to define interfaces or behavior contracts for models and services to implement.
  - `/errors`: Custom error types and error handling logic.
  - `/bin`: Other executables.
- `benches` is where benchmarking code goes.
- `examples` is where example code goes.
- `tests` is where test code goes.

## License