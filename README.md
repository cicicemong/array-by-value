# array-by-value


     #include <stdio.h>
     #include <stdlib.h>
     int main()
     {
    int bil[7],i;
    printf ("Elemen 1 ? "); scanf ("%d",&bil[0]);
    bil[1] = 5;
    bil[2] = bil[1] + 20;
    for (i=4;i<7;i++) bil[i] = i*10;
    bil[3] = bil[bil[1]];
    for(i=0;i<7;i++) printf("bil[%d]= %d dan alamatnya : %X\n",i,bil[i],&bil[i]);
    return 0;
    }
