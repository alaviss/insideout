# insideout

This is an experimental concurrency library.

[![Test Matrix](https://github.com/disruptek/insideout/workflows/CI/badge.svg)](https://github.com/disruptek/insideout/actions?query=workflow%3ACI)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/disruptek/insideout?style=flat)](https://github.com/disruptek/insideout/releases/latest)
![Minimum supported Nim version](https://img.shields.io/badge/nim-1.9.3-informational?style=flat&logo=nim)
[![License](https://img.shields.io/github/license/disruptek/insideout?style=flat)](#license)
[![IRC](https://img.shields.io/badge/chat-%23%23disruptek%20on%20libera.chat-brightgreen?style=flat)](https://web.libera.chat/##disruptek)

## Support

insideout supports `define:useMalloc`, `mm:arc` and `backend:c` or
`backend:cpp` and POSIX threads. insideout does not support `mm:orc`.

insideout is tested with valgrind/helgrind/drd using c and c++.

## Documentation

Nim's documentation generator breaks when attempting to read insideout.

Define `insideoutValgrind=on` to enable valgrind-specific annotations.
Define `insideoutSleepyMonkey=N` to nanosleep `N`ns disruptively.

## License
MIT
