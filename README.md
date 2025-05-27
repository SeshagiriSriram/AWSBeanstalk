# Sample Applications for AWS Beanstalk

As it currently stands on May 27 2025, the following apps are supported

Directory Structure

- SampleNodeAppWithAngular
- SamplePHP

The SamplePHP application is based on the AWS Beanstalk samples and includes info.php (the "standard hello world" program to list system info using phpinfo(())

The Sample Angular application is based on the "Angular Tour of Heroes" application. Please see the Procfile for command to run when starting the command. 

We recommend that you look into package.json to 

- Update all depdencies and versions
- Fix any broken dependencies
- See the "scripts" available including SSR support 

NB: Package required components as app.zip for use with AWS Beanstalk. 