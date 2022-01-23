hey: one two
	# Outputs "hey", since this is the first target
	echo $@

	# Outputs all prerequisites newer than the target 
	echo $?

	# Outputs all prerequisites
	echo $^

one:
	touch one

two:
	touch two

clean:
	rm -f hey one two
