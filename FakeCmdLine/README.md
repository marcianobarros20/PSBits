FakeOwnCmdLine: Simple PoC for a process falsyfying its data. Run it, and then try analyze details e.g. with Process Explorer.

FakeCmdLine: Simple demonstration of a less-known (but documented) behavior of [`CreateProcess()`](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessa) function. Effectively you can put any string into the child process *Command Line* field.
<p>
<img src="https://github.com/gtworek/PSBits/blob/master/FakeCmdLine/fakecmd.gif" width="640" height="480" />
