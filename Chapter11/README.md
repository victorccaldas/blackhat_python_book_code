### Notes for the readers
- You need Volatility for this chapter. Get it here https://code.google.com/archive/p/volatility/ or even better check https://github.com/volatilityfoundation/volatility. For easy ref the zip file is included here too. You can both install it or run the `vol.py` standalone in your fav folder.
- You can get Immunity Debugger (required to finalize the last pj) here https://www.immunityinc.com/products/debugger/. To use the `immlib` module required for the code, you could follow this: 

`import sys`
`sys.path.append('C:/Program Files (x86)/Immunity Inc/Immunity Debugger')`
`sys.path.append('C:/Program Files (x86)/Immunity Inc/Immunity Debugger/Libs')`

`import immlib` 

The book explain a very little-to-none about how to use Volatility. Here are some useful resources: 
-https://support.eset.com/en/kb380-how-do-i-generate-a-memory-dump-manually
- https://heisenberk.github.io/Profile-Memory-Dump/
- https://book.hacktricks.xyz/forensics/basic-forensic-methodology/memory-dump-analysis/volatility-examples
- https://github.com/volatilityfoundation/volatility/wiki
- This is specific if you're running win10 https://blog.cyberhacktics.com/memory-forensics-on-windows-10-with-volatility/ 

Also, dealing with Windows registry, those should come in handy:
- https://www.top-password.com/blog/tag/windows-sam-registry-file/ 
- https://en.wikipedia.org/wiki/Security_Account_Manager
- https://ad-pdf.s3.amazonaws.com/Registry%20Offsets%209-8-08.pdf