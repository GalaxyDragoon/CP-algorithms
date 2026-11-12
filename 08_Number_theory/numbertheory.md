# Finding all the factors of a number : 

```cpp
void Factors(int x) {
    vector<int > v ; 

    for(int i = 1 ; i*i<=x ; i++){
        if(x%i==0){
            v.push_back(i) ;
            v.push_back(x/i) ; 
        }
        if(i*i == x){
            v.pop_back() ; 
        }
    }
    for(auto i : v){
        cout << i << " " ; 
    }
}
```

# Finding the total number of a number : 

```cpp

```
