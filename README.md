# Cooperari repl.it demo [![Run on Repl.it](run_on_replit.svg)](https://repl.it/github/cooperari/cooperari-replit)

1. In the replit command line configure the PATH using:

  ```
export PATH=$HOME/cooperari-replit/bin:$PATH
  ```

2. Access the examples directory and execute

  ```
cjavac
  ```

  to compile the examples.

3. Run the examples in cooperative mode using 

  ```  
cjunit org.cooperari.examples.All
  ```
 or in preemptive mode using 

  ```
cjunitp org.cooperari.examples.All
  ```
