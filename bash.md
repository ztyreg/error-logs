# Change file encoding
`iconv -f GB18030 -t UTF-8 original.txt > new_UTF-8.txt`
# List files with their absolute path, concatenated by colons
`find $PWD | awk '{a=a colon $0; colon=":"} END {print a}'`
