# marlin2smoothie-webConfig
A web page to convert Marlin Configuration.h to a SmoothieWare config.txt

Goal :

1 - Paste or upload your Configuration.h file from your Marlin in the first area,
2 - Click the [Convert] button
3 - Get your config.txt file ready for your SmoothieBoard (-:

Way to get it work :

1 - Make a hash from the marlin Configuration.h
2 - Make a hash from the SmoothieWare config.txt sample
3 - Apply a lot of Rules from the marlin.hash to the smoothie.hash (Regex)
4 - Write the smoothie config.h from the smoothie.hash
