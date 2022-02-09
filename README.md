# Cpp-exception-handling
In this challenge, the task is to debug the existing code to successfully execute all provided test files.

You are required to extend the existing code so that it handles std::invalid_argument exception properly. More specifically, you have to extend the implementation of process_input function. It takes integer n as an argument and has to work as follows:

It calls function largest_proper_divisor(n).
If this call returns a value without raising an exception, it should print in a single line result=d where d is the returned value.
Otherwise, if the call raises a std::invalid_argument exception, it has to print in a single line the string representation of the raised exception, i.e. its message.
Finally, no matter if the exception is raised or not, it should print in a single line returning control flow to caller after any other previously printed output.
To keep the code quality high, you are advised to have exactly one line printing returning control flow to caller in the body of process_input function.

Your function will be tested against several cases by the locked template code.
