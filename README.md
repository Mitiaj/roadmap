# ROADMAP for great developer


### STEP 1. Git & Composer


#### You will need:

- [ ] PhpStorm installed on yout PC
- [ ] PHP installed on your PC (could me WAMP or XAMP)
- [ ] PHP executable available from terminal. You can just add it to PATH after installing XAMP or WAMP
- [ ] Composer. Composer is purely written in PHP and compiled to phar. You can install it globally or you can add composer.phar file to each project seperatelly. PhpStorm can do that for you.
- [ ] In PhpStorm's configuratia set PHP executable in order to get better auotocomplete.

#### Sequence:

##### GIT:

- [ ] Become familiar with PhpStorm http://phpstorm.tips/tips/
- [ ] Go through GIT documentation
- [ ] Register on https://bitbucket.com
- [ ] Register on https://github.com
- [ ] Practice in github: If terminal looks scary, you could try UI version for github: https://desktop.github.com/ or universal UI: https://tortoisegit.org/
	- [ ] Create repository
	- [ ] Clone repository
	- [ ] Open repository with PhpStorm
	- [ ] Create simple hello world application
	- [ ] commit & push
	- [ ] add ```readme.md``` file to project
	- [ ] fill information about the author
	- [ ] commit && push
- [ ] Read about feature branching in git https://www.atlassian.com/git/tutorials/comparing-workflows | https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

##### Composer:

- [ ] Get familiar with composer, what you should be able to do: 
	* Create composer package 
	* require your own composer package 
	* Require composer package from packagist.org
	
	- [ ] Create project on github
	- [ ] Clone
	- [ ] Create ```src``` folder
	- [ ] Add simple class to ```src``` folder, for example: Calculator
	- [ ] Add namespace
	- [ ] Init composer: https://getcomposer.org/doc/03-cli.md#init or PhpStorm can do that for you. It will create composer.json file in root directory of your project
	- [ ] Setup autoloading by psr-4 https://getcomposer.org/doc/04-schema.md#autoload
	- [ ] Add additional information to package. Author etc..
	- [ ] commit && push
	
	Your package is complete
	
	- [ ] Create other repository on github
	- [ ] Clone
	- [ ] Add ```index.php``` file. Our mission is to require our Calculator package via composer
	- [ ] init composer
	- [ ] setup repository you are going to use (Calculator) | https://getcomposer.org/doc/04-schema.md#repositories type: VCS (version control system)
	- [ ] require calculators master branch
	- [ ] require ```'vendor/composer/autoload.php'```
	- [ ] Try to create new calculator and call any function. It should work.
	- [ ] Commit all the work and push
	
	You just created package and required it in a project
	
##### Composer advanced:

- [ ] Using symfony components create your own frame with tutorial: http://symfony.com/doc/current/create_framework/introduction.html
- [ ] Read about dependency injection / inversion of control: http://fabien.potencier.org/what-is-dependency-injection.html
	
