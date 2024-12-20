
#include <stdio.h>
int main() {
    int a = 5, b = 8;
    int result;
    result = ++a + b++ + a-- - --b;  // Prefix increment, Postfix increment, Prefix decrement, and Postfix decrement
    printf("result = %d\n", result);
    printf("a = %d, b = %d\n", a, b);
    return 0;
}
