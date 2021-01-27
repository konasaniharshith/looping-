# looping-
first looping program
#incint main()
int main()
{
int i, j, N;
scanf("%d", &N);
for(i=1; i<=N; i++)
{
for(j=2; j<=i; j++)
{
if(j % 2 == 1)
{
printf("1");
}
else
{
printf("0");
}
}
printf("\n");
}
return 0;
}
