# Bristol
Insanely configurable logging for Node.js

##ChangeLog

### v0.3.2
- Fix: Don't assume all errors have stack traces

### v0.3.1
- Fix: Human formatter now outputs pretty-printed JSON when it encounters an
object literal instead of "[object Object]".
- Fix: CommonInfoModel formatter now replaces all double-quotes with
single-quotes, instead of just the first.

### v0.3.0
- Added: Loggly target
- Added: Better documentation regarding targets

### v0.2.2
- Fix: Error objects not being properly sent to log targets

### v0.2.1
- Fix: Minor inaccuracies in README examples
- Fix: Options were improperly sent to target functions

### v0.2.0
- Added: Human formatter
- Added: CommonInfoModel formatter
- Added: Syslog formatter
- Added: File target
- Added: Travis CI testing
- Added: Incredible amounts of docs
- Fix: Move dateformat to constant in CommonInfoModel and Syslog formatters
- Fix: Remove comma separator from date elements in JSON formatter
- Fix: Options documentation in JSON formatter
- Fix: Target and formatter paths

### v0.1.0
- **Initial Release**
