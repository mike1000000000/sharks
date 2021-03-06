# sharks 
Sharks is an exit code visual aid. This can be used in CI/CD pipelines like Azure/Bamboo/Jenkins so long as node is installed. 

#### Prerequisites:
Node and NPM must be installed. 

To install run:
> $ npm i


### To run this script use:

> $ node ./sharks.js {{variable}}

{{Variable}} can be replaced with `$?` in Bash or `$LastExitCode` in Powershell. 

&nbsp;
## Arguments
Passing a numbered argument will output a shark (0, 1, 2+). It's possible to output more than one shark at a time. 
> $ node ./sharks.js 1 2 3

#### Help
This argument shows the name and version of the program. 
> --help

&nbsp;
## Output examples:
```
>                        __
>     o                 /' )
>                     /'   (                          ,
>                 __/'     )                        .' `;
>  o      _.-~~~~'          ``---..__             .'   ;
>    _.--'   b)                      ``--...____.'   .'
>   (     _.      )).      `-._                     <
>    `vvvvvvv-)-.....___.-     `-.         __...--'-.'.
>      `^^^^^'-------.....`-.___.'----... .'         `.;
>                                 jgs    `-`           `
>
>  _____           _   _              _                ____                                        _  
> |  ___|   __ _  (_) | |   ___    __| |              / ___|   ___   _ __     ___   _ __    __ _  | | 
> | |_     / _` | | | | |  / _ \  / _` |    _____    | |  _   / _ \ | '_ \   / _ \ | '__|  / _` | | | 
> |  _|   | (_| | | | | | |  __/ | (_| |   |_____|   | |_| | |  __/ | | | | |  __/ | |    | (_| | | | 
> |_|      \__,_| |_| |_|  \___|  \__,_|              \____|  \___| |_| |_|  \___| |_|     \__,_| |_| ....
>
> Exit Code: (1)
```
## Warranty:
VENDOR MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY IMPLIED WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.
