# ABAP Continuous Integration Plugin


[![Build Status](https://ci.jenkins.io/buildStatus/icon?job=Plugins/abap-ci-plugin/master)](https://ci.jenkins.io/job/plugins/job/abap-ci/)
[![Jenkins Plugin](https://img.shields.io/jenkins/plugin/v/abap-ci.svg)](https://plugins.jenkins.io/abap-ci)
[![Issues](https://img.shields.io/github/issues/jenkinsci/abap-ci-plugin)](https://github.com/jenkinsci/abap-ci-plugin/issues)
[![Jenkins Plugin Installs](https://img.shields.io/jenkins/plugin/i/abap-ci.svg?color=blue)](https://plugins.jenkins.io/abap-ci)
[![Contributors](https://img.shields.io/github/contributors/jenkinsci/abap-ci-plugin.svg)](https://github.com/jenkinsci/abap-ci-plugin/graphs/contributors)

## Getting Started 

- Install the plugin using the `Jenkins Plugin Manager`, and restart Jenkins.
- Go to the global configuration page (`Manage Jenkins > Configure System`).
- Find the AbapCi Plugin Section and specify and the `connection info` for your ABAP development system. 
- Create a new `Jenkins job` for an ABAP Package of your ABAP Dev System (freestyle project or pipeline project) 

## Features 

This plugin provides the foundation to integrate an ABAP on premise System into Jenkins. 

Currently there are two Continuous Integration features supported: 

- running ATC checks 
- running Unit tests 
  
The plugin can be used as a build step in a free-style project or also within a pipeline project. 

## Global configuration   

![Global Jenkins Configuration](documentation/abap_ci_global_configuration.PNG/?raw=true "Global Jenkins Configuration")
 
 
## Free-style project: 
![Free-style project](documentation/freestyle_project.PNG/?raw=true "Free-style project")

 
## Pipeline project: 

![Pipeline project definition](documentation/Pipeline_definition.png/?raw=true "Pipeline project definition")

![Pipeline project output](documentation/Pipeline_output.png/?raw=true "Pipeline_output.png")
 

 
