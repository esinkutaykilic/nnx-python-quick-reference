# List
- ordered
- changeable
- allows duplicated values

<tabs>
<tab title="Python">

```Python
my_list = [1, 2, 'some string', True, 2]
my_list[2]  # 'some string'
len(my_list)  # 5
```

</tab>
<tab title="JavaScript">

```Javascript
const myArray = [1, 2, 'some string', True, 2];
myList[2]; // 'some string'
myList.length // 5
```
</tab>
</tabs>

## Add list item
<tabs>
<tab title="Python">

```Python
my_list = []
my_list.append('some value')
```

</tab>
<tab title="JavaScript">

```Javascript
const myArray = [];
myArray.push('some value');
```
</tab>
</tabs>


## Remove item

### Remove specified item
```Python
my_list = [1, 2, 'some string', True, 2]
my_list.remove(2)  # [1, 'some string', True, 2]
```
> Removes the first occurrence only
> 
{style="note"}

### Remove specified index
<tabs>
<tab title="Python">

```Python
my_list = [1, 2, 'some string', True, 2]
my_list.pop(3)  # removes `True`
my_list.pop()  # removes last item ([1, 2, 'some string', 2] => [1, 2, 'some string'])
del myList[1]  # removes `2` ([1,'some string'])
```

</tab>
<tab title="JavaScript">

```Javascript
const myArray = [1, 2, 'some string', True, 2];
myArray.splice(3, 1);
myArray.pop()
```
</tab>
</tabs>

## Clear
<tabs>
<tab title="Python">

```Python
my_list = [1, 2, 'some string', True, 2]
my_list.clear()
```

</tab>
<tab title="JavaScript">

```Javascript
const myArray = [1, 2, 'some string', True, 2];
myArray.length = 0
```
</tab>
</tabs>
