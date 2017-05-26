# Tool for working with WEBFS file system #

usage: webfs_tool.py build [-h] [-s SOURCE] [-d DYNAMIC_FILES]
                           [-n EXCLUDE_GZIP] [-f FILE]
                           output

positional arguments:
  output                Output image file

optional arguments:
  -h, --help            show this help message and exit
  -s SOURCE, --source SOURCE
                        Source directory
  -d DYNAMIC_FILES, --dynamic_files DYNAMIC_FILES
                        Files with dynamic content (default " *.htm, *.html, *.cgi, *.xml, *.bin, *.txt, *.wav ")
  -n EXCLUDE_GZIP, --exclude_gzip EXCLUDE_GZIP
                        Files not to be gzipped
  -f FILE, --file FILE  Add file to image in format path/in/image:path/on/disc
