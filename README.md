# Updating NodeJS:

Go to nodejs.org and download the latest version - uninstall (all) installed versions on your machine first.

# Updating npm:

Run

    [sudo] npm install -g npm
    
(sudo  is only required on Mac/ Linux)

# Updating the CLI

    [sudo] npm uninstall -g angular-cli @angular/cli

    npm cache verify 

    [sudo] npm install -g @angular/cli