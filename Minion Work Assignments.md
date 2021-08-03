New challenge "Minion Work Assignments" added to your home folder.
Time to solve: 168 hours.
foobar:~/ stefan.caraiman$ ls
minion-work-assignments
journal.txt
start_here.txt
foobar:~/ stefan.caraiman$ pwd
/home/stefan.caraiman
foobar:~/ stefan.caraiman$ cat journal.txt 
Success! You've managed to infiltrate Commander Lambda's evil organization, and finally earned yourself an entry-level position as a Minion on their space station. From here, you just might be able to subvert Commander Lambda's plans to use the LAMBCHOP doomsday device to destroy Bunny Planet. Problem is, Minions are the lowest of the low in the Lambda hierarchy. Better buck up and get working, or you'll never make it to the top...

Commander Lambda sure is a task-master, aren't they? You're being worked to the bone!
foobar:~/ stefan.caraiman$ ls
minion-work-assignments
journal.txt
start_here.txt
foobar:~/ stefan.caraiman$ cat start_here.txt 
Type request to request a challenge. Type help for a list of commands.
foobar:~/ stefan.caraiman$ cd minion-work-assignments/
foobar:~/minion-work-assignments stefan.caraiman$ ll
ll: command not found. Type help for a list of commands
foobar:~/minion-work-assignments stefan.caraiman$ ls
Solution.java
constraints.txt
readme.txt
solution.py
foobar:~/minion-work-assignments stefan.caraiman$ ls -l
ls: -l: No such file or directory
foobar:~/minion-work-assignments stefan.caraiman$ ls -la
ls: -la: No such file or directory
foobar:~/minion-work-assignments stefan.caraiman$ ll
ll: command not found. Type help for a list of commands
foobar:~/minion-work-assignments stefan.caraiman$ ls
Solution.java
constraints.txt
readme.txt
solution.py
foobar:~/minion-work-assignments stefan.caraiman$ cat readme.txt 
Minion Work Assignments
=======================

Commander Lambda's minions are upset! They're given the worst jobs on the whole space station, and some of them are starting to complain that even those worst jobs are being allocated unfairly. If you can fix this problem, it'll prove your chops to Commander Lambda so you can get promoted!

Minions' tasks are assigned by putting their ID numbers into a list, one time for each day they'll work that task. As shifts are planned well in advance, the lists for each task will contain up to 99 integers. When a minion is scheduled for the same task too many times, they'll complain about it until they're taken off the task completely. Some tasks are worse than others, so the number of scheduled assignments before a minion will refuse to do a task varies depending on the task.  You figure you can speed things up by automating the removal of the minions who have been assigned a task too many times before they even get a chance to start complaining.

Write a function called solution(data, n) that takes in a list of less than 100 integers and a number n, and returns that same list but with all of the numbers that occur more than n times removed entirely. The returned list should retain the same ordering as the original list - you don't want to mix up those carefully-planned shift rotations! For instance, if data was [5, 10, 15, 10, 7] and n was 1, solution(data, n) would return the list [5, 15, 7] because 10 occurs twice, and thus was removed from the list entirely.

Languages
=========

To provide a Python solution, edit solution.py
To provide a Java solution, edit Solution.java

Test cases
==========
Your code should pass the following test cases.
Note that it may also be run against hidden test cases not shown here.

-- Python cases --
Input:
solution.solution([1, 2, 3], 0)
Output:
    

Input:
solution.solution([1, 2, 2, 3, 3, 3, 4, 5, 5], 1)
Output:
    1,4

-- Java cases --
Input:
Solution.solution({1, 2, 3}, 0)
Output:
    

Input:
Solution.solution({1, 2, 2, 3, 3, 3, 4, 5, 5}, 1)
Output:
    1,4

