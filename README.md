# Pattern Lab Standard Edition for Twig [BETA]

The Standard Edition for Twig gives developers and designers a clean base from which to develop Twig-based patterns.

## Installing the Standard Edition for Twig

### 1. Install Composer 

Pattern Lab uses [Composer](https://getcomposer.org/) to manage project dependencies. To install Composer type the following two lines in the command line:

    curl -sS https://getcomposer.org/installer | php -- --install-dir=bin

Then close and re-open your command line terminal.

### 2. Install the Standard Edition

Use Composer's `create-project` feature to install the Standard Edition into a location of your choosing. Type:

    cd install/location/
    composer create-project pattern-lab/edition-twig-standard your-project-name && cd $_

This will create a directory called `your-project-name`.

### 3. Install a StarterKit

To install a near-empty StarterKit project as a starting point you can run:

    php core/console --starterkit --init

### 4. Generate Pattern Lab

To generate Pattern Lab for the first time and make sure everything was installed correctly type:

    php core/console --generate

To list all available commands type:

    php core/console --help

### 5. Start the server to see your Pattern Lab web site

You can use PHP's built-in web server to review your Pattern Lab project in a browser. In a new terminal window type:

    php core/console --server

And then visit [http://localhost:8080](http://localhost:8080)
