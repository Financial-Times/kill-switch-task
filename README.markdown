# Kill Switch Task

This Dropwizard task allows you to simulate OutOfMemoryExceptions to test the behaviour of your app in the unlikely
event of one.

## Usage

### In your code

environment.addTask(new KillSwitchTask());

### POST request to

http://localhost:9091/tasks/killswitch

(Or whatever the admin port of your Dropwizar app is.)