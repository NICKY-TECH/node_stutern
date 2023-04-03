1. The Event Loop is a constantly running process that monitors both the callback queue and the call stack.

2.

- Timers

  executes callbacks using timers. If there are timers set to 0 ms or setImmediate(), they will run here. Incomplete timers will run in later iterations of the loop.

- Pending

  Internal phases of the event loop

- idle/Prepare

  Internal phases of the event loop

- poll

  processes I/O callbacks

- Check

  execute any setImediate() timers added in the Poll phase

- Close

  loop continues if there are more timers or I/O calls. If all timers and I/O calls are done, the loop closes and the process ends.

4. NPM5 is a package manager for javascript

5. npm init

6. npm run script-name


