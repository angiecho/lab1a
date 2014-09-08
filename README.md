Lab 1: Fibonacci Numbers & Testing
======

The Fibonacci Sequence is a sequence of integers, Fib(1), Fib(2), ... that is described as follows:
```
  Fib(0) = 0
  Fib(1) = 1
  Fib(n) = Fib(n-1)+Fib(n-2) for n >= 2
```
Thus the first few numbers of the sequence are 1, 1, 2, 3, 5, 8, 13, 21, 34, 55.

You are provided with a library (as a JAR file) that contains a single class (`Fibonacci`) and a single method within that class:
```
	/**
	 * Return the n^{th} Fibonacci number.
	 * The n^{th} Fibonacci number is defined as follows:<br />
	 * 	Fib( 0 ) = 0<br />
	 * 	Fib( 1 ) = 1<br />
	 * 	Fib( n ) = Fib( n-1 ) + Fib( n-2 ) for n > 1<br />
	 * @param n
	 * @return the n^{th} Fibonacci number
	 */
	public static long getFibonacci( int n ) 
```

Your initial tasks for this part of the lab activity are to:
* clone this GitHub repository to either your own machine or to a machine in the lab;
* set up Eclipse to include the `fibonacci/Fibonacci.jar` file as a library [1];
* include the Javadoc documentation that accompanies `Fibonacci.jar` [2];
* create an appropriate class and a main( ) method so that you can test the correctness of `getFibonacci( )`;
* after running the tests, describe in a text file named `testStrategy.txt` your approach to testing, any problems uncovered and whether you consider your testing strategy efficient.

After the initial tasks:
* create a repository in your BitBucket account called `lab1a`;
* add the teaching assistant for your lab session as a user of that repository;
* clone the BitBucket repository to a local machine;
* copy the `testStrategy.txt` file to the root of the local repository;
* and push the file to the BitBucket repository.

Once you have completed these steps, proceed to Part B (http://github.com/EECE-210/lab1b) of this lab activity.

=====

1. To include a JAR file to the list of libraries Eclipse uses for a project, use the `Project > Properties` menu in Eclipse. Select `Build Path` and then select the `Libraries` tab. Then `Add External JARs`. Locate the appropriate JAR file and include it in the list of libraries. 
2. To add the Javadoc documentation, after you have add the JAR as a library, you will see a drop-down list in the `Libraries` tab of the `Build Path` menu for the library that you have just added. (This is indicated by the triangle at the left of the library name. Click on the triangle.) You will then see an item named `Javadoc location`. `Edit` this option and choose `Javadoc URL`. Browse to the path `lab1a/fibonacci/docs/` and select the folder. Click `Validate` and you should get a message that says that the location is likely valid. Select `OK` and confirm all choices.
