# SequentialNumber
PW module for fields with a formatted sequential number

## Status

Alpha

## Beware

The sequences are created per field, so don't use a field of this type in more than one template.

## Details

In the field configuration, you can set a pattern with a placeholder of '##' for the number itself.

You can also set a padding length. Shorter numbers will be left-padded with zeroes to that length.

E.g.:

A value of '12' with a padding length of '5' and a pattern of 'SEQ-##-x' will be converted to 'SEQ-00012-x'.
