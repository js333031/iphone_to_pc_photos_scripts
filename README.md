# iphone_to_pc_photos_scripts

* Find unique extensions in directories: *
`find . -type f | perl -ne 'print $1 if m/\.([^.\/]+)$/' | sort -u`

* Find HEIC files: *
`find . -type f -iname "*HEIC*"`

