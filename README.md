On feature1 the scenario is as follows:

1- Dev1 writes on feature1:
"line1 feature1 by dev1"
"line2 feature1 by dev1"
2- Dev1 adds and commits with a message "line 1 and 2 on feature1 by dev1"
3- Dev1 pushs to origin/feature1
4- Dev2 writes on feature1:
"line1 feature1 by dev2"
"line2 feature1 by dev2"
5- Dev2 adds and commits with a message "line 1 and 2 on feature1 by dev2"
6- Dev2 pushs to origin/feature1 but gets rejected
7- Dev2 executes pull -r and resolves conflicts
8- Dev2 pushs again to orgin/feature1
9- Dev1 writes on feature1:
"line3 feature1 by dev1"
10- Dev1 adds and commits with a message "line 3 on feature1 by dev1"
11- Dev1 pushs to origin/feature1 but gets rejected
12- Dev1 executes pull -r and resolves conflicts
13- Dev1 pushs again to origin/feature1

/////////////////////////////////////////////////////////////////////////////////////////////
