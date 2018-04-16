# Magento 1

Platform.sh provides [a starter kit for Magento 1 Community Edition projects](https://github.com/platformsh/platformsh-example-magento1) hosted on Platform.sh.  It is the recommended way to start a Magento 1 project on Platform.sh.

## Starting a new project

To start a new project based on this template, follow these 3 simple steps:

1. Clone this repository locally.  You may optionally remove the `origin` remote or remove the `.git` directory and re-init the project if you want a clean history.
 
2. Create a new project through the Platform.sh user interface and select "Import an existing project" when prompted.

3. Run the provided Git commands to add a Platform.sh remote and push the code to the Platform.sh repository.

That's it!  You now have a working Magneto 1 project you can build on.

## Using as a reference

You can also use this repository as a reference for your own projects, and borrow whatever code is needed. The most important parts are the `.platform.app.yaml` file and the `.platform` directory.  You will also need the `magento-build.php`, `magento-deploy.php`, and `magento-vars.php` files, as well as the supporting `Platformsh.php` library.