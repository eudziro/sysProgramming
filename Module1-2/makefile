program1 = program1.cc
program2 = program2.cc
binary1 = program1
binary2 = program2
cflags = -lglfw -lGLESv2 -lm

one : $(program1)
	clang++ $(program1) -o $(binary1) $(cflags) && ./$(binary1)

two : $(program2)
	clang++ $(program2) -o $(binary2) $(cflags) && ./$(binary2)
