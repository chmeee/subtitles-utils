# subtitles-utils

Some simple scripts to manage subtitles (.srt) files

## subs-scaffold

Creates a first subtitles file to help you start

    Syntax: ./subs-scaffold number-of-subtitle-lines step-in-seconds output-file

## subs-op

Adds or substract time or indexes in a subtitles file (WARNING: in place operation)

    Syntax: ./subs-op [index|time] operation subs-file
    Example: ./subs-op index +3 subs-file.srt
    Example: ./subs-op time -00:01:12 subs-file.srt
    
