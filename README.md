# DotnetMakeDeb-Issue-4
Reproducing https://github.com/ygoe/DotnetMakeDeb/issues/4

# Step to reproduce
1.  Add `make-deb.exe` to the root directory.
2.  Execute `build.bat`.

# Output

```
D:\Documents\Visual Studio\DotnetMakeDeb-Issue-4>make-deb.exe myapp.debspec -v
Specification file: myapp.debspec

Process is terminated due to StackOverflowException.

D:\Documents\Visual Studio\DotnetMakeDeb-Issue-4>PAUSE
Press any key to continue . . .
```
