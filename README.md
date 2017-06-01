# me-myself
//korupulu 108116043
**hey there!!This is Chandra hasini...**
_I like to sketch,sometimes things around me_.
*To be honest,present I dont have clear clarity on my interest.I want to explore more deep into the things around me and find my interest.This induction process is one of the oppurtunity to explore in coding and learn something new.I hope i will be supported and i will continue my exploring no matter i am in* **SPIDER** 
:sparkles: :sparkles: :cat:
/* Bubble sort code */
 
#include <stdio.h>
 
int main()
{
  int array[100], n, c, d, swap;
 
  printf("Enter number of elements\n");
  scanf("%d", &n);
 
  printf("Enter %d integers\n", n);
 
  for (c = 0; c < n; c++)
    scanf("%d", &array[c]);
 
  for (c = 0 ; c < ( n - 1 ); c++)
  {
    for (d = 0 ; d < n - c - 1; d++)
    {
      if (array[d] > array[d+1]) /* For decreasing order use < */
      {
        swap       = array[d];
        array[d]   = array[d+1];
        array[d+1] = swap;
      }
    }
  }
 
  printf("Sorted list in ascending order:\n");
 
  for ( c = 0 ; c < n ; c++ )
     printf("%d\n", array[c]);
 
  return 0;
}
