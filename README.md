check_cpu_proc Nagios Plugin
============================
This plugin takes in a process name and then uses the command ps to work out how much memory and cpu all the processes of that name are taking up in percentage. It will output performance data for CPU Usage Percentage, Memory Usage Percentage, VSZ, RSS and the number of processes of that name.

Options
-------

Only the -p option is required all other options are optional.

-p allows you to specify the name of the process you want to monitor (REQUIRED)

-w specify a warning for CPU percentage utilization

-c specify a critical for CPU percentage utilization

-m specify a warning for Memory percentage utilization

-n specify a critical fro Memory percentage utilization


See http://www.toms-blog.com/post/check-a-process-cpu-and-memory-with-nagios/ for more.