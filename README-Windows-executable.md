## Using the Windows executable

1. Clone this repository using the [GitHub application for Windows](http://windows.github.com/).
1. Use the `cf.exe` file in the root of this repository from the command prompt, e.g:

    C:\Users\Administrator\Documents\GitHub\cf>cf.exe target api.run.pivotal.io


## Creating your own Windows executable

1. [Download and install Ruby](rubyinstaller.org).
1. `[from anywhere]>gem update --system`
1. `[from anywhere]>gem install bundler`
1. `[from anywhere]>gem install ocra`
1. Clone this repository using the [GitHub application for Windows](http://windows.github.com/).
1. `C:\Users\Administrator\Documents\GitHub\cf>bundle`
1. `C:\Users\Administrator\Documents\GitHub\cf>ocra --console bin\cf`

Note this last command will create a new `cf.exe` in the root directory of the repository, overwriting the previous one.
