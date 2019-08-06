# Get all files with a given extension and then get all lines greater then a length.
find config.json . | grep config | xargs grep '.\\{120\\}'
