# network-block
Enables network blocking for specific classrooms:
1. Each block has its own file.
2. Blocks applies for 2h only when the file exists (naming as `classroom-weekday-start`). 
3. This is the list of valid blocks:
    - ada-mon-19
    - ada-tue-19
    - ada-wed-16
    - torvalds-wed-19
    - torvalds-thu-19
    - torvalds-fri-16
4. In order to disable a block, **DO NOT DELETE THE FILE**, just append `-disabled` to the file name.