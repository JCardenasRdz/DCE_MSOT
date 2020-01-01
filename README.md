# DCE_MSOT
A collection of code to analyze Dynamoc Contrast-Enhanced (DCE) Multispectral Optoacoustic Tomography (MSOT)

## MATLAB Interfacing Library to the ViewMSOT Proprietary File Format
### msotlib.itheramedical.com  


### INSTALL
1. Place the `msotlib_rev701` folder in your MATLAB directory. If you do not know your default directory, type `userpath` in MATLAB's command window:
```bash
>> userpath

ans =

    'C:\Users\jdata\OneDrive\Documents\MATLAB'
```
After having copied the `msotlib_rev701` folder to the MATLAB directory, type the following in the command line to verify that is was copied ( I am including the output below):

```bash
>> cd 'C:\Users\jdata\OneDrive\Documents\MATLAB'
>> pwd

ans =

    'C:\Users\jdata\OneDrive\Documents\MATLAB'

>> ls

.               ..              msotlib_rev701
```

2. `CD` to the  `MSOTBeans` folder under the `msotlib_rev701` folder:
```bash
>> cd msotlib_rev701\MSOTBeans
```

3. Add the location of two jar files under the `MSOTBeans` folder to your startup.m file
```bash
>> javaaddpath xbean.jar
>> javaaddpath msotbeans.jar
```

### CONTENTS

Listing of functions:
- `listMSOT`:	    Lists contents of a study folder
- `loadMSOT`:          Loads MSOT META information
- `loadMSOTRecon`:     Loads MSOT Reconstructions
- `loadMSOTMsp`:       Loads MSOT MSP (multispectrally processed) data
- `loadMSOTSignals`:   Loads optoacoustic Signals as acquired by the transducers


### USAGE
For usage please refer to the function documentation using help <function>
