# Vagrant - Robot Framework

Setup a virtualbox vm with ubuntu-18.04-desktop and [RobotFramework](http://robotframework.org/) preinstalled.

These examples were generated and tested using:
* **Host OS:** Windows 10
* **VM OS:** Ubuntu 18.04
* **VirtualBox:** 5.2.12r122591
* **Vagrant:** 2.1.1

The examples are based on the [official examples](http://robotframework.org/#examples), experience and experiments.

## Prerequisites
* [VirtualBox](https://www.virtualbox.org/)
* [Vagrant](https://www.vagrantup.com/)

## Installation
Provision and run the vagrant box inside this folder:

```
vagrant up
```

## Examples

### Example 1: Simple Browser Test
See detailes about example1 [here](examples/example1/example1.md)
The example will run a simple browser test example and create a report which you can inspect.

### Example 2: Run tests from VM to Host
See detailes about example2 [here](examples/example2/example2.md)
The example will run a simple test example from the VM to the host machine and create a report which you can inspect.

### Example 3: Merge Reports
See detailes about example3 [here](examples/example3/example3.md)
The example will run a simple browser test example and create a report which then will be merged with other reports.

### Example 4: Import ExampleLibrary
See detailes about example4 [here](examples/example4/example4.md)
The example will create a simple custom ExampleLibrary in python and use it inside the robot framework test suite.
