#include <stdio.h>

int main() {
int n, key, i;
int pos = -1;
if (scanf("%d", &n) != 1) return 1; 
int arr[n]; 
for (i = 0; i < n; i++) {
scanf("%d", &arr[i]);
}
if (scanf("%d", &key) != 1) return 1; 
for (i = 0; i < n; i++) {
if (arr[i] == key) {
pos = i;
break;
}
}
if (pos != -1) {
printf("found at position %d\n", pos);
} else {
printf("%d not found\n", key);
}
return 0;
}


