diary.exe : memo.o cal.o main.o
		gcc -o diary_exe memo.o cal.o main.o

memo.o : memo.c
		gcc -c -o memo.o memo.c

cal.o : memo.c
		gcc -c -o cal.o cal.c

main.o : main.c
		gcc -c -o main.o main.c

clean :
		rm *.o diary_exe
