# Audacity description parser #

Just a dummy class for playing with groowy and gradle. This parses audacity description files (somelike).

Changing from:

 0,058201        153,766832      Line1

To:

 00:00     02:33      Line1

- - -

Run with:

gradle exec
 - file description.txt will be taken from src/main/resources/ and process
gradle exec -q -Pquiet 
 - the output will be just the "converted" data from the file
gradle exec -Pfile=/path/to/file.txt
 - specified file will be taken to parse

