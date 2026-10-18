CXX=g++
CPPFLAGS=--std=c++17

qsTest: testQS
	./testQS

partitionTest: testPartition
	./testPartition

testQS: testQS.o tddFuncs.o qs.o
	${CXX} ${CPPFLAGS} -o testQS testQS.o tddFuncs.o qs.o

testPartition: testPartition.o tddFuncs.o qs.o
	${CXX} ${CPPFLAGS} -o testPartition testPartition.o tddFuncs.o qs.o

clean:
	/bin/rm -f testPartition testQS testMerge *.o
