# TODO

## --importdb
Add --importdb to reverse an --exportdb

## Multiline Notes
Some way of entering multiline notes. Perhaps
the ole 'single . on a line' termination that
mail & smtp use?

## CUI
curses based interface?

## Partial Loading of DB
don't read entire db into RAM---just decrypt the name and the string lengths.
--add can be done w/o decrypting any strings!

## pwsafe-agent mode
pwsafe-agent mode (like ssh-agent)? with encrypted string like win32 passwordsafe?
or will interactive mode be enough? What about actually using ssh-agent and a
public key under which the passphrase is stored?

