!!Average1--You have to multiply those weight with x & y because
            if you are calculating GPA of student,then credit(here Weight) per subject is not same.

  #include <stdio.h>
    int main()
    {
        float x,y,MEDIA;
        
        scanf("%f %f", &x, &y);
        
        MEDIA = (x*3.5+y*7.5)/(3.5+7.5);
        
        printf("MEDIA = %.5f\n", MEDIA);
        
        return 0;
    }   
