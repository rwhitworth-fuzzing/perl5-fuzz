# perl5-fuzz
fuzzing results for git://perl5.git.perl.org/perl.git

- `2017-06-21-5.27.1` - perl 5.27.1 fuzz.  Results from cperl crashes fed into perl caused these to be found.

- `2017-06-22-5.27.1` - perl 5.27.1 fuzz.  Unreported to perl5-porters, because they're drowning in reports from fuzzers and haven't yet responded to my previous fuzz results.

- `2017-07-03-5.27.2` - perl 5.27.2 fuzz.  Unreported to perl5-porters.

- `2017-07-06-5.27.2` - perl 5.27.2 fuzz.  Unreported to perl5-porters.  Still no response to report from 2017-06-22, so no reason to report these.  Lots of trouble with afl-fuzz dying due to OOM/fork-server trouble.  Also trouble with tmux dying and taking afl-fuzz with it, somehow?
