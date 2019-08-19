Compile:
	make
	
Run:
	./ACS [filename]

	for example: ./ACS customer.txt

-------
Modifications on original design document:
- A q_length mutex is added. It is used when any thread tries to modify the queue length.