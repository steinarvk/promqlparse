# promqlparse

A CLI tool that reads an expression from stdin and tries to parse
it as a Prometheus PromQL expression.

It returns success (0) or failure (1) depending on whether or not
the parse succeeded, and prints an error message to stdout if the
parse failed.

This program is primarily meant to used in linters, checks, and
the like.
