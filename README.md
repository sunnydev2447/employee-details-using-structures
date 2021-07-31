    #include <stdio.h>
 
    struct employee
    {
    char    name[30];
    char   dept[30];
    int     empnum;
    float   salary;
    };
 
    int main()
    {
    struct employee emp;
    
    printf("\nEnter details :\n");
    printf("Name ?:");          
    scanf("%s",&emp.name);
    printf("dept ?:");             
    scanf("%s",&emp.dept);
    printf("empnum?:");           
    scanf("%d",&emp.empnum);
    printf("Salary ?:");       
    scanf("%f",&emp.salary);
     
    printf("\nEntered detail is:");
    printf("Name: %s"   ,emp.name);
    printf("dept:%s",emp.dept);
    printf("Num: %d"     ,emp.empnum);
    printf("Salary: %f\n",emp.salary);
    return 0;
    }
