# ABNF
A nom-based ABNF parser.

# Status
Not thoroughly tested, but "works for me" (and with arguably complex ABNFs)

# Branches
This branch provides a quick&dirty transformation of ABNF to ANTLR syntax.

The output should be *almost correct*, but outputs wrong repetitions (see src/abnf.rs:64).
