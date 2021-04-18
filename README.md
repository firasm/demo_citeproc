# README

To use pandoc to convert this md file to a pdf, run the following:

```
pandoc --bibliography bibliography.bib -o test.pdf test.md  --citeproc
```

## Known issues

I would like to print out the full bibliographic record in the middle of the document. This is possible in regular latex using \bibentry (part of the natbib package).
