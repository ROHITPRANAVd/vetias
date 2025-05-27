#include <stdio.h>

int main() {
    int n, q;
    scanf("%d %d", &n, &q);

    int arr[n];

    for(int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }
    for(int i = 0; i < q; i++) {
        int L, R;
        int found = 0;
        scanf("%d %d", &L, &R);

        for(int j = 0; j < n; j++) {
            if(arr[j] >= L && arr[j] <= R) {
                found = 1;
                break;
            }
        }
        printf("%d ", found);
    }

    return 0;
}
