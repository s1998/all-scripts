# Get all files with a given extension and then get all lines satisfying a constraint.
find config.json . | grep config | xargs grep '.\{120\}
