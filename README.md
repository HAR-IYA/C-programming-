#include <stdio.h>

int main()
{
    int n, i, num, largest;

    printf("Enter the number of elements: ");
    scanf("%d", &n);

    printf("Enter %d numbers:\n", n);
    scanf("%d", &largest);

    for (i = 2; i <= n; i++)
    {
        scanf("%d", &num);

        if (num > largest)
        {
            largest = num;
        }
    }

    printf("Largest number = %d", largest);

    return 0;
}
