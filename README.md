# PiccoloDocsTemplate

Simply

```
Pkg.add(url="https://github.com/harmoniqs/doc_template", rev="v0.2.0")
Pkg.instantiate()
```

and then add a

```
using MyPackageHere
using PiccoloDocsTemplate

pages = [ ... ]

generate_docs( ... )
```