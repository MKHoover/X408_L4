# X408_L4
Programmatic Virtual Machine assignment for Session 4

Instructions for setting up virtual machine and getting access to hello_http app.

1. Go to https://github.com/MKHoover/X408\_L4 and clone to your local directory.
2. CD into new directory.
3. While in new directory, clone https://github.com/drines-uc/hello\_http to get the C app.
4. In terminal, run `vagrant up`. 
5. When you want to run the application, type `vagrant ssh`.
6. Type `cd /app` which is where the synced file will be.
7. Run command `gcc -o dummyserv dummy_serve.c`.
8. Run command `./dummyserv 12344`.