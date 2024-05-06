# conan-config

Contains a standard Conan 2 configuration for Datalogics, including:

- profiles for various platforms
- `settings.yml` file containing definitions of compilers and platforms
- remote repositories
- config variable overrides

This configuration can be installed with `conan config install`. 

## Using

```bash
$ conan config install git@octocat.dlogics.com:datalogics/conan-config.git
```

## Tagging

Tags with version numbers aren't used on this repo.

This config should be **forward compatible**; only add items to the config. It's
possible to create new named profiles, and add remotes.

Projects will use the tip of the default (`develop`) branch.
