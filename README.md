# Heroku Build Cache Checker buildpack

Proof of concept: if the current BUILD_DIR has been built before,
use a cached build output instead of rebuilding.

Why would you want this? You probably wouldn't, unless you're doing
some wacky monorepo stuff.
