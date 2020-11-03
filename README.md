# candels
In this task I have to find the highest value in the array and write the number of highest value.

int birthdayCakeCandles(vector<int> candles,int n) {
int m = 0;
int count = 0;
for (int i=0;i<n;i++)
{
if (candles[i]>m) {m=candles[i];}
}
for (int i=0;i<n;i++)
if(candles[i]==m) {count=count+1;}
return count;
}