Use verify [file] to test your solution and see how it does. When you are finished editing your code, use submit [file] to submit your answer. If your solution passes the test cases, it will be removed from your home folder.
foobar:~/minion-work-assignments stefan.caraiman$ cat solution.py 
def​ ​solution(data,​ ​n):​ ​
​ ​​ ​​ ​​ ​#​ ​Your​ ​code​ ​here
foobar:~/minion-work-assignments stefan.caraiman$ ps
ps: command not found. Type help for a list of commands
foobar:~/minion-work-assignments stefan.caraiman$ vim
vim: command not found. Type help for a list of commands
foobar:~/minion-work-assignments stefan.caraiman$ ls
Solution.java
constraints.txt
readme.txt
solution.py
foobar:~/minion-work-assignments stefan.caraiman$ help
Use the following shell commands:

cd	change directory [dir_name]
cat	print file [file_name]
deleteme	delete all of your data associated with foobar
edit	open file in editor [file_name]
feedback	provide feedback on foobar
less	print a file a page at a time [file_name]
ls	list directory contents [dir_name]
request	request new challenge
status	print progress
submit	submit final solution file for assessment [file_name]
verify	runs tests on solution file [file_name]

Keyboard help:

⌘ + S	save the open file [when editor is focused]
⌘ + E	close the editor [when editor is focused]

Toggle between the editor and terminal using ESC followed by TAB, then activate with ENTER.

foobar:~/minion-work-assignments stefan.caraiman$ status
You've not yet solved a challenge.
foobar:~/minion-work-assignments stefan.caraiman$ ls
Solution.java
constraints.txt
readme.txt
solution.py
foobar:~/minion-work-assignments stefan.caraiman$ cat constraints.txt 
Java
====
Your code will be compiled using standard Java 8. All tests will be run by calling the solution() method inside the Solution class

Execution time is limited.

Wildcard imports and some specific classes are restricted (e.g. java.lang.ClassLoader). You will receive an error when you verify your solution if you have used a blacklisted class.

Third-party libraries, input/output operations, spawning threads or processes and changes to the execution environment are not allowed.

Your solution must be under 32000 characters in length including new lines and and other non-printing characters.

Python
======
Your code will run inside a Python 2.7.13 sandbox. All tests will be run by calling the solution() function.

Standard libraries are supported except for bz2, crypt, fcntl, mmap, pwd, pyexpat, select, signal, termios, thread, time, unicodedata, zipimport, zlib.

Input/output operations are not allowed.

Your solution must be under 32000 characters in length including new lines and and other non-printing characters.
foobar:~/minion-work-assignments stefan.caraiman$ ls -la
ls: -la: No such file or directory
foobar:~/minion-work-assignments stefan.caraiman$ ls
Solution.java
constraints.txt
readme.txt
solution.py
foobar:~/minion-work-assignments stefan.caraiman$ cat readme.txt 
Minion Work Assignments
=======================

Commander Lambda's minions are upset! They're given the worst jobs on the whole space station, and some of them are starting to complain that even those worst jobs are being allocated unfairly. If you can fix this problem, it'll prove your chops to Commander Lambda so you can get promoted!

Minions' tasks are assigned by putting their ID numbers into a list, one time for each day they'll work that task. As shifts are planned well in advance, the lists for each task will contain up to 99 integers. When a minion is scheduled for the same task too many times, they'll complain about it until they're taken off the task completely. Some tasks are worse than others, so the number of scheduled assignments before a minion will refuse to do a task varies depending on the task.  You figure you can speed things up by automating the removal of the minions who have been assigned a task too many times before they even get a chance to start complaining.

Write a function called solution(data, n) that takes in a list of less than 100 integers and a number n, and returns that same list but with all of the numbers that occur more than n times removed entirely. The returned list should retain the same ordering as the original list - you don't want to mix up those carefully-planned shift rotations! For instance, if data was [5, 10, 15, 10, 7] and n was 1, solution(data, n) would return the list [5, 15, 7] because 10 occurs twice, and thus was removed from the list entirely.

Languages
=========

To provide a Python solution, edit solution.py
To provide a Java solution, edit Solution.java

Test cases
==========
Your code should pass the following test cases.
Note that it may also be run against hidden test cases not shown here.

-- Python cases --
Input:
solution.solution([1, 2, 3], 0)
Output:
    

Input:
solution.solution([1, 2, 2, 3, 3, 3, 4, 5, 5], 1)
Output:
    1,4

