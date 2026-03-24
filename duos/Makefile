CC = riscv64-linux-gnu-gcc

source  = duo_pinmux.c devmem.c
object  = $(source:%.cc=%.o)

CFLAGS += -mcmodel=medany -mabi=lp64d -static

all: $(object)
	$(CC) $(CFLAGS) $(object) -o duo-pinmux

%.o: %.c
	$(CC) $(CFLAGS) -c $<

clean:
	$(RM) *.o duo-pinmux
