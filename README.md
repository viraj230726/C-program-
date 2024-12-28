// Input values
printf("Enter the first number: ");
scanf("%d", &a);
printf("Enter the second number: ");
scanf("%d", &b);

// Swapping logic
temp = a;
a = b;
b = temp;

// Output the results
printf("After swapping:\n");
printf("First number: %d\n", a);
printf("Second number: %d\n", b);

return 0;
