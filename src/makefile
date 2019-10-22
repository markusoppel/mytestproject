FOR= gfortran
FOROPT=   -O2  

OBJ= test.o

test.x: $(OBJ)
	$(FOR) $(FOROPT) -o test.x $(OBJ) 

.f.o:   
	$(FOR)  $(FOROPT) -c $*.f 

clean:
	rm -rf *.o *.x

check: test.x
	./test.x 
	

