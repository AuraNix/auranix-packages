# AuraNix Packages

### Here lies the official repositories for AuraNix

## Adding and building custom packages
### Setup

1. Clone this repository to a memorable location (ideally in your home folder)
2. Rename the examples folder to the name of your custom repo
3. Use the layout and scripts in it as the basis for whatever packages you add

### Adding your repo to Astral

There's a couple ways to go about this

#### What's 'Officially' Supported
Just add the URL of your custom repo to your astral.conf under [Custom Repos]

There's also a couple ways you can add the URL:

1. If you just want to keep the repo local, use /path/to/your/repo instead of a URL
2. If you want to use your repo across multiple installs, make packages available that aren't in the main repos to other users, etc.
    * Fork this repo
    * Add your packages
    * Add your repo to [Custom Repos]

#### What's 'Unofficially' Supported but Should Still Work
If you *really* want to, you can completely replace our repos with yours and the steps to do so are as follows:

1. Follow setup but ignore the examples folder aside from using the scripts as a basic for your packages
2. Add your package(s) to community
3. From here you can do one of two things
    * Keep your repo local and replace the repo URL under [Main Repos] in astral.conf with the /path/to/your/repo
    * Fork, add packages, and replace the main repo URL
        * If you do this, please submit a pull request so that we can add your packages to community