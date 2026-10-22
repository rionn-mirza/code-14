#include <stdio.h>

int main() {
    int n, i;

    printf("20 (N): ");
    scanf("%d", &n);

    printf("1 to 20 %d even number :\n", n);
    for(i = 1; i <= n; i++) {
        if(i % 2 == 0) {
            printf("%d ", i);
        }
    }
    printf("\n");

    return 0;
}
