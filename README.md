# include <stdio.h>
# include <string.h>

int main()
{
    int n;
    char s[100];
    printf("Dati sirul de caractere\n");
    fgets(s, sizeof(s), stdin);
    n = strlen(s);
    printf("\n");
    printf("Sirul initial:");
    puts(s);
    printf("sirul modificat:");
    for (int i=0;i<n;++i)
    {
        if(s[i]=='z')
        {
            s[i] == 'A';

        }
    }

    printf("\n");
    puts(s);
    printf("\n");
}
