# Leaner-Search
#include &lt;stdio.h>
#include &lt;stdlib.h>  
//-------------Leaner Search------------- 
int lSearch (float d[],int size,float key)
{ 
int index,position=-1,found=0;    
for(index=0;index&lt;size&amp;&amp;!found;index++) 
{         
if (d[index]==key)     
  {       
    found=1;            
    position=index;       
    }     
  }
  return position; 
  
} 

int main() 
{    
float d[10]={9,5,1,3,7,4,6,2,8,10};    
printf("The Position Is %d",lSearch(d,10,4));   
return 0; 
}     



