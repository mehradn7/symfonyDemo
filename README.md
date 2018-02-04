Symfony Demo Application
========================

- Install Vagrant (2.0.2)
- Install Virtual Box (5.2.6)
- Clone the repository https://github.com/mehradn7/symfonyDemo.git to your development folder (for example ~/projects/symfonyDemoApp)
- Install the Homestead Vagrant box :
	* run 'git clone https://github.com/laravel/homestead.git ~/Homestead'
	* run the init script with 'bash init.sh'
	* in the 'Homestead.yaml' file, map your development folder to a folder from the virtual machine; map 'homestead.test' to the development folder located on the virtual machine
- add line '192.168.10.10     homestead.test' in the hosts file of your computer
- open 'homestead.test' in your browser