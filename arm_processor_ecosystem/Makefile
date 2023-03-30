TARGET=ecosystem
CC=dot
CFLAGS=-Tsvg

$(TARGET).svg: $(TARGET).dot
	$(CC) $(CFLAGS) $< -o $@

clean:
	rm $(TARGET).svg
