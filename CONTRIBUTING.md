# Contributing

Thank you for contributing to Apathetic Tools Recipes!

## Artifact Directories

The `_dist-site-repo` directory is an automatically generated directory used for publishing. **Do not make manual edits to files inside `_dist-site-repo`**, as they will be overwritten by the build script.

If you need to make changes to files like `NOTICE` or `LICENSE` that are distributed, edit the source files in the root of the repository instead.

### Build Process
To update the `_dist-site-repo` directory after modifying root files, run the build script:

```bash
./scripts/pocket-build.py
```

The script is configured via the `.pocket-build.json` file.
