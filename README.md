# SAFTraversal

A study into tree traversal times for Safe access framework.

Note: my phone does have some problems with freezing every 5 seconds, so times are impacted for SAF, probably upwards of +2-3 seconds.

* `java.io.File` traversal: ~1.9 seconds for 45719 files.
* Direct `ContentProvider` traversal: ~15 seconds for 45719 files.
* `DocumentFile.listFile()` traversal: a whopping **~203 seconds** for 45719 files.
