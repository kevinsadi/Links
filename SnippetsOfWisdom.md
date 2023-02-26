# Snippets of Wisdom
Some code snippets of clever programming implementations. The code examples will have different languages depending on the task.

## Geometry
* Get all the edges of a list of vertices. Includes the wrap around as well. 
```cpp

#include <iostream>
#include <vector>

using namespace std;

int main()
{
    vector<int> arr = {1, 2, 3, 4};
    for (int i = 0, j = arr.size() - 1; i < arr.size(); j = i++)
    {
        // CCW directed edge AB, assuming pts are all CCW
        int A = arr[j];
        int B = arr[i];
    }
    return 0;
}

```