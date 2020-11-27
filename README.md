# CSharp-Compiler-Win-Linux
Compile C# To Windows Executable On Linux

## Usage
### How To Use CSharp-Compiler-Win-Linux 32Bit Version
1. Install Dependencies In Debian/Ubuntu/Kali/Parrot Sec OS Linux `sudo apt-get update && sudo apt-get install mono-complete mono-devel git -y`
2. Git Clone Repo `git clone https://github.com/rc-chuah/CSharp-Compiler-Win-Linux`
3. Change Directory `cd CSharp-Compiler-Win-Linux`
4. Give execution permission `chmod +x cs-compiler-32bit.sh`
5. Run script `./cs-compiler-32bit.sh <options>`
### How To Use CSharp-Compiler-Win-Linux 64Bit Version
1. Install Dependencies In Debian/Ubuntu/Kali/Parrot Sec OS Linux `sudo apt-get update && sudo apt-get install mono-complete mono-devel git -y`
2. Git Clone Repo `git clone https://github.com/rc-chuah/CSharp-Compiler-Win-Linux`
3. Change Directory `cd CSharp-Compiler-Win-Linux`
4. Give execution permission `chmod +x cs-compiler-64bit.sh`
5. Run script `./cs-compiler-64bit.sh <options>`
### How To Use CSharp-Compiler-Win-Linux Itanium Version
1. Install Dependencies In Debian/Ubuntu/Kali/Parrot Sec OS Linux `sudo apt-get update && sudo apt-get install mono-complete mono-devel git -y`
2. Git Clone Repo `git clone https://github.com/rc-chuah/CSharp-Compiler-Win-Linux`
3. Change Directory `cd CSharp-Compiler-Win-Linux`
4. Give execution permission `chmod +x cs-compiler-itanium.sh`
5. Run script `./cs-compiler-itanium.sh <options>`
### How To Use CSharp-Compiler-Win-Linux Arm Version
1. Install Dependencies In Debian/Ubuntu/Kali/Parrot Sec OS Linux `sudo apt-get update && sudo apt-get install mono-complete mono-devel git -y`
2. Git Clone Repo `git clone https://github.com/rc-chuah/CSharp-Compiler-Win-Linux`
3. Change Directory `cd CSharp-Compiler-Win-Linux`
4. Give execution permission `chmod +x cs-compiler-arm.sh`
5. Run script `./cs-compiler-arm.sh <options>`
### CSharp-Compiler-Win-Linux 32Bit Version Options
```
Usage: cs-compiler-32bit.sh [options] source-files
   --about              About the Mono C# compiler      
   -addmodule:M1[,Mn]   Adds the module to the generated assembly                                            
   -checked[+|-]        Sets default aritmetic overflow context
   -clscheck[+|-]       Disables CLS Compliance verifications                                                
   -codepage:ID         Sets code page to the one in ID (number, utf8, reset)                                
   -define:S1[;S2]      Defines one or more conditional symbols (short: -d)                                  
   -debug[+|-], -g      Generate debugging information                                                       
   -delaysign[+|-]      Only insert the public key into the assembly (no signing)
   -doc:FILE            Process documentation comments to XML file
   -fullpaths           Any issued error or warning uses absolute file path
   -help                Lists all compiler options (short: -?)
   -keycontainer:NAME   The key pair container used to sign the output assembly
   -keyfile:FILE        The key file used to strongname the ouput assembly
   -langversion:TEXT    Specifies language version: ISO-1, ISO-2, 3, 4, 5, 6, Default or Experimental
   -lib:PATH1[,PATHn]   Specifies the location of referenced assemblies
   -main:CLASS          Specifies the class with the Main method (short: -m)
   -noconfig            Disables implicitly referenced assemblies
   -nostdlib[+|-]       Does not reference mscorlib.dll library
   -nowarn:W1[,Wn]      Suppress one or more compiler warnings
   -optimize[+|-]       Enables advanced compiler optimizations (short: -o)
   -out:FILE            Specifies output assembly name
   -pathmap:K=V[,Kn=Vn] Sets a mapping for source path names used in generated output
   -pkg:P1[,Pn]         References packages P1..Pn
   -platform:ARCH       Specifies the target platform of the output assembly
                        ARCH can be one of: anycpu, anycpu32bitpreferred, arm,
                        x86, x64 or itanium. The default is anycpu.
   -recurse:SPEC        Recursively compiles files according to SPEC pattern
   -reference:A1[,An]   Imports metadata from the specified assembly (short: -r)
   -reference:ALIAS=A   Imports metadata using specified extern alias (short: -r)
   -sdk:VERSION         Specifies SDK version of referenced assemblies
                        VERSION can be one of: 2, 4, 4.5 (default) or a custom value
   -target:KIND         Specifies the format of the output assembly (short: -t)
                        KIND can be one of: exe, winexe, library, module
   -unsafe[+|-]         Allows to compile code which uses unsafe keyword
   -warnaserror[+|-]    Treats all warnings as errors
   -warnaserror[+|-]:W1[,Wn] Treats one or more compiler warnings as errors
   -warn:0-4            Sets warning level, the default is 4 (short -w:)
   -helpinternal        Shows internal and advanced compiler options

Resources:
   -linkresource:FILE[,ID] Links FILE as a resource (short: -linkres)
   -resource:FILE[,ID]     Embed FILE as a resource (short: -res)
   -win32res:FILE          Specifies Win32 resource file (.res)
   -win32icon:FILE         Use this icon for the output
   @file                   Read response file for more options

Options can be of the form -option or /option
```
### CSharp-Compiler-Win-Linux 64Bit Version Options
```
Usage: cs-compiler-64bit.sh [options] source-files
   --about              About the Mono C# compiler      
   -addmodule:M1[,Mn]   Adds the module to the generated assembly                                            
   -checked[+|-]        Sets default aritmetic overflow context
   -clscheck[+|-]       Disables CLS Compliance verifications                                                
   -codepage:ID         Sets code page to the one in ID (number, utf8, reset)                                
   -define:S1[;S2]      Defines one or more conditional symbols (short: -d)                                  
   -debug[+|-], -g      Generate debugging information                                                       
   -delaysign[+|-]      Only insert the public key into the assembly (no signing)
   -doc:FILE            Process documentation comments to XML file
   -fullpaths           Any issued error or warning uses absolute file path
   -help                Lists all compiler options (short: -?)
   -keycontainer:NAME   The key pair container used to sign the output assembly
   -keyfile:FILE        The key file used to strongname the ouput assembly
   -langversion:TEXT    Specifies language version: ISO-1, ISO-2, 3, 4, 5, 6, Default or Experimental
   -lib:PATH1[,PATHn]   Specifies the location of referenced assemblies
   -main:CLASS          Specifies the class with the Main method (short: -m)
   -noconfig            Disables implicitly referenced assemblies
   -nostdlib[+|-]       Does not reference mscorlib.dll library
   -nowarn:W1[,Wn]      Suppress one or more compiler warnings
   -optimize[+|-]       Enables advanced compiler optimizations (short: -o)
   -out:FILE            Specifies output assembly name
   -pathmap:K=V[,Kn=Vn] Sets a mapping for source path names used in generated output
   -pkg:P1[,Pn]         References packages P1..Pn
   -platform:ARCH       Specifies the target platform of the output assembly
                        ARCH can be one of: anycpu, anycpu32bitpreferred, arm,
                        x86, x64 or itanium. The default is anycpu.
   -recurse:SPEC        Recursively compiles files according to SPEC pattern
   -reference:A1[,An]   Imports metadata from the specified assembly (short: -r)
   -reference:ALIAS=A   Imports metadata using specified extern alias (short: -r)
   -sdk:VERSION         Specifies SDK version of referenced assemblies
                        VERSION can be one of: 2, 4, 4.5 (default) or a custom value
   -target:KIND         Specifies the format of the output assembly (short: -t)
                        KIND can be one of: exe, winexe, library, module
   -unsafe[+|-]         Allows to compile code which uses unsafe keyword
   -warnaserror[+|-]    Treats all warnings as errors
   -warnaserror[+|-]:W1[,Wn] Treats one or more compiler warnings as errors
   -warn:0-4            Sets warning level, the default is 4 (short -w:)
   -helpinternal        Shows internal and advanced compiler options

Resources:
   -linkresource:FILE[,ID] Links FILE as a resource (short: -linkres)
   -resource:FILE[,ID]     Embed FILE as a resource (short: -res)
   -win32res:FILE          Specifies Win32 resource file (.res)
   -win32icon:FILE         Use this icon for the output
   @file                   Read response file for more options

Options can be of the form -option or /option
```
### CSharp-Compiler-Win-Linux Itanium Version Options
```
Usage: cs-compiler-itanium.sh [options] source-files
   --about              About the Mono C# compiler      
   -addmodule:M1[,Mn]   Adds the module to the generated assembly                                            
   -checked[+|-]        Sets default aritmetic overflow context
   -clscheck[+|-]       Disables CLS Compliance verifications                                                
   -codepage:ID         Sets code page to the one in ID (number, utf8, reset)                                
   -define:S1[;S2]      Defines one or more conditional symbols (short: -d)                                  
   -debug[+|-], -g      Generate debugging information                                                       
   -delaysign[+|-]      Only insert the public key into the assembly (no signing)
   -doc:FILE            Process documentation comments to XML file
   -fullpaths           Any issued error or warning uses absolute file path
   -help                Lists all compiler options (short: -?)
   -keycontainer:NAME   The key pair container used to sign the output assembly
   -keyfile:FILE        The key file used to strongname the ouput assembly
   -langversion:TEXT    Specifies language version: ISO-1, ISO-2, 3, 4, 5, 6, Default or Experimental
   -lib:PATH1[,PATHn]   Specifies the location of referenced assemblies
   -main:CLASS          Specifies the class with the Main method (short: -m)
   -noconfig            Disables implicitly referenced assemblies
   -nostdlib[+|-]       Does not reference mscorlib.dll library
   -nowarn:W1[,Wn]      Suppress one or more compiler warnings
   -optimize[+|-]       Enables advanced compiler optimizations (short: -o)
   -out:FILE            Specifies output assembly name
   -pathmap:K=V[,Kn=Vn] Sets a mapping for source path names used in generated output
   -pkg:P1[,Pn]         References packages P1..Pn
   -platform:ARCH       Specifies the target platform of the output assembly
                        ARCH can be one of: anycpu, anycpu32bitpreferred, arm,
                        x86, x64 or itanium. The default is anycpu.
   -recurse:SPEC        Recursively compiles files according to SPEC pattern
   -reference:A1[,An]   Imports metadata from the specified assembly (short: -r)
   -reference:ALIAS=A   Imports metadata using specified extern alias (short: -r)
   -sdk:VERSION         Specifies SDK version of referenced assemblies
                        VERSION can be one of: 2, 4, 4.5 (default) or a custom value
   -target:KIND         Specifies the format of the output assembly (short: -t)
                        KIND can be one of: exe, winexe, library, module
   -unsafe[+|-]         Allows to compile code which uses unsafe keyword
   -warnaserror[+|-]    Treats all warnings as errors
   -warnaserror[+|-]:W1[,Wn] Treats one or more compiler warnings as errors
   -warn:0-4            Sets warning level, the default is 4 (short -w:)
   -helpinternal        Shows internal and advanced compiler options

Resources:
   -linkresource:FILE[,ID] Links FILE as a resource (short: -linkres)
   -resource:FILE[,ID]     Embed FILE as a resource (short: -res)
   -win32res:FILE          Specifies Win32 resource file (.res)
   -win32icon:FILE         Use this icon for the output
   @file                   Read response file for more options

Options can be of the form -option or /option
```
### CSharp-Compiler-Win-Linux Arm Version Options
```
Usage: cs-compiler-arm.sh [options] source-files
   --about              About the Mono C# compiler      
   -addmodule:M1[,Mn]   Adds the module to the generated assembly                                            
   -checked[+|-]        Sets default aritmetic overflow context
   -clscheck[+|-]       Disables CLS Compliance verifications                                                
   -codepage:ID         Sets code page to the one in ID (number, utf8, reset)                                
   -define:S1[;S2]      Defines one or more conditional symbols (short: -d)                                  
   -debug[+|-], -g      Generate debugging information                                                       
   -delaysign[+|-]      Only insert the public key into the assembly (no signing)
   -doc:FILE            Process documentation comments to XML file
   -fullpaths           Any issued error or warning uses absolute file path
   -help                Lists all compiler options (short: -?)
   -keycontainer:NAME   The key pair container used to sign the output assembly
   -keyfile:FILE        The key file used to strongname the ouput assembly
   -langversion:TEXT    Specifies language version: ISO-1, ISO-2, 3, 4, 5, 6, Default or Experimental
   -lib:PATH1[,PATHn]   Specifies the location of referenced assemblies
   -main:CLASS          Specifies the class with the Main method (short: -m)
   -noconfig            Disables implicitly referenced assemblies
   -nostdlib[+|-]       Does not reference mscorlib.dll library
   -nowarn:W1[,Wn]      Suppress one or more compiler warnings
   -optimize[+|-]       Enables advanced compiler optimizations (short: -o)
   -out:FILE            Specifies output assembly name
   -pathmap:K=V[,Kn=Vn] Sets a mapping for source path names used in generated output
   -pkg:P1[,Pn]         References packages P1..Pn
   -platform:ARCH       Specifies the target platform of the output assembly
                        ARCH can be one of: anycpu, anycpu32bitpreferred, arm,
                        x86, x64 or itanium. The default is anycpu.
   -recurse:SPEC        Recursively compiles files according to SPEC pattern
   -reference:A1[,An]   Imports metadata from the specified assembly (short: -r)
   -reference:ALIAS=A   Imports metadata using specified extern alias (short: -r)
   -sdk:VERSION         Specifies SDK version of referenced assemblies
                        VERSION can be one of: 2, 4, 4.5 (default) or a custom value
   -target:KIND         Specifies the format of the output assembly (short: -t)
                        KIND can be one of: exe, winexe, library, module
   -unsafe[+|-]         Allows to compile code which uses unsafe keyword
   -warnaserror[+|-]    Treats all warnings as errors
   -warnaserror[+|-]:W1[,Wn] Treats one or more compiler warnings as errors
   -warn:0-4            Sets warning level, the default is 4 (short -w:)
   -helpinternal        Shows internal and advanced compiler options

Resources:
   -linkresource:FILE[,ID] Links FILE as a resource (short: -linkres)
   -resource:FILE[,ID]     Embed FILE as a resource (short: -res)
   -win32res:FILE          Specifies Win32 resource file (.res)
   -win32icon:FILE         Use this icon for the output
   @file                   Read response file for more options

Options can be of the form -option or /option
```
