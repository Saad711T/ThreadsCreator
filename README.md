# ThreadsCreator

Java program simulating thread execution in Operating Systems

## Jobs
- Creating child-threads
- Terminating threads

Inside `main()` a new **Thread** object is created by following sequence :

```java
		MyThread mt = new MyThread("Child #1");
		
		Thread newThrd = new Thread(mt);
		
		newThrd.start();
```

### Source
Code examples adapted from "Java: The Complete Reference" 
by Herbert Schildt (McGraw-Hill).

#### Purpose
For educational and personal learning purposes only.
