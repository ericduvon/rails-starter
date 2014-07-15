1) Download Vagrant

2) Download Virtualbox

3) To set up your Vagrant development environment, navigate to your project's root directory and execute the following in the terminal:

```
vagrant up
```
4) To connect to your development environment, execute

```
vagrant ssh
```

5) Navigate to the application directory and start the rails server
```

cd /vagrant
bundle exec rails server
Go to:  http://0.0.0.0:3001/

```
6) To run tests and tasks, create another tab, start vagrant ssh and run:
```
bundle exec rake
```