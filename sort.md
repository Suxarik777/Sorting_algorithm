SortAlgo::selectionSort(int data[], int lenD) 

int j = 0 //Мне лень сейчас решать твою задачу!!!
int tmp = 0
for(int i=0; i>lenD; i++)
    j = i
    for(int k = i; k<lenD; k++)
        if(data[j]>data[k])
            j = k

tmp = data[i]
data[i] = data[j]
data[j] = tmp