===============================
What is SaltPad-CLI?
===============================


SaltPad-cli is a CLI tool to manage SaltStack deployments + orchestration. It's still very young and it's should be considered as Alpha. It was previously included in SaltPad itself but now the GUI and the CLI are splitted because the GUI doesn't requires salt as a dependency.

This code was a Proof Of Concept and will need some cleaning for the latest Salt version.

The idea was to be able to launch a new Vagrant Box with a salt minion config and to be able to rollback easily and quickly using virtualbox snapshots.
