.PHONY: clean

CFLAGS=-Wall -g

driver: driver.o rbtree.o
test_rbtree_insert : test_rbtree_insert.o rbtree.o

clean:
	rm -f driver *.o
	rm -f test_rbtree_insert *.o
