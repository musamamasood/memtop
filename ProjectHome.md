ATTENTION: the project has migrated to:  https://github.com/MartinThoma/memtop !!!

In linux it is easy to check system memory usage by processes, at least it looks so. Problem is that tools like top provides few different categories of "memory". My tools provides only one number - private/writeable memory, and present it in easy to read manner. Processes are sorted starting with biggest one. Even though it resembles (h)top command by the output, this is intended to run over long periods of time (days/weeks/even months) and iterate in minutes or hours.

One of intended use is when you are trying to reduce memory consumption of your box or are trying to identify misbehaving application (memory leaks and so on).

The tool completely ignores shared memory, read [memtop](memtop.md) wiki for reasoning and additional info...