# Additional required info

* What ports ( Jenkins,ssh,etc ) should be left open ?
    - 22
    - 443
    - 50000
    - 9200

* Change ssh default from 22 or it would just cause confusion ?
    - keep 22

* Is removing `su` usage privileges enough to stop switching to root/other users ?
    - root nologin instead

* Openfile/process stresholds (What requires the most, should we use it as LCD ) ?
    - 65536 