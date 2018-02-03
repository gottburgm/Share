### Command

```bash
perl -e 'my @o = `cat /var/www/scripts/src/replacements.data`; foreach my $l (@o) { chomp $l; $l =~ s/</\\</gi; $l =~ s/>/\\>/gi; $l = "| $l |"; $l =~ s/:::/\|/gi; $l =~ s/\_\_RCHAR\_\_/\$/gi; print "$l\n"; }'
```
