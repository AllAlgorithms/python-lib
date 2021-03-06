# Quicksort

A quicksort is a quicker method of sorting, and there are four different ways of implementing it.  The example given uses a pivot point.

A pivot point is created in the middle of an array, and all larger items go after the pivot point, and smaller items are placed in front
of the pivot point.

The pivot point is then moved to the middle of either the smaller or larger items, and the sort is run again on that half.

This continues over and over again until everything is in the proper place.

## Install

```
pip install allalgorithms
```

## Usage

```py
from allalgorithms.sorting import quicksort

arr = [77, 2, 10, -2, 1, 7]

print(quicksort(arr))
# -> [-2, 1, 2, 7, 10, 77]
```

## API

```
quicksort(array)
```

> Returns a sorted array

##### Params:

- `array`: Sorted Array
