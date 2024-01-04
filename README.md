# awesome-forkbomb
A fork bomb is a type of malicious code or program that is designed to consume system resources by rapidly and exponentially creating new processes. The term "fork" refers to the system call used to create a new process in many operating systems.

When a fork bomb is executed, it starts by creating a new process. This new process then duplicates itself by invoking the fork system call, creating another identical process. This process continues recursively, with each new process creating additional processes, quickly multiplying and overwhelming the system's available resources such as CPU, memory, and process table entries.

Fork bombs are often used as a form of denial-of-service attack or as a means to disrupt or crash a system. The excessive number of processes created can lead to system slowdowns, unresponsiveness, or even a complete system freeze. Restarting the affected system is usually required to recover from the fork bomb and restore normal operation.

It's important to note that the creation and execution of fork bombs are typically considered malicious activities. Engaging in such activities without proper authorization is illegal and unethical. Fork bombs should not be used for any legitimate purpose, and it's crucial to exercise responsible and lawful use of technology.

Checkout this blog post for more information and prevention technique.
https://securioo.medium.com/11-characters-and-boom-5f1cd2b1645f
