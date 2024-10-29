**Difference between server,virtual machine,containerizationse**

+----------------------+-----------------------+-----------------------+
| **Server**           | **Virtual machine**   | **containerization**  |
+----------------------+-----------------------+-----------------------+
| A physical machine   | An emulation of a     | A lightweight method  |
| or hardware that     | physical computer     | of virtualization     |
| provides             | that runs an          | that packages         |
| resour               | operating system and  | applications and      |
| ces,data,services,or | applications just     | their dependencies    |
| programs to other    | like a real server    | together in isolated  |
| computers over a     | but on a virtualized  | environments called   |
| network.             | environment.          | containers.           |
|                      |                       |                       |
| It can run multiple  | Operates on a         | Shares the host OS    |
| applications and     | hypervisor has its    | kernal,which makes    |
| services to a single | own OS,which can      | containers more       |
| task,requires space  | differ from the host  | efficient than        |
| and maintenance.     | OS,uses resourses     | vm.faster startup     |
|                      | from the physical     |                       |
|                      | server.               | times,uses tools like |
|                      |                       | kubernetes for        |
|                      |                       | management.           |
+----------------------+-----------------------+-----------------------+
