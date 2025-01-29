# procedural-horse-race

#include <cstdlib>
#include <time>

srand(time(NULL));
coin = rand() % 1;

 void advance(int horseNum, int* horses);
 in a array of horses roll a value between one and zero
 add value to horses position
 
 void printLane(int horseNum, int* horses);
 goes through each horse in the array and prints out lane
 
 bool isWinner(int horseNum, int* horses);
 if horses value reaches a certain value "Track_Length"
 then print that horse as a winner

 void main
