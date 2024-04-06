# Dictionary

- ordered
- changeable
- **not allows duplication**

> As of Python version 3.7, dictionaries are ordered. In Python 3.6 and earlier, dictionaries are **unordered**.
> 
{style="warning"}

<tabs>
<tab title="Python">

```Python
my_dictionary = {
    'name': 'Marty',
    'surname': 'McFly',
    'travel_to': 2015
}

len(my_dictionary)  # 3
```

</tab>
<tab title="JavaScript">

```Javascript
const myObject = {
    name: 'Marty',
    surname: 'McFly',
    travelTo: 2015
};

Object.keys(myObject).length; // 3 
```
</tab>
</tabs>


## Access items

<tabs>
<tab title="Python">

```Python
my_dictionary = {
    'name': 'Marty',
    'surname': 'McFly',
    'travel_to': 2015
}

my_dictionary['name']  # 'Marty'
my_dictionary['date']  # raise error

my_dictionary.get('name') # 'Marty'
my_dictionary.get('date') # None

key = 'name'
my_dictionary[key]  # 'Marty'
my_dictionary.get(key)  # 'Marty'
```

</tab>
<tab title="JavaScript">

```Javascript
const myObject = {
    name: 'Marty',
    surname: 'McFly',
    travelTo: 2015
};

myObject['name']; // 'Marty'
myObject['date']; // undefined

myObject.name; // 'Marty'
myObject.date; // undefined

const key = 'name';
myObject[key]; // 'Marty'
```
</tab>
</tabs>


## Change values

<tabs>
<tab title="Python">

```Python
my_dictionary = {
    'name': 'Marty',
    'surname': 'McFly',
    'travel_to': 2015
}

my_dictionary['travel_to'] = 1955
my_dictionary['travel_to'] = '1955'

my_dictionary.update({
    'travel_to': 1885,
    'aka': 'Clint Eastwood'
})
```

</tab>
<tab title="JavaScript">

```Javascript
const myObject = {
    name: 'Marty',
    surname: 'McFly',
    travelTo: 2015
};

myObject.travelTo = 1955; // 'Marty';

myObject = {
    ...myObject,
    travelTo: 1885,
    aka: 'Clint Eastwood'
};

```
</tab>
</tabs>


## Remove items

<tabs>
<tab title="Python">

```Python
my_dictionary = {
    'name': 'Marty',
    'surname': 'McFly',
    'travel_to': 2015
}

my_dictionary.pop('surname')
my_dictionary.pop('surname')  # raise error
del my_dictionary['year']
del my_dictionary['year']  # raise error
```

</tab>
<tab title="JavaScript">

```Javascript
const myObject = {
    name: 'Marty',
    surname: 'McFly',
    travelTo: 2015
};

delete myObject.surname
```
</tab>
</tabs>



