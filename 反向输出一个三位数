#include <stdio.h>

int main () {
	unsigned n;
	scanf ("%d", &n);
	
	/* Get the hundreds/tens/ones place for input number */
	unsigned hundr, ten, one, tenone;
	hundr = n / 100;
	tenone = n % 100;
	ten = tenone / 10;
	one = tenone % 10;
	
	/* Calulate the reverse number */
	unsigned rn = 100 * one + 10 * ten + hundr;
	
	/* Output for rn */
	if (one == 0) {
		printf ("%d", 0);
		if (ten == 0) {
			printf ("%d", 0);
		}
	}
	printf ("%d", rn);
		
	return 0;
}
