### 列表

#### 简单操作

```python
列表表示：movies = ["","",""]
访问列表：print(movies[1])
列表长度：print(len(movies))
末尾增加数据项：movies.append("aa")
末尾删除数据项：movies.pop()
末尾增加数据项集合：movies.extend(["","",""])
删除特定数据项：movies.remove("aa")
特定位置前增加一个数据项：movies.insert(1,"")
```

#### 循环

```python
//for循环
for m in movies:
    print(m)
    
//while循环
count = 0
while count < len(movies):
    print(movies[count])
    count = count + 1
    
```

#### 嵌套列表

```python
movies = ["0","1","2",["30","31",["320","321"]]]
print(movies[3][2][1])

//判断movies是不是list类型数据，是返回true,否返回false
判断特定标识符：isinstance(movies,ist)
```