-- Java cases --
Input:
Solution.solution({1, 2, 3}, 0)
Output:
    

Input:
Solution.solution({1, 2, 2, 3, 3, 3, 4, 5, 5}, 1)
Output:
    1,4

Use verify [file] to test your solution and see how it does. When you are finished editing your code, use submit [file] to submit your answer. If your solution passes the test cases, it will be removed from your home folder.
foobar:~/minion-work-assignments stefan.caraiman$ edit solution.py 
foobar:~/minion-work-assignments stefan.caraiman$ ls
Solution.java
constraints.txt
readme.txt
solution.py
foobar:~/minion-work-assignments stefan.caraiman$ verify solution.py 
Verifying solution...
All test cases passed. Use submit solution.py to submit your solution
foobar:~/minion-work-assignments stefan.caraiman$ cat solution.py 
def​ ​solution(data,​ ​n):​ ​
​ ​​ ​​ ​​ ​#​ ​Your​ ​code​ ​here
​ ​​ ​​ ​​ ​return​ ​[x​ ​for​ ​x​ ​in​ ​data​ ​if​ ​data.count(x)​ ​<=​ ​n]
foobar:~/minion-work-assignments stefan.caraiman$ edit solution.py 
foobar:~/minion-work-assignments stefan.caraiman$ verify solution.py 
Verifying solution...
Test 1 passed!
Test 2 passed!
Test 3 failed  [Hidden]
Test 4 passed! [Hidden]
Test 5 failed  [Hidden]
Test 6 passed! [Hidden]
Test 7 failed  [Hidden]
Test 8 passed! [Hidden]
Test 9 failed  [Hidden]
foobar:~/minion-work-assignments stefan.caraiman$ verify solution.py 
Verifying solution...
All test cases passed. Use submit solution.py to submit your solution
foobar:~/minion-work-assignments stefan.caraiman$ submit solution.py 
Are you sure you want to submit your solution?
[Y]es or [N]o: Y
Submitting solution...
You survived a week in Commander Lambda's organization, and you even managed to get yourself promoted. Hooray! Henchmen still don't have the kind of security access you'll need to take down Commander Lambda, though, so you'd better keep working. Chop chop!
Submission: SUCCESSFUL. Completed in: 26 mins, 11 secs.




                             /@
                            @~/@      @@
                            @~~/ %    @$%@
                           @~(((((%  %/////@
                           @((//////@~//~~@
                            @(//// @///////@
                              @//% @~~~/~~@
                             /@$$$ @////~~/@           @@///%$$@
                           @    %/@%//$///@@        @/%/////  $//@@\
                           @$   ////(((((///~ @   $@@/////~ ~~~~///////@@     //
                          @$   ///@@@((((/////@//%%        ~~~~~~~~/////@  $@@//@/$
                         @$   ///(@  @((((////%         ~~~~~~~////////////@$       @
                         @    //((@@@((((//             ~~~~~~~~~~/////////@      @@
                        @ ~      (((((((((             ~~~~~~~~~~//////////@      @
                          @       ((((((              ~ ~~~~~~~~///////////@$   /@@
                          @@/$                  ~~~~~~~~~~~~/////////////@ @@@
                             //@@@%%/~~             ~~~~~~~///////$$$$$$
                                  @$$~             %%%$%  ~~~~~~~~///@
                                $           //@@@@   $  ~~~~~~~~////@
                                $~~~~~     @@@/\\     @@    ~~~~((($@
                                @$~~~    $@@            @/~~~~~~(%%%@
                              @~~~~~@@%                @(((((((((%%%@
                             @~~~~@@                      @(((((((((@
                             //%$$@                        @((((((((@
                               @@//                          @%%%%@
                                                              @@@
Level 1 complete
You are now on level 2
Challenges left to complete level: 2

Level 1: 100% [==========================================]
Level 2:   0% [..........................................]
Level 3:   0% [..........................................]
Level 4:   0% [..........................................]
Level 5:   0% [..........................................]

Type request to request a new challenge now, or come back later.
foobar:~/ stefan.caraiman$ request
Requesting challenge...