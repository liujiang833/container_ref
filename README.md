# Syntax Lookup

## Table of Content

### Containers

- [vector](#vector)
- [list](#list)
- [stack](#stack)
- [queue](#queue)
- [heap](#heap)
- [map](#map)
- [unordered_map](#unordered_map)
- [set](#set)
- [unordered_set](#unordered_set)

### Useful Functions

- [C++ split string](#C++ split string)



#### Vector

| Java | C++  | Python |
| ---- | ---- | ------ |
|      |      |        |



#### C++ split string

Here is a quick way to do string splitting in c++ using STL. Then you don't need to use ```find``` that can get you astray. 

```C++
vector<string> mysplit(string&s, char delimiter){
    vector<string> res;
    istringstream ss(s);
    string hold;
    while(getline(ss,hold,delimiter)){
       res.push_back(move(hold)); 
    }
    return res;
}
```

